# **Solidity Joint Savings**
This smart contract hosts join saving accounts and consists of ability to deposit and withdraw funds from the account.

---

## Technologies
This application is developed on the *Python 3.7.11 version*:


* [Remix IDE](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null) - For building and testing smart contracts that you create with Solidity.

---

## Installation Guide
This app can be run in any browser using Remix IDE and upload the sol file.

---

## Usage

A Solidity smart contract that governs usage of a joint savings account. The contract accepts multiple user addresses and supports Ether transactions.

There are three functions in the contract with differing inputs. Deposit: Takes a value in wei, gwei, finney, or ether and credits the amount to the contract balance. Set Accounts: Takes two account addresses to be used for withdrawal. Withdraw: Takesan amount in Wei and a recipient address.


The contract allows the user to check the contract balance, view the last address to withdraw, and the last withdrawal amount.

The Joint Savings Smart Contract includes requirements to ensure the recipient address matches one of the accounts provided. There is a requirement to ensure there are sufficient funds in the contract to support the withdraw transaction, along with a fallback function.

Screenshots from successful transactions are contained within the Image folder of this repository.

---

## Contributors

*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---

## License
UC Berkeley

---