---
date: 2020-10-03
thumbnail: "/uploads/quiz.png"
title: Start by AfricaHacks
categories:
- website
- africa
- app
- design
project_bg_color: ''
project_fg_color: ''

---
Many people have asked me how [I](https://uchibeke.com/) got started with Blockchain, so I will be breaking it down in the post to share some insights for those looking to break into the space. I will share insights and options to help total a beginner become a Blockchain Developer. First, the basics.

## Bitcoin is not Blockchain

Although Bitcoin was the first application of Blockchain technology, the Bitcoin blockchain is just one implementation of Blockchain technology. Blockchain is more than just cryptocurrencies. Read my [Blockchain beyond Bitcoin](https://dev.to/uu/blockchain-beyond-bitcoin-for-africa-and-north-america-342m) on [Dev](http://dev.to/) to learn more.

## Programming Languages to learn

Some popular programming for building Blockchain applications include Javascript (Nodejs), C++, Rust, Python, and Go. Bitcoin is written mostly in C++, there’s a Go implementation of Ethereum and Hyperledger Fabric, by the Linux Foundation is written firstly in Go.

## Blockchain Paths to follow

There are two broad areas of Blockchain to focus on:

* **Private Blockchain**: Broadly speaking, in private blockchains, we have all the benefits of Blockchain, but access to the transactions is restricted to authorized parties. For permissioned and private blockchains, access to the network is limited to invited parties. Entreprises like Banks prefers this because they have some control while also reaping the benefits of Blockchain. [Hyperledger Fabric](https://www.hyperledger.org/use/fabric) is an example of a Private Blockchain (DLT)
* **Public Blockchain**: As the name implies, in public blockchains, transactions and history are available to anyone to see. Bitcoin and Ethereum are examples of public blockchains.

## Getting Started with a Path

### Private Blockchain

#### Hyperledger

Currently, you can build on Hyperledger with NodeJs, Go, or Java. You can either use an API or an SDK. See the [Getting Started Guide](https://hyperledger-fabric.readthedocs.io/en/release-2.2/getting_started.html). Some of the Official language APIs are below:

* **NodeJS**: [https://github.com/hyperledger/fabric-chaincode-node](https://github.com/hyperledger/fabric-chaincode-node "https://github.com/hyperledger/fabric-chaincode-node")
* **Java**: [https://hyperledger-fabric.readthedocs.io/en/release-2.2/getting_started.html](https://github.com/hyperledger/fabric-chaincode-node "https://github.com/hyperledger/fabric-chaincode-node")
* **Go**: [https://github.com/hyperledger/fabric-contract-api-go](https://github.com/hyperledger/fabric-chaincode-node "https://github.com/hyperledger/fabric-chaincode-node")

### Public Blockchain

#### Ethereum

You can build Ethereum Smart contracts with Python, Javascript, and others.

See the [Official Developer Resources](https://ethereum.org/en/developers/) page and [Get started](https://ethereum.org/en/build/) guide.

With Ethereum, you can build with one of the existing Smart Contract Languages:

* **Solidity**: [https://solidity.readthedocs.io/en/v0.7.0/](https://github.com/hyperledger/fabric-chaincode-node "https://github.com/hyperledger/fabric-chaincode-node") or
* **Vyper**: [https://vyper.readthedocs.io/en/stable/](https://github.com/hyperledger/fabric-chaincode-node "https://github.com/hyperledger/fabric-chaincode-node")

##### EVM (Ethereum Virtual Machine)

Ethereum Smart Contract languages like Solidity and Vyper run on the EVM (Ethereum Virtual Machine), just like NodeJS runs on [v8](https://v8.dev/). Just like you do not need to know the implementation details of v8 to develop Nodejs apps, you also do not need to know how Ethereum, EVM, or the Smart Contract Engine is implemented to develop an Ethereum solution. [Read more](https://ethereum.org/learn/#ethereum-basics) about the EVM and Ethereum basic [here](https://ethereum.org/learn/#ethereum-basics)

## Action Items

* Pick a path: You can either go with Private Blockchains or Public Blockchains.
* Pick a Blockchain to focus on: If you pick the Public way, consider Ethereum, but if you go the private path, consider Hyperledger, specifically, Hyperledger Fabric.
* Pick an SDK or API: For the selected Blockchain, pick an SDK or API that is written in the language that you understand and find the documentation and example projects on Github.
* Build a project to solve a problem you are passionate about: find that working one a project is an excellent way to learn, especially if you are building something that aligns with your interests.
* Please show me what you built! Mention [@Uchibeke](https://github.com/uchibeke/) in Github issues or PR or mention [@UchiUchibeke](https://twitter.com/uchiuchibeke) on Twitter and I will review and leave feedback.

I can’t wait to see what you build!