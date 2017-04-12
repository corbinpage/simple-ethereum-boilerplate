# Simple Ethereum Starter - Node
This simple project provides a super easy starter app for using ethereum smart contracts in a web app. It is intended for web developers familiar with Node and is based on the [Truffle webpack demo](https://github.com/trufflesuite/truffle-init-webpack).



## Dependencies
1. truffle
1. Metamask
npm
git
testrpc


## Get Started
| Command | What's going on |
| --- | --- |
| `git clone git@github.com:corbinpage/simple-ethereum-starter-node.git; cd simple-ethereum-starter-node` | Clones this repo and opens it up |
| `npm install` | Installs all dependencies in package.json |
| `truffle compile` | Compiles all smart contracts in /contracts (written in Solidity) into Javascript objects that your app will interact with. The resulting objects can be found in /build |


have your changes rebuilt automatically.\n\nMake sure you have an Ethereum client like the ethereumjs-testrpc running on http://localhost:8545

| Open up a new tab and run `testrpc -a` |  |

| `truffle migrate` | Deploys all your smart contracts to the testnet running on http://localhost:8545 |
| `npm run dev` | List all new or modified files |




## File Structure


1. Metamask
1. Got to http://localhost:8080 in a browser.

## Tools

## More Depth


Example webpack project with Truffle. Includes contracts, migrations, tests, user interface and webpack build pipeline.

## Building and the frontend

1. First run `truffle compile`, then run `truffle migrate` to deploy the contracts onto your network of choice (default "development").
1. Then run `npm run dev` to build the app and serve it on 

## Possible upgrades

* Use the webpack hotloader to sense when contracts or javascript have been recompiled and rebuild the application. Contributions welcome!

## Common Errors

* **Error: Can't resolve '../build/contracts/MetaCoin.json'**

This means you haven't compiled or migrated your contracts yet. Run `truffle compile` and `truffle migrate` first.
