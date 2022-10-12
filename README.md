# Description
This is the frontend/ UI files for the Lottery dApp showcasing randomness with chainlink VRF 


## Quickstart

```
git clone https://github.com/obah/lottery-dapp-backend.git
cd lottery-dapp-backend
yarn
yarn dev
```

# Supported Chains

Goerli testnet
Ethereum mainnet
Polygon mainnet

# Usage

1. Run your local blockchain with the lottery dapp backend code (https://github.com/obah/lottery-dapp-backend.git)

> In a different terminal / command line

```
git clone https://github.com/obah/lottery-dapp-backend.git
cd lottery-dapp-backend
yarn 
yarn hardhat node
```

2. Add hardhat network to your metamask/wallet

- Get the RPC_URL of your hh node (usually `http://127.0.0.1:8545/`)
- Go to your wallet and add a new network. [See instructions here.](https://metamask.zendesk.com/hc/en-us/articles/360043227612-How-to-add-a-custom-network-RPC)
  - Network Name: Hardhat-Localhost
  - New RPC URL: http://127.0.0.1:8545/
  - Chain ID: 31337
  - Currency Symbol: ETH (or GO)
  - Block Explorer URL: None

Then [import one of the accounts](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account) from hardhat to your wallet/metamask. 

3. Run this code

Back in a different terminal with the code from this repo, run:

```
yarn dev
```

4. Go to UI and use the dApp!

Head over to your [localhost](http://localhost:3000) and play the lottery!