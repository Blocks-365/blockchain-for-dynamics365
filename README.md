# Blockchain for Dynamics 365

With Blockchain for Dynamics 365 you can easily create [ERC1155](https://eips.ethereum.org/EIPS/eip-1155) non-fungubale tokens (NFT's) on Ethereum Blockchain directly from your CDS or Dynamics 365 environment and start trading them.

NFT's are tokenized versions of real-world assets. They are similar to stablecoins but are used to represent non-fungible assets like customer assets, shipments, artworks, real estate or collectibles. Blockchain for Dynamics 365 allows you to easily convert a CDS or Dynamics 365 record into a digital asset on the Blockchain which you can hold in your Ethereum wallet, transfer to others or trade on a Marketplace like [OpenSea](https://www.poensea.io).

### PART I: Installation

**Step 1:** Before you start installing the solution [request an API Key](https://www.blocks365.com/blockchain-for-dynamics365)

**Step 2:** Download the latest version of the Blockchain for Dynamics 365 solution:
- [Blockchain for Dynamics 365 v1.0.0.0](https://github.com/Blocks-365/blockchain-for-dynamics365/raw/master/solution/Blockchain_for_Dynamics365_1_0_0_0.zip)

**Step 3:** From within Dynamics 365, navigate to Settings → Solutions → Import and select he downloaded solution file. Follow the instruction.

<kbd>![](/images/import-crm-solution.png)</kbd>

### PART II: Setting up your Wallet in Dynamics 365

In step 1 you should have received a API Key. With this key you can now configure your environment and start minting those tokens!

First navigate to Advanced Find. Look for 'Blocks365 Wallet' en click on Execute.

<kbd>![select-blocks365-wallet](https://github.com/Blocks-365/blockchain-for-dynamics365/blob/master/images/select-blocks365-wallet.png)</kbd>

Now click on 'New Blocks365 Wallet'

<kbd>![new-blocks365-wallet](https://github.com/Blocks-365/blockchain-for-dynamics365/blob/master/images/new-blocks365-wallet.png)</kbd>

Fill in the following information and Save the record:
- Name of your Wallet
- The Wallet Key  which you received by Email in step 1
- The name, description and image of your NFT token collection. The token collection image has a default image value which you can override.

<kbd>![new-wallet](https://github.com/Blocks-365/blockchain-for-dynamics365/blob/master/images/new-wallet.png)</kbd>

When you click on Save your Wallet Key is validated. In case of successful validation your Ethereum Account Address and (smart)contract Address will appear.

You are now ready to mint the tokens! 

[For instructions on how to mint the NFT tokens go click here](https://www.blocks365.com/blockchain-for-dynamics365).



