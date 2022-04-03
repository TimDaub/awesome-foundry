# Awesome Foundry

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Telegram Chat](https://img.shields.io/endpoint?color=neon&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Ffoundry_rs)](https://t.me/foundry_rs) [![Telegram Chat](https://img.shields.io/endpoint?color=neon&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2Ffoundry_support)](https://t.me/foundry_support)

[//]: # ([![Track Awesome List]&#40;https://www.trackawesomelist.com/badge.svg&#41;]&#40;https://www.trackawesomelist.com/avelino/awesome-go/&#41;)

Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust. [Install Foundry here](https://github.com/gakonst/foundry).

<img align="center" src="https://mirror.xyz/_next/image?url=https%3A%2F%2Fimages.mirror-media.xyz%2Fpublication-images%2Fkt99mFtZZ1Gl2ZbWGNI3J.png&w=3840&q=90" alt="awesome-foundry" title="awesome-foundry" />


> A curated list of awesome Foundry resources, tutorials, tools and libraries. Inspired by [awesome-go](https://github.com/avelino/awesome-go).


### Contributing 

Please take a quick gander at the [contribution guidelines](https://github.com/crisgarner/awesome-foundry/blob/main/CONTRIBUTING.md) first. 

[//]: # (Thanks to all [contributors]&#40;https://github.com/crisgarner/awesome-foundry/graphs/contributors&#41;; you rock!)

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Content

- [Awesome Foundry](#awesome-foundry)
- [Tools](#tools)
- [Libraries](#libraries)
- [Tutorials](#tutorials)
- [Projects Using Foundry](#projects-using-foundry)

**[⬆ back to top](#awesome-foundry)**

## Tools
Frameworks, plugins and utilities for Foundry.
- [Foundryup](https://github.com/gakonst/foundry/tree/master/foundryup) - Update or revert to a specific Foundry branch with ease.
- [Foundry Template](https://github.com/ZeframLou/foundry-template) - A template for a Foundry project.
- [Forge Template](https://github.com/FrankieIsLost/forge-template) - A template for quickly getting started with forge.
- [Forge Standard Library](https://github.com/brockelmore/forge-std/) - Collection of helpful contracts for use with forge and foundry.
- [Forge CI](https://gist.github.com/clifton/b5ee5286bb229281fb31d7c4b15e6f31) - Simple Github Actions workflow to run forge test.
- [Forge Replit](https://replit.com/@wilsonc/VanillaForge) - Run Forge in the browser, vanilla setup.
- [Gitpod Template](https://github.com/gakonst/forge-template/blob/master/.gitpod.yml) - Gitpod configuration file.
- [Foundrydeploy](https://github.com/joshieDo/foundrydeploy) - Limited scripting (declarative?) language to implement a basic deployment pipeline using foundry. 

## Libraries
Solidity libraries or utilities that use Foundry.
- [Solmate](https://github.com/Rari-Capital/solmate) - Modern, opinionated, and gas optimized building blocks for smart contract development.
- [Chain Claim](https://github.com/botdad/chain-claim) - Solidity lib and helper scripts for providing claim code generation and on chain verification of a claim.
- [Playpen](https://github.com/ZeframLou/playpen) - Set of modern, gas optimized staking pool contracts.
- [TokenMigrator](https://github.com/ZeframLou/token-migrator) - A simple contract for migrating from an old ERC20 token to a new ERC20 token.
- [VestedERC20](https://github.com/ZeframLou/vested-erc20) - A wrapper ERC20 token that linearly vests an underlying ERC20 token to its holders.
- [lil web3](https://github.com/m1guelpf/lil-web3/) - Small, focused, utility-based smart contracts.
- [RollCall](https://github.com/withtally/rollcall) - Rollup Governance Libraries.
- [Forge Optimism](https://github.com/tarrencev/forge-optimism) - Forge Optimism is a collection of helpful contracts for use with forge and foundry on Optimism.
- [Yearn Strategy Foundry Mix](https://github.com/storming0x/foundry_strategy_mix) - Basic Solidity Smart Contract for creating your own Yearn Strategy.
- [indexed-sparse-merkle-tree](https://github.com/rugpullindex/indexed-sparse-merkle-tree) - A gas-optimized implementation of a sparse merkle tree in Solidity. 
- [libharberger](https://github.com/rugpullindex/libharberger) - A library for charging Harberger taxes on partial common non-fungible property. 

## Tutorials
- [Getting Started by Crisgarner](https://mirror.xyz/crisgarner.eth/BhQzl33tthkJJ3Oh2ehAD_2FXGGlMupKlrUUcDk0ALA) - Short intro tutorial for getting started. 
- [Getting Started by Wilson](https://w.mirror.xyz/mOUlpgkWA178HNUW7xR20TdbGRV6dMid7uChqxf9Z58) - Extended tutorial with information about testings and logging.
- [Getting Started by What The Func?](https://youtu.be/wqFnif_6Mbc) - Video tutorial.
- [How to Foundry with Brock Elmore](https://www.youtube.com/watch?v=Rp_V7bYiTCM) - YouTube live code tutorial on how to get started with Foundry.
- [Foundry Book](https://onbjerg.github.io/foundry-book/) - A book on all things Foundry.
- [Mainnet Forking](https://mirror.xyz/susheen.eth/bRCzT2QLdNINMVk8251udkfjHW_T9ascCQ1DV9hURz0) - This article teaches how to run a locally simulate a swap on Uniswap.
- [Ethernaut x Foundry](https://github.com/ciaranmcveigh5/ethernaut-x-foundry) - Ethernaut puzzles solved & tested with foundry.
- [Damn Vulnerable Defi - Foundry Version](https://github.com/nicolasgarcia214/damn-vulnerable-defi-foundry) - The Damn Vulnerable Defi CTF using Foundry.
- [Getting Started (Chinese)](https://learnblockchain.cn/article/3502) - Getting started tutorial on Chinese.

## Projects Using Foundry
- [MapleLoan](https://github.com/maple-labs/loan) - Set of contracts to facilitate on-chain Loans between Maple Finance Pools and institutional borrowers.
- [Cryptex Finance](https://github.com/cryptexfinance/contracts) - Index token that tracks the total cryptocurrency market capitalization. (Optimism version uses Foundry tests).
- [Gov of Venice](https://github.com/pentagonxyz/gov-of-venice) - Governance of Venice is a new paradigm in DAO governance, attempting to standardise the existence of functional groups within DAOs (Guilds) in terms of how they participate in the Governance process of different DAOs. 


**[⬆ back to top](#awesome-foundry)**
