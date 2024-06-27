

<h1 align="center">
  <br>
  <a href="#"><img src="https://assets.shano-web.com/shano-modified.png" alt="IvanShano" width="200"></a>
  <br>
  Automated DEX Market Maker (Uniswap)
  <br>
</h1>
<p align="center" width="100%">
<img src="https://skillicons.dev/icons?i=nodejs,nextjs,supabase,tailwind,ts&theme=light">
</p>
<h4 align="center">Automated DEX Market Maker. Currently supported Uniswap(Mainnet, Base), Raydium (Solana). Generate wallets and market make tokens.</h4>

![screenshot](https://github.com/shnmrc/dexmarketmaker/blob/c12323382cc5f90f247e3d4f88fc7af8fcec2868/assets/generateflows.gif)

## Key Features

* Search Tokens - Search using DEXScreener API, fetching pairdata.
  - Watch chart and build trade flows.
  ![SearchTokens](https://github.com/shnmrc/dexmarketmaker/blob/c12323382cc5f90f247e3d4f88fc7af8fcec2868/assets/searchtokens.gif)
* Generate unlimited wallets
  - Generate wallets, set labels and use groups.
  ![GenerateWallets](https://github.com/shnmrc/dexmarketmaker/blob/c12323382cc5f90f247e3d4f88fc7af8fcec2868/assets/generatewallets.gif)
  ![DoLabels](https://github.com/shnmrc/dexmarketmaker/blob/c12323382cc5f90f247e3d4f88fc7af8fcec2868/assets/dolabels.gif)
* Airdrop ETH or Tokens between generated wallets. 
    - Airdrop contract audited and secured by [thirdweb](https://thirdweb.com/) lab.
      ![Airdrop](https://github.com/shnmrc/dexmarketmaker/blob/c12323382cc5f90f247e3d4f88fc7af8fcec2868/assets/airdrop.gif)
* Single buys/sells and flows.
    - Ability to do mass buys/sells with the same value settings and custom delays between buys.
    - Full position orders.
    - Ability to generate Automated Flows. All that you need to do is fill required inputs and generate. Each transaction cost is: value - gascost = estimated receive value.
    - All transactions have ETA gas settings if the gas limit can't be estimated using the standard 500.000 gas limit.
    - As router on the backend using AlptaRouter/UniswapV3Router/Smart-order-router.
    - RPC can be customized via the backend. By default using Infura.
    - Buy and sell orders can work as async and sync jobs.  
* Sweep balances to the connected wallet.
	- Ability to sweep ETH or Token balance of all selected wallets to the connected wallet.
* Orders and transactions management.
* Favorite tokens.
	- Search and save tokens as favourites.

## How To Use

For the public currently not available, only by private request. Reach me via contact details for more info.

## Credits

This software uses the following open-source packages:

- [Supabase](https://supabase.com/)
- [NextJS13](https://nextjs.org/)
- [Node.js](https://nodejs.org/en)
- [Ethers.js](https://docs.ethers.org/v6/)
- [React-flow](https://reactflow.dev/)
- [BullMQ](https://docs.bullmq.io/)
- [RainbowKit](https://www.rainbowkit.com/)
## Contacts

My telegram [@shanowebcn](https://t.me/shanowebcn) ![Telegram](https://avatars.githubusercontent.com/u/6113871?s=24&v=4)

## License

MIT

