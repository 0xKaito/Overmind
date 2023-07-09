# Broker it Yourself


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Broker it Yourself is to build a peer-to-peer exchange for non-custodial trading of Aptos assets for cash.

## Overview
The P2P trading quest consists of the following key components:

-Smart Contracts: The core functionality of the trading platform is implemented through smart contracts on the blockchain. These contracts handle offer creation, matching, asset transfers, and other trading operations.

Modules: The project is organized into different modules to encapsulate related functionality. Each module represents a logical unit of the trading platform, such as offer management, asset management, user authentication, and transaction processing.

Off-Chain Asset Management: The quest involves managing off-chain assets, specifically USD. The platform should provide functionalities to handle USD transactions off-chain, such as fiat payment gateways or integrations with external payment providers.

On-Chain Asset (APT) Management: The quest integrates with the on-chain APT asset, allowing users to hold, transfer, and trade APT tokens on the blockchain. This involves interacting with the APT token smart contract and leveraging its functionality.

Order Creation: Users can create offers specifying the amount of APT they want to buy or sell and the corresponding amount of USD they are willing to give or receive. These offers are stored on-chain and become visible to potential counterparties.

Offer Matching: The platform matches buy and sell offers based on their pricing and quantity. When a match is found, the platform initiates the asset transfer process, ensuring the secure exchange of APT and off-chain USD.

Transaction Settlement: Once an offer is matched, the platform facilitates the settlement process, ensuring that the agreed-upon amounts of APT and USD are transferred between the participating users. This may involve off-chain payment verification and on-chain asset transfers.

## Tech

Broker it Yourself uses a move open source projects to work properly:

- [Move] - Move is a programming language for writing safe smart contracts originally developed at Facebook to power the Diem blockchain. Move is designed to be a platform-agnostic language to enable common libraries, tooling, and developer communities across diverse blockchains with vastly different data and execution models. Move's ambition is to become the "JavaScript of web3" in terms of ubiquity--when developers want to quickly write safe code involving assets, it should be written in Move.

## Installation

# Visual Studio Code:

Visual Studio Code ( [Download here](https://code.visualstudio.com/) )

1.) Installing the move-analyzer language server 

- Invoke:

```rust
cargo install --git https://github.com/move-language/move move-analyzer --features "address32"
```

- Confirm correct installation, invoke the below function and confirm expected output:

```rust
move-analyzer --version
```

**Expected output:** `move-analyzer 1.0.0`

2.) Installing the *move-analyzer* Visual Studio Code extension

- Install Visual Studio Code Extension `move-analyzer`
- Open any file that ends in `.move`. Or to create a new file, click **Select a language**, and choose the **Move** language. As you type, you should see that keywords and types appear in different colors.

### Troubleshooting Visual Studio Code?

Refer to the official documentation of *move-analyzer* ( [Official documentation](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer) ) 

---

# IntelliJ IDE:

IntelliJ IDE ( [Download here](https://www.jetbrains.com/idea/download) ) -  **Choose the community version [FREE]** 

1.) Install the *Move Language* plugin for IntelliJ ( [Plugin link](https://pontem.network/move-intellij-ide-plugin) )

- Search & Install `Move Language` **on IntelliJ’s plugin marketplace

### Troubleshooting IntelliJ IDE?

Refer to the official documentation of the Move Language plugin ( [Official documentation](https://github.com/pontem-network/intellij-move) [](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer)) or ( [Unofficial Move IntelliJ IDE tutorial](https://www.notion.so/Intellij-Move-IDE-Tutorial-c48010f17a5a4118822239541d01febb?pvs=21) )
# Visual Studio Code:

Visual Studio Code ( [Download here](https://code.visualstudio.com/) )

1.) Installing the move-analyzer language server 

- Invoke:

```rust
cargo install --git https://github.com/move-language/move move-analyzer --features "address32"
```

- Confirm correct installation, invoke the below function and confirm expected output:

```rust
move-analyzer --version
```

**Expected output:** `move-analyzer 1.0.0`

2.) Installing the *move-analyzer* Visual Studio Code extension

- Install Visual Studio Code Extension `move-analyzer`
- Open any file that ends in `.move`. Or to create a new file, click **Select a language**, and choose the **Move** language. As you type, you should see that keywords and types appear in different colors.

### Troubleshooting Visual Studio Code?

Refer to the official documentation of *move-analyzer* ( [Official documentation](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer) ) 

---

# IntelliJ IDE:

IntelliJ IDE ( [Download here](https://www.jetbrains.com/idea/download) ) -  **Choose the community version [FREE]** 

1.) Install the *Move Language* plugin for IntelliJ ( [Plugin link](https://pontem.network/move-intellij-ide-plugin) )

- Search & Install `Move Language` **on IntelliJ’s plugin marketplace

### Troubleshooting IntelliJ IDE?

Refer to the official documentation of the Move Language plugin ( [Official documentation](https://github.com/pontem-network/intellij-move) [](https://marketplace.visualstudio.com/items?itemName=move.move-analyzer)) or ( [Unofficial Move IntelliJ IDE tutorial](https://www.notion.so/Intellij-Move-IDE-Tutorial-c48010f17a5a4118822239541d01febb?pvs=21) )
## License


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
