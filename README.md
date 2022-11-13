# Sample Hardhat Project

This is a project based on the FreeCodeCamp tutorial

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

To run it:

1. Rename .env.example file to .env
2. Fill the .env file with the private key of a metamask's wallet (with no real fund on it!! https://goerlifaucet.com/)
3. Fill the .env file with an etherscan api key : https://etherscan.io/myapikey
4. Fill the .env file with a coinmarketcap api key : https://pro.coinmarketcap.com/account
5. Run "yarn compile" command in the command prompt
6. Run "yarn hardhat run scripts/deploy.js --network hardhat" command in the command prompt for a local deployment
7. Run "yarn hardhat run scripts/deploy.js --network goerli" command in the command prompt for a testnet deployment

To run the tests :
1. Run "yarn hardhat test" command in the command prompt
2. If you want to launch a gasReporter, change the "gasReporter->enabled" propertie of hardhat.config.js file from false to true

To run the code coverage :
1. Run "yarn hardhat coverage" command in the command prompt
