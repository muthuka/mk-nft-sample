# NFT Sample

This project demonstrates a basic NFT contract and minting process. It involves a simple contract implemented using Open Zeppelin and also minting it from a Ropsten network. I used the tutorials to create this and also hardhat for development.

## Setup

You need to create a .env file with the following setup.

```text
API_URL="https://eth-ropsten.alchemyapi.io/v2/REPLACE-API-KEY"
PRIVATE_KEY="REPLACE-PRIVATE-KEY"
PUBLIC_KEY="REPLACE-PUBLIC-KEY"
```

Once done, the following commands will help you run

```bash
npm install
npx hardhat compile
npx hardhat --network ropsten run scripts/deploy.js
```

## Tutorials used

* <https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/>
* <https://ethereum.org/en/developers/tutorials/how-to-mint-an-nft/>
* <https://ethereum.org/en/developers/tutorials/how-to-view-nft-in-metamask/>
