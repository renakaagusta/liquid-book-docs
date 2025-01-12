# 🔍 Problem

### 1. Limitations of AMM-based DEXs

Current Automated Market Maker (AMM) DEXs dominate the decentralized trading landscape, but their fundamental design creates significant inefficie

*   #### Slippage Costs

    Slippage remains one of the most significant barriers to efficient trading on current AMM-based decentralized exchanges. Every trade on an AMM, regardless of size, experiences some level of price slippage due to the fundamental mathematical models these protocols employ. When traders attempt to execute larger orders, they face substantial price impacts that can significantly erode their trading profits. This inherent design flaw makes AMMs particularly unsuitable for institutional traders and professional market makers who need to move large volumes without incurring excessive costs.
*   **Capital inefficiency**&#x20;

    AMMs creates a persistent drag on returns for liquidity providers and restricts the protocol's ability to scale effectively. The current model requires liquidity to be distributed across an entire price curve, meaning vast amounts of capital sit idle and unproductive. This inefficient capital allocation forces liquidity providers to lock up substantially more assets than necessary to support trading activity, resulting in diluted yields and suboptimal resource utilization. As trading volumes grow, the capital requirements scale disproportionately, making the system increasingly inefficient at larger sizes.
*   **Impermanent loss**&#x20;

    Impermanent loss represents an unavoidable risk that plagues liquidity providers in AMM protocols. This complex phenomenon can cause portfolio values to decline even in relatively stable market conditions, creating a significant barrier to participation for sophisticated capital providers. The mathematical complexity of impermanent loss makes risk assessment challenging, and there are no native mechanisms within AMMs to prevent these losses without relying on additional protocols or complex derivatives. This fundamental risk factor often results in returns that underperform simple buy-and-hold strategies.
*   **Price discovery**

    Price discovery in AMM systems falls short of true market efficiency. Rather than reflecting direct market sentiment, prices are determined by rigid mathematical formulas that react slowly to changing market conditions. Traders have no mechanism to directly signal their price preferences or contribute to price discovery through limit orders. This limitation creates artificial barriers to market efficiency and can lead to persistent price discrepancies between AMM markets and broader cryptocurrency markets.

### 2. Current Solutions and Their Limitations

Existing attempts at order book DEXs have largely relied on hybrid solutions that compromise decentralization for performance. Current implementations typically use off-chain order books with on-chain settlement, introducing trust assumptions and potential points of failure. This architecture creates a fragmented liquidity landscape where traders must navigate multiple isolated venues, each with its own liquidity pools and trading pairs. The reliance on centralized components for order matching and execution contradicts the fundamental promise of DeFi: true decentralization and trustlessness.

Layer 2 solutions have attempted to address these limitations by moving order book operations to separate chains, but this approach introduces additional complexity in bridging and settlement. Users must lock their assets in bridge contracts, creating new security risks and friction in the trading experience. The multi-step process of bridging assets, placing orders, and settling trades increases both transaction costs and execution time, making these solutions impractical for high-frequency trading or sophisticated market making strategies.

####
