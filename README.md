# C_Block
Smart contract to push NFT based on carbon-capture assets on-chain

This code is based on Patrick Collins' code (https://github.com/PatrickAlphaC/nft-mix). You'll need testnet Rinkeby and testnet LINK in the wallet associated with your private key. You will need to run the following commands: 

- brownie run scripts/advanced_collectible/deploy_advanced.py --network rinkeby
- brownie run scripts/advanced_collectible/create_collectible.py --network rinkeby
- brownie run scripts/advanced_collectible/create_metadata.py --network rinkeby
- brownie run scripts/advanced_collectible/set_tokenuri.py --network rinkeby

