A resource for developers preparing to build on Fuel.

## Getting Help

The fastest way to get help is by posting a question on the Fuel forum. Join the forum [here](https://forum.fuel.network/). To help you as efficiently as possible, please ensure the following:

1. state instructions for reproducing the issue clearly
2. add the output logs if possible
3. add the `hackathon` tag in your forum post

> 💡 It is recommended to use VS code and download the [Live Share extension](https://code.visualstudio.com/learn/collaboration/live-share) so that our team can easily hop into your code to provide support.

## FAQs

1. [What is Fuel?](https://forum.fuel.network/t/welcome-what-is-fuel/7)
2. [Can I run my own node?](https://forum.fuel.network/t/can-i-run-my-own-node/100)
3. [What is Sway?](https://forum.fuel.network/t/about-the-sway-category-what-is-sway/25)
4. [How do I deploy my Sway contract?](https://forum.fuel.network/t/how-do-i-deploy-my-sway-contract/99)
5. [How do I test my Sway contract](https://forum.fuel.network/t/how-do-i-test-my-sway-contract/97)
6. [How can I check the max gas allowed for a transaction?](https://forum.fuel.network/t/how-do-i-check-the-max-gas-allowed-for-a-transaction/1557)
7. [Does Sway have a fallback equivalent](https://forum.fuel.network/t/does-sway-have-a-fallback-equivalent/104)
8. [Can I declare a `Vec` in a `storage` block?](https://forum.fuel.network/t/can-i-declare-a-vec-in-a-storage-block/115)
9. [What are predicates in Sway?](https://forum.fuel.network/t/what-is-a-predicate/36)
10. [Where can I find the Sway standard library and instructions for how to use it?](https://forum.fuel.network/t/does-sway-have-a-standard-library/719)

Check out more questions asked by the Fuel community on our [forum](https://forum.fuel.network/)!

## Developer Resources

### Developer Quickstart

Follow the [Developer Quickstart](https://fuellabs.github.io/fuel-docs/master/developer-quickstart.html) in the Fuel Book to learn how to:
- Set up the Fuel development environment
- Define an ABI
- Write a Sway smart contract
- Test the contract using the Rust SDK
- Deploy the contract to the testnet
- Write a frontend using the TS SDK

### Sway Book

Follow [Sway Book](https://fuellabs.github.io/sway/latest/) for the official Sway documentation and learn about all things Sway—Fuel's own Rust-inspired DSL. Learn various concepts such as:
- Sway program types
- Language basics
- Contract storage, native assets, & access control.
- Storage vectors & storage maps
- Testing, & more!

### TS SDK

You can build a frontend for your Sway smart contracts using the TypeScript SDK. Checkout the [TS SDK Docs](https://fuellabs.github.io/fuels-ts/) to understand how the SDK lets you:
- Deploy and call contracts
- Generate contract types with TypeChain
- Build and send transactions
- Encode and decode contract ABIs

### Rust SDK

You can test your Sway smart contracts using the Rust SDK. Read the official [Rust SDK Docs](https://fuellabs.github.io/fuels-rs/latest/) to understand various concepts such as:
- Compiling, deploying, and testing Sway contracts
- Using the testnet or running a local Fuel node
- Crafting and signing transactions with hand-crafted scripts or contract calls
- Generating type-safe Rust bindings of contract ABI methods
- And more!

> ❗️Note that `fuels-rs` is still under active development

### Workshops, Guides, & Examples!

1. [Learnsway-web3rsvp](https://github.com/FuelLabs/learnsway-web3rsvp)
2. [Learnsway-marketplace](https://github.com/FuelLabs/learnsway-marketplace)
3. [Sway-farm](https://github.com/sarahschwartz/sway-farm)
4. [Sway-apps](https://github.com/FuelLabs/sway-applications)

### Awesome Fuel

Check out [Awesome Fuel](https://github.com/FuelLabs/awesome-fuel)—A collection of community resources such as podcasts, articles, presentations, events, & more related to Fuel.

## Inspiration - Existing Projects on Fuel

| Name | Description | Link | Presented At |
|---|---|---|---|
|  Authsome | Authsome implements a multi-signature wallet using the predicate system of the Fuel VM and Sway programming language. This multi-signature wallet is then used as the basis for an pluggable auth infrastructure, similar to Web3Auth. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9tv1epm14319401w1mf7ltuhm/idea | ETH Lisbon 2022 |
|  Fuel Price Oracle | Token price (ETH, DAI) oracle for Fuel blockchain. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9upb5rc53868701tpdvj6n05d/idea | ETH Lisbon 2022 |
|  Capitalist Pigs | Gamify staking for fees in a DeFi project using a set of NFTs. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9uljahi38530301ttxkbkask0/idea | ETH Lisbon 2022 |
| Nuclear Swap | Stablecoin AMM	| https://github.com/mauricewbr/nuclear_swap | Beyond Monolithic Hakathon |
| Kitelife | Multisig Predicate | https://github.com/recizk/multisig-predicate | Beyond Monolithic Hakathon |
| Fuel Ferret | Oracle | https://github.com/Ferret-san | Beyond Monolithic Hakathon |
| FRC721 | NFT Token contract on Fuel | https://github.com/SwayStar123/FRC721/tree/master | Beyond Monolithic Hakathon |
| Emacs plugin | Emacs plugin for Sway | https://github.com/hhamud/sway-mode | Beyond Monolithic Hakathon |
| Chrome Wallet Extension | Wallet extension for chrome | https://github.com/00vian/fision-wallet-hackaton-fuel | Beyond Monolithic Hakathon |
| DataBits | DAO Voting | https://github.com/Pfed-prog/Fuel_Voting | Beyond Monolithic Hakathon |
| FuelScape | FuelScape turns player items on RuneScape Classic server into NFTs on the Fuel VM | https://github.com/fuelscape/fuelscape | ETHSF |
| Sail | Sail is a central limit order book built on Fuel. It uses predicates to keep state bloat minimal. | https://ethglobal.com/showcase/sail-6httb | ETHSF |
| Fuel Names | Fuel Names is a decentralized naming registar built on Fuel. Fuel names allows users to mint a ".fuel" address, similar to how ENS functions on Ethereum. | https://github.com/ArshKochhar/FuelNames | ETHSF |
| Thunder | NFT Marketplace | https://thundernft.market/ | ETHBerlin |

## Project Ideas

| Name | Description | Difficulty |
|---|---|---|
|  Fuel Lotto | Create a simple counter that releases money to the user who increases the counter to a pre-defined number. Follow the [Developer Quickstart](https://fuellabs.github.io/fuel-docs/master/developer-quickstart.html) to get the counter functionality set up. | Easy |
|  Community run Twitter | Users can propose tweets, token holders vote on the proposed tweet. If the tweet gets x amount of votes or more, post the tweet automatically via the twitter API. | Intermediate |
|  DAO on Fuel | A smart contract for a DAO. | Intermediate |
|  Flash Loans | A lower-level detail that could enable flash-loans. Any contract could mint n tokens for the caller, as long as they’re returned to the contract at the end of the call (and maybe burned as well).| Advanced |