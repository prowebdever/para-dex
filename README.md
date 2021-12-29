# Para Dex

> React components and hooks for fast building dApps without running own backend

GitHub: https://github.com/phantom20320/para-dex

This dApp is built on [react-moralis](https://github.com/MoralisWeb3/react-moralis). Also has its own context provider for quick access to `chainId` or `ethAddress`

There are many components in this project that do not require an active web3 provider, they use Moralis Web3 API. Moralis supports the most popular blockchains and their test networks. You can find a list of all available networks in [Moralis Supported Chains](https://docs.moralis.io/moralis-server/web3-sdk/intro#supported-chains)

Please check the [official documentation of Moralis](https://docs.moralis.io/#user) for all the functionalities of Moralis.


# Quick Start

Clone or fork `Para DeX`:
```sh
git clone https://github.com/para-dex/para-dex.git
```
Install all dependencies:
```sh

yarn install 
```
✏ Rename `.env.example` to `.env` in the main folder and provide your `appId` and `serverUrl` from Moralis ([How to start Moralis Server](https://docs.moralis.io/moralis-server/getting-started/create-a-moralis-server)) 
Example:
```jsx
REACT_APP_MORALIS_APPLICATION_ID = xxxxxxxxxxxx
REACT_APP_MORALIS_SERVER_URL = https://xxxxxx.grandmoralis.com:2053/server
```
Run your App:
```sh
yarn start
```
