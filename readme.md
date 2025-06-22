# Papers

## AMM (Automated Market Makers)

### 1. Automated Market Makers and Decentralized Exchanges: A DeFi Primer
This paper explores Automated Market Makers (AMMs) in decentralized finance (DeFi), treating AMMs as black-box systems that convert tokens into prices via exchange functions. It examines various AMM types, including Constant Product, Constant Mean, Constant Sum, Hybrid Function, and Dynamic AMMs, and discusses the impact of concentrated liquidity. The framework provides a geometric representation of AMM operations and highlights similarities and differences across AMM types.

[Download full](/amm/1_Automated%20market%20makers%20and%20decentralized%20exchanges%20-%20DeFi%20primer%20.pdf)

### 2. Theory of Automated Market Makers in DeFi
This paper presents a theoretical framework for AMMs, focusing on their role in decentralized finance (DeFi). It introduces an abstract operational model of user-AMM interactions and formalizes fundamental properties of AMMs, including structural and economic aspects. The paper also provides a general solution to the arbitrage problem, a key game-theoretic foundation of AMMs.

[Download full](/amm/2_Theory%20of%20automated%20market%20makers%20in%20defi.pdf)

### 3. Automated Market Making and Arbitrage Profits in the Presence of Fees
This study extends the model of Milionis et al. to analyze the impact of trading fees on arbitrage profits in AMMs. It introduces fees and discrete Poisson block generation times, enabling the computation of the expected instantaneous rate of arbitrage profit in closed form.

[Download full](/amm/3_Automated%20Market%20Making%20and%20Arbitrage%20Profits%20in%20the%20Presence%20of%20Fees.pdf)

### 4. Dynamic Automated Market Makers for Decentralized Cryptocurrency Exchange
This paper proposes a dynamic AMM approach that uses market price oracles to adjust the mathematical relationship between assets in a liquidity pool. By continuously aligning the pool price with the market price, the approach eliminates arbitrage opportunities and enhances liquidity management.

[Download full](/amm/4_Dynamic%20Automated%20Market%20Makers%20for%20Decentralized%20Cryptocurrency%20Exchange.pdf)

### 5. Dynamic Curves for Decentralized Autonomous Cryptocurrency Exchanges
This work introduces dynamic curves for AMMs, leveraging market price oracles to automatically adjust asset relationships in liquidity pools. The approach eliminates the need for external arbitrageurs, maintains liquidity across assets, and preserves the total value of the pool under varying market conditions.

[Download full](/amm/5_Dynamic%20Curves%20for%20Decentralized%20Autonomous%20Cryptocurrency%20Exchanges.pdf)

### 6. Dynamic Function Market Maker (DFMM)
This paper proposes a Dynamic Function Market Maker (DFMM) protocol that addresses inventory risk management through data aggregation and order routing. The DFMM ensures price synchronization with external markets, optimizes inventory risk via arbitrageurs, and incorporates protective buffers to mitigate market volatility. The protocol offers a fully automated, decentralized solution for efficient and stable market making.

[Download full](/amm/6_Dynamic%20Function%20Market%20Maker%20(DFMM).pdf)

### 7. Coexisting Exchange Platforms: Limit Order Books and Automated Market Makers

A growing number of blockchain-based decentralized exchanges (DEX) have adopted Constant Function Market Makers (CFMMs)—a single-function algorithm to determine the execution
price for a trade. We build a model of coexisting exchanges where a centralized exchange (CEX)
with the traditional order-book mechanism operates in parallel with a DEX with the CFMM.
Traders are either informed or uninformed and endogenously choose their trading venue. We
first investigate how the arrival of the CFMM affects an adverse selection cost for market makers
and liquidity on both exchanges. Our result indicates that liquidity on the DEX has a positive
spillover effect on CEX liquidity. Secondly, we derive a profit function for liquidity providers
using the CFMM when there is an asymmetric information problem. As in the traditional market microstructure theory, informed trading imposes an adverse selection cost, while uninformed
noise trading adds value to liquidity pools. We analyze the market makers’ equilibrium behavior
and endogenize the amount of liquidity supplied via the CFMM.