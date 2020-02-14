# GoDapp
Writing a DApp typically involves two steps:

Writing the contract code in Solidity or a similar language.
Writing the code that interacts with the deployed smart contract.
The Go Ethereum SDK allows us to write code for the second step in the Go programming language.

The code is written to interact with the smart contract usually performs tasks like serving up a user interface that allows the user to send calls and messages to a deployed contract.

Go allows us to write that application code with the same safety features that Solidity gives, plus other perks like:

An extensive library of tools to interact with the Ethereum network.
Tools to transpile Solidity contract code to Go, allowing direct interaction with the contract ABI (Application Binary Interface) in a Go application.
Allows us to write tests for contract code and application using Go's testing libraries and Go Ethereum's blockchain simulation library. Meaning unit tests that we can run without connecting to any Ethereum network, public or private.
