# OnBridge NFT cross-chain Gateway

[![](https://img.shields.io/badge/site-onbridge.io-blue.svg?style=flat-square)](https://onbridge.io)
[![](https://img.shields.io/badge/demo-youtube-blue.svg?style=flat-square)](https://youtu.be/R3vM0xEpgGE)
[![](https://img.shields.io/badge/live-app.onbridge.io-blue.svg?style=flat-square)](https://app.onbridge.io)
[![](https://img.shields.io/badge/build%20with-openzeppelin-blue.svg?style=flat-square)](https://openzeppelin.com/)
![Solidity](https://img.shields.io/badge/solidity-v0.8.9-green)
[![Test](https://github.com/Onbridge-io/onbridge_contracts/actions/workflows/test.yml/badge.svg)](https://github.com/Onbridge-io/onbridge_contracts/actions/workflows/test.yml)

## Cross-chain ERC-721/1155 bridge for advanced GameFi mechanics

Status: Early prototype

Was initially bootstrapped diring the [BSC GameFi Hackathon](https://hackerlink.io/grant/REE/1). [Demo](https://youtu.be/R3vM0xEpgGE).

[![BSC GameFi Hackathon](bsc_hackathon.png)](https://hackerlink.io/grant/REE/1)

Support us [here](https://hackerlink.io/buidl/1606?roundProj=1184)

# Releases and Changelog

* `v0.1.0-pre-alpha-bsc` implement basic flow of one-way bridging from Ethereum mainnet (Rinkeby) to BSC (testnet) [Demo](https://youtu.be/pQbSB7JWahE)
* `v0.1.1-pre-alpha-bsc-battleverse` bidirectional bridging from Ethereum mainnet (Rinkeby) to BSC (testnet) and back. Cross-chain play-and-earn with Battleverse [Demo](https://youtu.be/R3vM0xEpgGE)

# Architecture

One day we'll restructure this into beautiful gitbook, but currently it's just a photo from the hackathon's whiteboard

![Diagram](architecture.jpg)

# Code repositories

* [Root repository](https://github.com/Onbridge-io/onbridge) - clone it recursively with submodules
* [Bridge DApp](https://github.com/Onbridge-io/onbridge_app) - ReactJS DApp of dual-network bridge
* [Indexing service and API endpoint](https://github.com/Onbridge-io/onbridge_api) - Pythonic WSGI/Django RESTful API WebApp and background workers
* [Contracts](https://github.com/Onbridge-io/onbridge_contracts) - Ethereum/EVM smart contracts for L1 and L2 networks (Bridges and ERC-721 tokens)
