# Smart Agents marketplace

A decentralised compute model is proposed that uses a competitive bidding system to pay providers for their computing power, which is used to power AI. \
\
Users own TRIN tokens, and the more tokens they have, the more AI computing power they can access. This model aims to improve the user experience by offering fast, accurate, and free AI computations while protecting against fake user attacks and maintaining privacy.

**Simplified Overview:**

* **Users**: Individuals or entities that use MOR tokens to access AI computations without directly paying for each use. They send requests for computations to a system called the Router.
* **Providers**: They offer computing power and get paid in MOR tokens, but only if their service is fast and meets quality standards.
* **Router**: A program that processes and matches users' requests with providers. It does not handle the MOR tokens or see the content of requests and responses to ensure privacy.
* **Compute Contract**: A smart contract that manages the distribution and payment of MOR tokens based on the computing power provided.

**How it Works:**

1. Users with MOR tokens send a request for computation to the Router.
2. The Router chooses the provider who offers the lowest price for the computation.
3. Providers must pass a liveness check to prove they are operational.
4. If they pass, they are connected to the user to perform the computation.
5. Users receive their results, and if they're satisfied, they report back to the Router.
6. Satisfied services lead to providers getting credit, and they can later ask for payment in MOR tokens from the Compute Contract.

**Payment System:**

* The Compute Contract has a daily budget, a percentage of its MOR token balance, to pay providers.
* Users' access to computing power is based on how many MOR tokens they have and a rate that determines how much computing power each token can get per day.
* If a user requests too much computing power beyond their token balance, the Router will deny the request.

**Quality Control:**

* Users report if the computation was satisfactory. Providers that fail to meet standards may not get paid or might receive a penalty.
* The Router tracks the speed and quality of each computation to ensure providers are prompt and accurate.

**Economic Model:**

* The system is designed to make sure MOR tokens have real value by providing access to AI computations.
* It avoids wasting tokens on unused computing power by only paying providers when there is actual demand.
* The model is scalable because it limits the number of necessary transactions on the blockchain.

In summary, the Yellowstone Compute Model incentivizes efficient, fast, and cost-effective AI computations, rewards providers for quality service, and offers users access to AI without per-use fees, all within a secure and private framework. Original paper by Eric Voorhees [here](https://github.com/MorpheusAIs/Docs/blob/main/!KEYDOCS%20README%20FIRST!/Yellowstone%20Compute%20Model.md).
