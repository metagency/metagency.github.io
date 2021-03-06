# Overview:

`Deploy Metagency Contract` has to be deployed ONLY ONCE in the beginning. After it is deployed we need to store the address of the Metagency Contract. VERY IMPORTANT: Only AFTER the 
address is added to the config `Create Artist Collection` and `Add Artwork to collection` can be done. During those steps take extreme caution as once contracts are deployed they can not be changed afterwards.

# 1. Deploy Metagency Contract

  1. Go to https://metagency.github.io/deploy_metagency.html
  2. Set chain to Mainnet.
  3. Connect through MetaMask.
  4. Make sure you use right Metagency Wallet.
  6. Click Deploy
  7. Wait until you see `Metagency deployed`. 
  8. Copy Address of the new contract.

# 2. Create Artist Collection

  1. Go to https://metagency.github.io/create_collection.html
  2. Set chain to Mainnet.
  3. Connect through MetaMask.
  4. Make sure you use right Metagency Wallet.
  5. Input data: Note: `Make sure everything is correct. This CAN NOT be changed afterwards.`
      - Add creator Address.
      - Add Artist name. Note: `No special characters or whitespaces allowed. E.g. Hervé Di Rosa -> HerveDiRosa`. This will be the Name of the Collection. The collection Name can be updated on OpenSea and Rarible.
      - Add First Sale Artist Percentage. Note: `90% of the first sale goes to the artist -> 9000, 75% -> 7500`
      - Add Artist Percentage. This is the secondary sales fee that goes to the artist. `5% of the secondary sale goes to the artist -> 0050`
      - Add Agency Percentage. This is the secondary sales fee that goes to the agency. `2.5% of the secondary sale goes to the agency -> 0025`
   6. Click create Collection. The new Contract for the collection is now Deployed. 
   7. MetaMask will ask you to confirm another transaction which adds the collection to the Metagency.
   8. Confirm this transaction and check in MetaMask if transaction succeeded. 

# 3. Add Artwork to collection

  1. Go to https://metagency.github.io/add_artwork.html
  2. Set chain to Mainnet.
  3. Connect through MetaMask.
  4. Make sure you use right Metagency Wallet.
  5. Input data: Note: `Make sure everything is correct. This CAN NOT be changed afterwards.`
      - Chosse collection you want to add the artwork to.
      - Add token URI to a ipfs stored JSON.
      - Add price. Note: `The price is set in ETH. 0.5 ETH -> 0.5`
      - Add Number of copies: Note: `50 Copies -> 50`
  6. Click add Artwork and check in MetaMask if transaction succeeded. 


# 4. Add Roalties and customize page 
  1. You have to set the royalties on open-sea and rarible manually.
