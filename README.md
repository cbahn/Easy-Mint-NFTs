# Overview
To create an NFT, you first need to choose a **blockchain** and a compatible **Wallet** and **dapp**.

The Blockchain stores the transactions and data that prove who owns the NFT. Ethereum is the first and most popular blockchain that supports NFTS, but it can be slow and expensive. For this guide we will be using Tezos, which is cheap, fast, and designed well for NFT use. Other options could include Solana, Polygon, or Cardano.

Our Wallet stores your account information so that you can store and use your NFT. There are various wallets avialable; some run on your computer, some are for a phone, and some run in a web browser. For the sake of this guide, we're going to be using a web based Wallet called [Kukai](https://wallet.kukai.app). 

The dapp, meaning **d**istributed **app**, is the code that runs on the blockchain. Dapps include an enormous range of applications that do all sorts of things, but for now all you need to know is that they can handle the minting and transferring of our NFT. For this guide we will be using Hic et Nunc which has a nifty web interface for minting NFTs.

# Minting an NFT

## Step 1 - Your Wallet

### Creating a new Wallet
We will be using a web based wallet called Kukai to store our Tezos account info. Visit [https://kukai.app](https://kukai.app) on a phone or computer and select **Create New Wallet** in the upper right. **Reveal your seed and write the whole thing down**. I reccomend writing it on paper. Then hit Next and **verify your seed**. If you ever forget your password, your seed is the only way to recover your account so make sure to keep it somewhere safe. Finally, **set a password**, **download your keystore file** and **Open Wallet**.

Now you'll be albe to see how much tez, the currency of Tezos, you have. This is often written as ꜩ. Because the account in brand new, you likely have 0 ꜩ. Once we get some NFTs then we can view and transfer them from the NFT tab.

### Accessing your Wallet
If you log out, or close your browser, you'll need to load your account again.

To access your Kukai account, visit [Kukai](https://wallet.kukai.app) and select **Import Wallet** in the upper right. **Upload your keystore file** and **enter your password** to load your account. If you send your keystore file to a different phone or computer then you'll be able to access your account there too.

## Step 2 - Getting tez

You'll need at least a little bit of tez to mint an NFT. 50¢ worth should be enough. You'll either need to buy the tez on a crypto exchange or, if you're my friend, I can give you some:
- In the upper right, click the icon to **Copy Address**. This is the address of your account.
- **Send me a discord message with this address** and I'll send you some tez.

## Step 3 - Minting an NFT

### Connecting to HeN
Log into your Kukai wallet then visit https://hicetnunc.art. Theres a bunch of neat stuff here; I reccomend hitting random and checking out some of the cool art.

We'll need to connect your wallet to Hic et Nunc so that they can communicate. Hit **sync** in the upper right then select **Kukai Wallet**. Go back to your Kukai Wallet and you should see a Permission Request. Hit **approve**.

Now go back to Hic et Nunc, open the menu in the upper right, then selet **OBJKT (mint)**. Now's the chance to customize your NFT:

- **Title**: The name of the NFT
- **Description**: Your description of the NFT
- **Tags**: words that people can search to find your NFT on Hic et Nunc
- **Editions**: how many copies of the same NFT are in existance. I usually just do 1.
- **Royalties**: Percent of marketplace sales go to you. I usualy set to 10%. Don't worry to much about this.
- **Upload OBJKT**: Upload your gif, jpeg, png, svg, mp4, webm, glb, mp3, wav, flac, pdf, html, or md file you want to display.

Hit **Preview**, the select **mint OBJKT**. Open your Kukai wallet and you'll be prompted for a confirmation. Because this costs tez, you'll need to **put in your password then hit Confirm**. It will take around 1 to 5 minutes for the minting to complete and appear on the blockchain. Be patient and keep an eye on your NFT tab in Kukai. Your newly minted NFT should appear there shortly.

You can also view your NFT on Hic et Nunc. Open your NFT in Kukai and tap More Info. You'll see the contract and the ID. For example, if it shows 
`KT1RJ6PbjHpwc3M5rw5s2Nbmefwbuwbdxton (623841)`
then your NFT's OBJKT ID on Hic et Nunc is 623841. You can view it by visiting https://hicetnunc.art/objkt/623841 *<-- enter your own OBJCT ID here*.

# Transferring an NFT
If you want to send your NFT to a friend, you can do that from the Kukai Wallet.

Open your Kukai Wallet > NFT tab > tap on your NFT > Hit **Send**. Enter Quantity as 1 then input your friends address. It's important that you double-check that the address is correct because the transfer cannot be undone! Hit preview the confirm the transfer.

If you'd like to 
