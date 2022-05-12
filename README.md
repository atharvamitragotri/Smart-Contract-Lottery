# Smart Contract Lottery
Simple lottery smart contract using the brownie framework.
1. Users can enter lottery with ETH based on a USD fee (uses Chainlink price feed)
2. The admin gets to choose when the lottery is over
3. The lottery will select a random number using the Chainlink VRF contract.
4. We test the contract using the following : a mainnet-fork, by deploying mocks for the local development environment, and using the kovan testnet.
