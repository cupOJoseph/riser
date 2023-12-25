# riser
Library of helpful scripts for Forge Scripts. Built with Foundry and no other dependencies.

A riser is a reservoir built into a metal casting mold to prevent cavities due to shrinkage. Most metals are less dense as a liquid than as a solid so castings shrink upon cooling, which can leave a void at the last point to solidify.

![image](https://github.com/cupOJoseph/riser/assets/9449596/801cc241-b9c1-4512-986b-b14a9664dac5)

## Motivation
We love scripting with forge and writting scripts in solidity that run smart contracts with transactions that can be sent on chain. But I re-use a lot of code when writing scripts that are meant to interact with things onchain. Riser provides a couple helpful templates of common patterns for forge scripts.

## Installation

1. Get foundryup
```bash
curl -L https://foundry.paradigm.xyz | bash
```
2. Follow terminal instructions to install foundry
3. clone this repo (I'll do package management later)


## Features

- [ ] loading a contract
- [ ] creating X number of accounts from a private key, and then exporting them as a csv
- [ ] seeding a list of accounts with gas from a paymaster
- [ ] send build transactions onchain via a default RPC

