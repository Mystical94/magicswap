# MagicSwap
## Decentralized Exchange(DEX) on Polygon(Matic) Blockchain

If you wanna try some magic head over to:
http://magicswap-6aly9g.spheron.app/


## MagicSwap core contracts
MagicSwap core contracts are the fork of [Uniswap V2](https://github.com/Uniswap/uniswap-v2-core)

MagicSwap/Uniswap-V2 contracts are non-upgradeable and hence immutable in nature

In-depth documentation on Uniswap V2 is available at [uniswap.org](https://uniswap.org/docs).

The built contract artifacts can be browsed via [unpkg.com](https://unpkg.com/browse/@uniswap/v2-core@latest/).

## Addresses:

Mumbai Testnet
- MagicSwapFactory: https://mumbai.polygonscan.com/address/0x4cab5791640c439d7aece517d70bfefca4b0fb6b
- MagicSwapRouter: https://mumbai.polygonscan.com/address/0x90d4e9eb792602aa7a7506b477b878307c35e24a

## Local Development

The following assumes the use of `node@>=10`.

## Install Dependencies

`yarn`

## Compile Contracts

`yarn compile`

## Run Tests

`yarn test`

## Changes from Uniswap V2

Not even a single line of code has been changed in the core contracts when compared with Uniswap V2. Hence no changelog.

## MagicSwap periphery contracts

This repository has been forked from [UniswapV2](https://github.com/Uniswap/uniswap-v2-periphery)


## MagicSwap Interface

An open source interface for MagicSwap -- a protocol for decentralized exchange on Polygon.

Enabling users to:

- Add and remove their liquidity positions on MagicSwap protocol
- Swap tokens on MagicSwap protocol

## Future Plans:

- Add a NFT airdrop for early adopters to give access to additional products to them
- Add a game section in the dapp for new magicians so that they become an expert
- Make it live on Polygon Mainnet

## Deploying the MagicSwap on local machine

Clone the repository

Move into the UserInterface Directory

```sh
cd UserInterface
```

install dependencies using **yarn** or **npm**

```sh
yarn

or

npm install
```

start the development server
```sh
yarn dev

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```

## MagicSwap is deployed on Spheron
