
ETHEREUM VIRTUAL MACHINE [EVM](https://ethereum.org/en/developers/docs/evm/)

#

This project uses the truffle suite for development and testing.

#
# Truffle 
- [Truffle Suite](https://trufflesuite.com/)

### create truffle project
`
npm install truffle
`
### init truffle project
`
npm install truffle
`
### compile truffle project
`
npx truffle compile
`
### start truffle
`
npx truffle develop
`

# Contracts

#### BEP20.sol

BEP 20 Token for the Binance Smart Chain.
- [BEP20: Tokens on Binance Smart Chain](https://github.com/bnb-chain/BEPs/blob/master/BEP20.md)

#### ownable.sol

Contract module which provides a basic access control mechanism, where there is an account (an owner) that can be granted exclusive access to specific functions.

#### context.sol

Provides information about the current execution context, including the sender of the transaction and its data. While these are generally available via msg.sender and msg.data, they should not be accessed in such a direct manner.

#### myPayment.sol

The contract can receive eth and will record all transactios. The owner of the contract can withdraw funds at any time.
