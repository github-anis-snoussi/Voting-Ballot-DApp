### Dapp development process
1. Analyze problem
2. Prototype smart contract on remix
3. Develop and test on truffle
4. Deploy

## Commun commands
1. truffle init
:used to get the empty project
2. truffle compile
:used to compile the project and put compiled files in a build dir
3. truffle develop
:used to deploy to the local blockchain
4. truffle migrate --reset
:use the deploy script in the migration dir to deploy our smart contract 
(--reset is for removing any previous versions of the smart contract => CAN'T BE DONE IN PRODUCTION OBVIOUSLY)
5. truffle test
:run test scripts in test dir.. duhh !
