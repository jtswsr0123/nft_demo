example showing a simple version of nft (using ipfs/pinata for image storage)

1. we didn't upload an image to IPFS ourselves
2. IPFS decentralized
3. anyone can mint an NFT here

how to run:
1. brownie run .\scripts\advanced_collectible\deploy_and_create.py --network rinkeby
2. brownie run .\scripts\advanced_collectible\create_metadata.py --network rinkeby
3. a few times: brownie run .\scripts\advanced_collectible\create_collectible.py --network rinkeby
4. brownie run .\scripts\advanced_collectible\set_tokenuri.py --network rinkeby
5. open web browser: https://testnets.opensea.io/assets/****