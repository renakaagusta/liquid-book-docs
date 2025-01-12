# 🧩 Challenge

Building an orderbook DEX using Arbitrum Stylus technology presents unique challenges. While Stylus enables the development of smart contracts in Rust on the Arbitrum network, the combination of complex orderbook implementation, Rust learning curve, and technical constraints requires careful consideration and significant development effort at first.

### Challenges

*   #### Complex Orderbook Implementation with New Language

    Building an orderbook DEX is inherently complex, requiring careful handling of order matching, price-time priority, and state management. This complexity is amplified by implementing it in Rust, a language our team had no prior experience with since our team comes from a Solidity development background. Learning Rust's unique concepts while simultaneously implementing complex orderbook logic that we would typically handle in Solidity created a steep learning curve and development challenges.
*   #### WASM Size Constraints

    The verification process is not instant due to the early-stage development of zk technology, which requires time to securely validate transactions and ensure data integrity.
*   **Limited Documentation and Examples**&#x20;

    The relatively new nature of Stylus technology means there is limited documentation and few real-world examples for complex use cases. While Offchain Labs provides excellent foundational documentation for Stylus development, implementing complex systems like an orderbook DEX often requires deeper exploration. The official documentation serves as a solid starting point, but for specific use cases and advanced implementations, we found ourselves needing to dive deeper - sometimes reaching out directly to the developer community through official channels. This direct engagement with the Stylus developer group proved invaluable for resolving complex technical challenges not covered in the standard documentation.
