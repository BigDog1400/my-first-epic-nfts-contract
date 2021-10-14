# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
```
# Deployment

To deploy the contract you will need to add .env with the required enviroment variables. Also, you can change the value in the deploy.js that is been passed to the deploy function if you want to set another max amount of NFTs availables.

To deploy in a rinkeby testnet:
```npx hardhat run scripts/deploy.js --network rinkeby```
