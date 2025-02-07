
**Cryptopia** is an all-in-one consumer wallet AI agent designed to revolutionize your digital asset experience. By integrating advanced blockchain analytics, real-time market data, and smart contract functionalities, Cryptopia serves as your comprehensive command center for managing, analyzing, and growing your crypto portfolio.

---

## Overview

Cryptopia empowers both casual enthusiasts and seasoned crypto users with the tools needed to navigate the decentralized world. It seamlessly blends multiple integrations and modular components to deliver a dynamic, secure, and user-friendly platform for managing digital assets.

---

## Key Features

### Real-Time On-Chain Insights & Market Alerts
- **The Graph Integration:**  
  - **How It Works:** Continuously monitors Uniswap V3 activity to detect large swaps, emerging liquidity pools, whale accumulations, and arbitrage opportunities.  
  - **Creative Implementation:** Set custom alerts that trigger automated trading strategies when significant market moves occur, ensuring you capitalize on real-time opportunities.

- **Crypto Compare API Integration:**  
  - **How It Works:** Fetches real-time price data, historical trends, and the latest crypto news, delivering a comprehensive market overview.  
  - **Creative Implementation:** Dynamically rebalance your portfolio by leveraging real-time news and price fluctuations, with automated trade suggestions based on market developments.

---

### Comprehensive Wallet & Asset Management
- **Moralis API Integration:**  
  - **How It Works:** Provides a holistic view of your digital assets across multiple blockchains. It retrieves detailed wallet history, token balances, NFT collections, and transaction records, enabling in-depth analysis of your crypto journey.  
  - **Creative Implementation:** Generate comprehensive portfolio reports and interactive dashboards that break down your token portfolio, historical performance, and overall net worth. These insights empower you to make informed decisions and refine your strategies.

---

### Smart Contract, NFT, and Token Operations
- **cdp_agentkit_core.actions Modules:**  
  - **Deploy & Manage:**  
    - **Deploy Contracts & Tokens:** Easily launch smart contracts, mint NFTs, or deploy ERC20 tokens with intuitive tools.  
    - **Asset Movements:** Seamlessly wrap/unwrap ETH for DeFi interactions and execute token swaps on Uniswap V3.
    - **Risk Management:** Assess address reputations and manage collateralized debt positions (CDPs) to enhance asset security.  
  - **Creative Implementation:** Instantly deploy a custom NFT collection to celebrate milestones or automate ETH wrapping during market dips, enabling participation in high-yield liquidity pools effortlessly.

---

### Developer & Experimentation Tools
- **Sandbox & Utility Functions:**  
  - **How It Works:** Access faucet funds for test networks and leverage robust utility functions to experiment with advanced DeFi strategies risk-free.  
  - **Creative Implementation:** Launch a sandbox mode to simulate trades, contract deployments, and liquidity strategies before committing real funds—perfect for refining your approach.

- **Browser Search Functionality:**  
  - **How It Works:** Integrates a browser-based search tool to fetch curated guides, tutorials, and educational content.  
  - **Creative Implementation:** New to crypto? Access step-by-step guides and comprehensive learning resources directly from Cryptopia. Whether you need market analysis tips or in-depth tutorials on wallet management and DeFi strategies, our built-in search tool brings the knowledge you need right to your fingertips.

---

## Why Cryptopia?

Cryptopia isn’t just another wallet—it's your digital asset command center. It empowers you to:

- **Stay Informed:** With real-time insights, alerts, and in-depth portfolio reports, never miss a market opportunity.
- **Control Your Assets:** Detailed analytics provide complete oversight of your digital portfolio, from transaction histories to token performance.
- **Educate & Innovate:** Access tailored guides and educational content to master crypto fundamentals, while experimenting with new DeFi strategies in a safe, sandboxed environment.

---


Step into **Cryptopia** and experience the future of crypto management—where every decision is informed, every asset is secure, and every opportunity is at your fingertips.



<br/><br/>


# Integrated Functionalities:


### 1. **The Graph Integration**
Utilizes two subgraphs on the Base network to query and analyze on-chain data. The integration supports several specialized queries:

      - Uniswap V3 Base Subgraph : https://gateway.thegraph.com/api/{api-key}/subgraphs/id/43Hwfi3dJSoGpyas9VwNoDAv55yjgGrPpNSmbQZArzMG
      - Bunni V2 Base Subgraph : https://gateway.thegraph.com/api/{api-key}/subgraphs/id/3oawHiCt7L9wJTEY9DynwAEmoThy8bvRhuMZdaaAooqW
 


- **Large Swap Detection:** Identifies whale exits by flagging transactions with sell volumes above a configurable threshold (e.g., $100,000+ USD).
- **Emerging Liquidity Pools:** Spots new pools with high Total Value Locked (TVL) that are experiencing rapid growth (e.g., TVL > $1,000,000 with 50%+ growth in 24 hours).
- **High Fee Pools:** Finds liquidity pools offering high fee returns (e.g., fee tiers above 5000, implying high APY).
- **Undervalued Tokens:** Searches for tokens that might be undervalued based on a low TVL-to-Market Cap ratio, provided they have significant liquidity.
- **Whale Accumulation:** Detects early whale activity by monitoring large buy transactions (e.g., >$250,000 within 24 hours).
- **Swap Trends Analysis:** Reviews historical swap data (over the last 7 days) to gauge market sentiment.
- **Gas Fee Insights:** Examines transactions with the highest gas usage in the past 24 hours to provide insight into network cost dynamics.
- **Arbitrage Opportunities:** Compares pool data and computed prices between different decentralized exchanges (DEXs) to highlight potential arbitrage margins.

---

### 2. **Browser Search Integration**
- **Dynamic Internet Search:** If deeper context or real-time information is needed, the agent can trigger a browser-based search. It asks for user consent before proceeding and then uses a dedicated tool (named "when_no_api_search_like_human") to perform multi-step searches on the internet.

---

### 3. **Crypto Compare API Integration**
Offers real-time and historical market data along with crypto news:
- **News Fetching:** Retrieves the latest news articles about specific tokens, including titles, bodies, sources, and publish times.
- **Price Data:** Provides current cryptocurrency prices with support for multiple currencies.
- **Trading Signals:** Fetches advanced trading signals and market indicators (such as network activity, large transaction patterns, and holder behavior) from analytics providers like IntoTheBlock.
- **Market Cap Rankings:** Lists top cryptocurrencies by market capitalization along with key metrics like price, volume, and circulating supply.
- **Exchange Rankings:** Identifies the top exchanges for specific trading pairs based on volume, market share, and price variations.
- **Volume Leaders:** Retrieves rankings of cryptocurrencies based on their total trading volume.

---

### 4. **Moralis API Integration**
Enables deep wallet and blockchain data retrieval:
- **Wallet History & Balance:** Fetches transaction histories and current balances for any given wallet on various blockchains.
- **NFT and Token Transfers:** Provides details on NFT transfers, ERC20 token transfers, and overall NFT trading activities.
- **Token Holdings & DeFi Positions:** Lists all tokens held by a wallet and shows current DeFi positions.
- **Price Retrieval:** Supports fetching current prices for single tokens or in batch, including options for percent-change data.
- **OHLCV Data:** Retrieves historical Open-High-Low-Close-Volume data for trading pairs to assist with technical analysis.
- **Wallet Net Worth & Stats:** Calculates the overall net worth of a wallet (filtering out spam or unverified tokens) and provides statistical insights into wallet activity.

---

### 5. **Wow Launch Pad Integration**
- **Multi-Token Contract Deployment:** Offers the ability to deploy new multi-token contracts with a customizable base URI for token metadata. This is useful for launching collections or projects with multiple tokens.

---

### 6. **ERC-20 Token Swapping on Uniswap V3 Base**
- **Swapping Functionality:** Facilitates the swapping of ERC-20 tokens on the Uniswap V3 platform operating on the Base network, allowing for on-chain token exchanges directly through the agent.

---

### 7. CDP Agent Kit Prepacked functionality

cdp_agentkit_core.actions – Subpackages & Submodules
This suite forms the backbone for blockchain interactions, each module handling a specific task:

- address_reputation: Assess the trustworthiness and risk profile of blockchain addresses.
- cdp_action: Manage and interact with collateralized debt positions (CDPs) or similar DeFi instruments.
- constants: Maintain global constants and configurations across the agent.
- deploy_contract: Deploy generic smart contracts onto blockchain networks.
-deploy_nft: Launch NFT contracts to create and deploy NFT collections.
- deploy_token: Deploy token contracts (e.g., ERC20), enabling new token issuance.
- get_balance: Retrieve wallet balances for various tokens across chains.
- get_balance_nft: Fetch NFT balance information for a wallet.
- get_wallet_details: Extract detailed wallet information, including transaction histories and holdings.
- mint_nft: Mint new NFTs on deployed NFT contracts.
- register_basename: Handle base name registration for token naming, domains, or identification.
- request_faucet_funds: Allow users to request testnet tokens for development.
- trade: Facilitate token trading, including order placement and execution on DEXs.
- transfer: Manage token transfers between wallet addresses.
- transfer_nft: Handle NFT transfers for smooth digital asset movement.
- utils: Provide utility functions and helpers for other modules.
- wrap_eth: Enable wrapping/unwrapping of ETH to WETH for DeFi protocol interactions.
