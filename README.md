## Uniswap 系列汇总

[uniswap-v1](https://github.com/Louis-XWB/Uniswap-v1/)

[uniswap-v2-core](https://github.com/Louis-XWB/uniswap-v2-core)

[uniswap-v2-periphery](https://github.com/Louis-XWB/uniswap-v2-periphery)

[uniswap-v3-core](https://github.com/Louis-XWB/uniswap-v3-core)

[uniswap-v3-periphery](https://github.com/Louis-XWB/uniswap-v3-periphery)


# Uniswap-v3 源码学习

## Intro

Uniswap V3 是 Uniswap 的第三个版本，于 2021 年 6 月推出，相较于前两版，它引入了几个关键的创新和改进：

* **集中流动性**
    
     V3 引入了集中流动性（concentrated liquidity）的概念，允许流动性提供者（LP）在指定的价格范围内提供流动性。这提高了 LP 的资本效率，因为他们可以将流动性集中在他们认为最有价值的价格范围内。
     

* **多层费率**

    在 V3 中，流动性提供者（LP）可以根据所选择的价格区间风险选择不同的费率层级，如0.05%，0.30%，或者1.00%。

* **非同质化的流动性Token（NFT）**

    在之前的版本中，LP 获得的是同质化的代币（ERC-20）。在V3中，他们获得的是代表其流动性份额的非均质化代币（NFT），这使得每个流动性提供的位置独一无二。

* **其他**

    比如支持 ERC-20 和 ERC-721 代币，改进价格预言机，实现交易更低的 gas 成本，但总之， V3 升级的重点，就是通过提高流动性资本效率和提供更多的定制化选项，为用户和流动性提供者带来了显著的改进。
    



## Resources

Uniswap-v3 Whitepaper: [uniswap.org/whitepaper-v3.pdf](https://uniswap.org/whitepaper-v3.pdf)

Uniswap-v3 blog: [blog.uniswap.org](https://blog.uniswap.org/uniswap-v3)



