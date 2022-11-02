A resource for developers preparing to build on Fuel.

## Developer Resources

[Developer Quickstart Guide](https://fuellabs.github.io/fuel-docs/master/developer-quickstart.html)
- Defining an ABI
- Smart Contract
- Testing with the Rust SDK
- Deploy to Testnet
- Write a frontend using the TS SDK

[Sway Docs](https://fuellabs.github.io/sway/latest/)
- All things Sway, our Rust-based programming language.

[TS SDK Docs](https://fuellabs.github.io/fuels-ts/)
- Deploying and calling contracts
- Generating contract types with TypeChain
- Building and sending transactions
- Encoding and decoding contract ABI

[Rust SDK Docs](https://fuellabs.github.io/fuels-rs/latest/)
- Compiling, deploying, and testing Sway contracts
- Use the Testnet or run a local Fuel node
- Crafting and signing transactions with hand-crafted scripts or contract calls
- Generating type-safe Rust bindings of contract ABI methods
- And more. fuels-rs is still in active development

[Awesome Fuel](https://github.com/FuelLabs/awesome-fuel)
- A maintained resource of all podcasts, articles, presentations, etc. related to Fuel.

## Inspiration - Existing Projects

| Name | Description | Link | Presented At |
|---|---|---|---|
|  Authsome | Authsome implements a multi-signature wallet using the predicate system of the Fuel VM and Sway programming language. This multi-signature wallet is then used as the basis for an pluggable auth infrastructure, similar to Web3Auth. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9tv1epm14319401w1mf7ltuhm/idea | ETH Lisbon 2022 |
|  Fuel Price Oracle | Token price (ETH, DAI) oracle for Fuel blockchain. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9upb5rc53868701tpdvj6n05d/idea | ETH Lisbon 2022 |
|  Capitalist Pigs | Gamify staking for fees in a DeFi project using a set of NFTs. | https://taikai.network/ethlisbon/hackathons/ethlisbon-2022/projects/cl9uljahi38530301ttxkbkask0/idea | ETH Lisbon 2022 |
|  Web3RSVP | An event creation and management platform where users can create new events and rsvp to existing events. | https://github.com/camiinthisthang/learnsway-web3rsvp | Workshop |

## Project Ideas

| Name | Description | Difficulty |
|---|---|---|
|  Fuel Lotto | Create a simple counter that releases money to the user who increases the counter to a pre-defined number. Follow the [Developer Quickstart](https://fuellabs.github.io/fuel-docs/master/developer-quickstart.html) to get the counter functionality set up. | Easy |
|  Community run Twitter | Users can propose tweets, token holders vote on the proposed tweet. If the tweet gets x amount of votes or more, post the tweet automatically via the twitter API. | Intermediate |
|  DAO on Fuel | A smart contract for a DAO. | Intermediate |
|  Flash Loans | A lower-level detail that could enable flash-loans. Any contract could mint n tokens for the caller, as long as they’re returned to the contract at the end of the call (and maybe burned as well).| Advanced |
