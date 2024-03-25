# Smart Agent installation

## Disclaimer

This is the first version of Morpheus that brings together an open source LLM (defaults to Llama2) + connecting a user's Meta Mask wallet + executing on chain transactions via a ETH focused Smart Agent.

After connecting Morpheus to your Meta Mask, you can test it by taking basic actions such as:

* "What is my balance?"
* "What is my address?"
* "Send ETH to Ethereum Address"

Morpheus doesn't have a connection to a block explorer or price oracles yet, so it can't answer general transactions questions. It just answers the above examples based on info from the Meta Mask wallet you connect.

**Warnings:**

* Review all transactions before approving them. The LLM makes mistakes, you have human wisdom.
* Seriously, double check all actions in the Meta Mask interface before sending money.
* This is an experimental release and the ETH Smart Agent may try and send your money into a black hole.
* Gas costs are high on Ethereum. Consider testing out 0.0.6 using the Sepolia testnet or Arbitrum.
