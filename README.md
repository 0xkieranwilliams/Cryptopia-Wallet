1. The Graph Integration
Utilizes two subgraphs (Uniswap V3 Base & Bunni V2 Base) on the Base network to query and analyze on-chain data. The integration supports several specialized queries:

Large Swap Detection: Identifies whale exits by flagging transactions with sell volumes above a configurable threshold (e.g., $100,000+ USD).
Emerging Liquidity Pools: Spots new pools with high Total Value Locked (TVL) that are experiencing rapid growth (e.g., TVL > $1,000,000 with 50%+ growth in 24 hours).
High Fee Pools: Finds liquidity pools offering high fee returns (e.g., fee tiers above 5000, implying high APY).
Undervalued Tokens: Searches for tokens that might be undervalued based on a low TVL-to-Market Cap ratio, provided they have significant liquidity.
Whale Accumulation: Detects early whale activity by monitoring large buy transactions (e.g., >$250,000 within 24 hours).
Swap Trends Analysis: Reviews historical swap data (over the last 7 days) to gauge market sentiment.
Gas Fee Insights: Examines transactions with the highest gas usage in the past 24 hours to provide insight into network cost dynamics.
Arbitrage Opportunities: Compares pool data and computed prices between different decentralized exchanges (DEXs) to highlight potential arbitrage margins.
2. Browser Search Integration
Dynamic Internet Search: If deeper context or real-time information is needed, the agent can trigger a browser-based search. It asks for user consent before proceeding and then uses a dedicated tool (named "when_no_api_search_like_human") to perform multi-step searches on the internet.
3. Crypto Compare API Integration
Offers real-time and historical market data along with crypto news:

News Fetching: Retrieves the latest news articles about specific tokens, including titles, bodies, sources, and publish times.
Price Data: Provides current cryptocurrency prices with support for multiple currencies.
Trading Signals: Fetches advanced trading signals and market indicators (such as network activity, large transaction patterns, and holder behavior) from analytics providers like IntoTheBlock.
Market Cap Rankings: Lists top cryptocurrencies by market capitalization along with key metrics like price, volume, and circulating supply.
Exchange Rankings: Identifies the top exchanges for specific trading pairs based on volume, market share, and price variations.
Volume Leaders: Retrieves rankings of cryptocurrencies based on their total trading volume.
4. Moralis API Integration
Enables deep wallet and blockchain data retrieval:

Wallet History & Balance: Fetches transaction histories and current balances for any given wallet on various blockchains.
NFT and Token Transfers: Provides details on NFT transfers, ERC20 token transfers, and overall NFT trading activities.
Token Holdings & DeFi Positions: Lists all tokens held by a wallet and shows current DeFi positions.
Price Retrieval: Supports fetching current prices for single tokens or in batch, including options for percent-change data.
OHLCV Data: Retrieves historical Open-High-Low-Close-Volume data for trading pairs to assist with technical analysis.
Wallet Net Worth & Stats: Calculates the overall net worth of a wallet (filtering out spam or unverified tokens) and provides statistical insights into wallet activity.
5. Wow Launch Pad Integration
Multi-Token Contract Deployment: Offers the ability to deploy new multi-token contracts with a customizable base URI for token metadata. This is useful for launching collections or projects with multiple tokens.
6. ERC-20 Token Swapping on Uniswap V3 Base
Swapping Functionality: Facilitates the swapping of ERC-20 tokens on the Uniswap V3 platform operating on the Base network, allowing for on-chain token exchanges directly through the agent.
