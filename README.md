---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 📜 Overview

### Introduction <a href="#introduction-to-jackramp" id="introduction-to-jackramp"></a>

LiquidBook is a decentralized exchange protocol that brings traditional order book trading to the blockchain through Arbitrum Stylus. By utilizing Rust-based smart contracts compiled to WebAssembly, LiquidBook achieves high performance and low transaction costs while maintaining the familiar trading experience of centralized exchanges. The protocol leverages Arbitrum Stylus's unique capabilities to create an efficient, secure, and transparent trading environment where users can place limit and market orders with minimal fees.

Through its implementation on Arbitrum Stylus, LiquidBook provides traders with a powerful yet intuitive platform that combines the best aspects of traditional finance with the benefits of decentralization. The protocol features real-time order matching, transparent price discovery, and secure settlement, all while maintaining true decentralization and user custody of funds.

### Key Features <a href="#key-features" id="key-features"></a>

*   **Orderbook Spot Trading**&#x20;

    LiquidBook's core feature is its decentralized spot trading system built on a true orderbook model. Unlike AMM-based DEXs, our implementation provides traditional orderbook functionality with limit and market orders, offering traders the familiar experience of centralized exchanges while maintaining full decentralization. The orderbook is optimized for efficient matching and execution, enabling precise price discovery and capital-efficient trading.
*   **Rehypothecation**&#x20;

    When users place limit orders, their funds typically sit idle while waiting for order execution. However, LiquidBook's unique rehypothecation feature allows these idle funds to be put to work, generating additional yield for traders during the waiting period. This breakthrough approach maximizes capital efficiency by enabling users to earn returns on their locked collateral while still maintaining their desired trading positions.

    _Note: Still on development._
*   **Multi-Pairs Limit Order**&#x20;

    Users can leverage a single USD collateral to place multiple limit orders across different assets simultaneously - whether it's BTC, ETH, SOL, or any other supported tokens. This unique feature enables traders to cast a wider net, increasing their opportunities to capture the best possible prices across various trading pairs without needing separate collateral for each position at their full USD collateral.

    _Note: Still on development._
*   **Permission Less**&#x20;

    Anyone can freely create and list new trading pairs without requiring approval or governance decisions. This groundbreaking approach means that token creators and communities can immediately list their tokens and create liquidity for trading, eliminating the traditional barriers and waiting periods associated with centralized exchanges or governed DEXs. Whether it's a newly launched token or an existing one, users have the freedom to create markets instantly and start trading.

    _Note: Still on development._

