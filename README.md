![image](https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/cryptopia-logo.png)

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


<!-- 1. The Graph Integration -->
<h3>1. <strong>The Graph Integration</strong></h3>
<div style="display: flex; align-items: center;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/thegraph.png" style="width: 50px; margin-right: 10px;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/uniswap.png" style="width: 50px; margin-right: 10px;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/base.png" style="width: 40px; margin-right: 10px;">
  <p>Utilizes two subgraphs on the Base network to query and analyze on-chain data. The integration supports several specialized queries:</p>
</div>
<ul>
  <li>Uniswap V3 Base Subgraph: <a href="https://gateway.thegraph.com/api/{api-key}/subgraphs/id/43Hwfi3dJSoGpyas9VwNoDAv55yjgGrPpNSmbQZArzMG">Link</a></li>
  <li>Bunni V2 Base Subgraph: <a href="https://gateway.thegraph.com/api/{api-key}/subgraphs/id/3oawHiCt7L9wJTEY9DynwAEmoThy8bvRhuMZdaaAooqW">Link</a></li>
</ul>
<p>Features include:</p>
<ul>
  <li>Large Swap Detection</li>
  <li>Emerging Liquidity Pools</li>
  <li>High Fee Pools</li>
  <li>Undervalued Tokens</li>
  <li>Whale Accumulation</li>
  <li>Swap Trends Analysis</li>
  <li>Gas Fee Insights</li>
  <li>Arbitrage Opportunities</li>
</ul>

<!-- 2. Browser Search Integration -->
<h3>2. <strong>Browser Search Integration</strong></h3>
<p>Dynamic Internet Search tool for real-time information with user consent.</p>

<!-- 3. Crypto Compare API Integration -->
<h3>3. <strong>Crypto Compare API Integration</strong></h3>
<div style="display: flex; align-items: center;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/cryptocompare.png" style="width: 50px; margin-right: 10px;">
  <p>Offers real-time and historical market data along with crypto news.</p>
</div>
<ul>
  <li>News Fetching</li>
  <li>Price Data</li>
  <li>Trading Signals</li>
  <li>Market Cap Rankings</li>
  <li>Exchange Rankings</li>
  <li>Volume Leaders</li>
</ul>

<!-- 4. Moralis API Integration -->
<h3>4. <strong>Moralis API Integration</strong></h3>
<div style="display: flex; align-items: center;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/moralis.png" style="width: 50px; margin-right: 10px;">
  <p>Enables deep wallet and blockchain data retrieval.</p>
</div>
<ul>
  <li>Wallet History & Balance</li>
  <li>NFT and Token Transfers</li>
  <li>Token Holdings & DeFi Positions</li>
  <li>Price Retrieval</li>
  <li>OHLCV Data</li>
  <li>Wallet Net Worth & Stats</li>
</ul>

<!-- 5. Wow Launch Pad Integration -->
<h3>5. <strong>Wow Launch Pad Integration</strong></h3>
<p>Offers the ability to deploy new multi-token contracts with a customizable base URI for token metadata.</p>

<!-- 6. ERC-20 Token Swapping on Uniswap V3 Base -->
<h3>6. <strong>ERC-20 Token Swapping on Uniswap V3 Base</strong></h3>
<div style="display: flex; align-items: center;">
  <img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/uniswap.png" style="width: 50px; margin-right: 10px;">
  <p>Facilitates the swapping of ERC-20 tokens on the Uniswap V3 platform operating on the Base network.</p>
</div>

<!-- 7. CDP Agent Kit Prepacked functionality -->
<h3>7. <strong>CDP Agent Kit Prepacked Functionality</strong></h3>
<img src="https://github.com/0xkieranwilliams/Cryptopia-Wallet/blob/main/assets/coinbase.png" alt="Uniswap" style="width: 50px; margin-right: 10px;">

<p>Forms the backbone for blockchain interactions, with modules handling tasks like:</p>
<ul>
  <li>Address Reputation</li>
  <li>CDP Management</li>
  <li>Smart Contract Deployment</li>
  <li>NFT Minting and Transfers</li>
  <li>Token Issuance and Trading</li>
  <li>Utility Functions for Blockchain Operations</li>
</ul>

- utils: Provide utility functions and helpers for other modules.
- wrap_eth: Enable wrapping/unwrapping of ETH to WETH for DeFi protocol interactions.
