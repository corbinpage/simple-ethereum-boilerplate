# Simple Ethereum Starter - Node
This simple boilerplate provides a super easy starter app for using ethereum smart contracts in a web app. It is intended for web developers familiar with Node and is based on the [Truffle webpack demo](https://github.com/trufflesuite/truffle-init-webpack).

## Dependencies
| Command | Why |
| --- | --- |
| Install Truffle with `npm install -g truffle` | Truffle will help us... |
| Install testrpc with `` | testrpc will help us... |
| Install Metamask with `` | Metamask will help us... |

## Get Started
| Command | What's going on |
| --- | --- |
| `git clone git@github.com:corbinpage/simple-ethereum-starter-node.git; cd simple-ethereum-starter-node` | Clones this repo and opens it up |
| `npm install` | Installs all dependencies in package.json |
| `truffle compile` | Compiles all smart contracts in `/contracts` (written in Solidity) into Javascript objects that your app will interact with. The resulting objects can be found in `/build/contracts` |
| Open up a new tab and run `testrpc -a` | Starts a local ethereum network for using during development. The parameter `-a` means to create a test user account to use on the network, which is running on http://localhost:8545. [More info](http://truffleframework.com/docs/getting_started/compile). |
| `truffle migrate` | Deploys all your smart contracts to the local test network. Your web app can now interact with the smart. [More info](http://truffleframework.com/docs/getting_started/migrations). |
| `npm run dev` | Starts a local webserver running a simple web app at http://localhost:8080. The web app has functionality to interact with the smart contracts deployed to the local test network in `/app/javascripts/app.js`. |

## App Functionality
| Functionality | What's going on |
| --- | --- |



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
