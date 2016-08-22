*** Ethereum smart contract dev env

- ethereumjs-testrpc

- solc

- truffle

*** docker run -it --name ethereum-dev -p 8080:8080 -p 8545:8545 neverlock/ethereum-dev

*** Example

- cd /root

- mkdir test

- cd test

- truffle init

- Edit truffle.js host: “localhost”, -> host: “HOST ‘s IP”,

- truffle compile

- truffle migrate

- truffle test

- truffle serve // server at localhost:8080
