# Description
This is the frontend/ UI files of the Lottery dApp showcasing randomness with chainlink VRF 

# How it works
After deploying the lottery smart contract and starting the frontend server, 

User will be promted to connect wallet

Then choose amount to stake and play game.

More details can be found in the backend's [readme](https://github.com/obah/lottery-dapp-backend)

## Requirements

- Git
- Node
- Yarn
- Nextjs

## Quickstart

1. Start the frontend server
```
git clone https://github.com/obah/lottery-dapp-frontend.git
cd lottery-dapp-frontend
yarn
yarn dev
```

2. Run your local blockchain with the lottery dapp backend code (https://github.com/obah/lottery-dapp-backend.git)

> In a different terminal

```
git clone https://github.com/obah/lottery-dapp-backend.git
cd lottery-dapp-backend
yarn 
yarn hardhat node
```

3. Add hardhat network to your metamask/wallet

- Get the RPC_URL of your hh node (usually `http://127.0.0.1:8545/`)
- Go to your wallet and add a new network. [See instructions here.](https://metamask.zendesk.com/hc/en-us/articles/360043227612-How-to-add-a-custom-network-RPC)
  - Network Name: Hardhat-Localhost
  - New RPC URL: http://127.0.0.1:8545/
  - Chain ID: 31337
  - Currency Symbol: ETH (or GO)
  - Block Explorer URL: None

Then [import one of the accounts](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account) from hardhat to your wallet/metamask. 

4. Run the code

Back in a different terminal with the code from this repo, run:

```
yarn dev
```

5. Go to UI and use the lottery dApp!

Head over to your [localhost](http://localhost:3000) and play the lottery!

# Supported Chains

- Goerli testnet
- Ethereum mainnet
- Polygon mainnet

# Tools used

- Javascript
- NodeJs
- ReactJs
- NextJs
- Ethers.js
