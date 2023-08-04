# web3foretellercontract

The Web3 ForeTeller smart contract generates a random "salt" value based on events from the Web3 world.

This smart contract has two main usage scenarios:

1. getRandomNumber() - returns a random value free of charge by fetching a random salt from the Web3 world.
2. getRandomSaltFromGasBurn() + getRandomNumberWithGas() generate Web3 salt based on the burned gas and the current block number.
