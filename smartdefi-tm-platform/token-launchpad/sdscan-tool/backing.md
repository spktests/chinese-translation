# 🔷 资产背书

<mark style="color:orange;">**此页面正在开发中**</mark>

**读取**

<details>

<summary>读取命令</summary>



1. DATA_READ()
2. UNISWAP_V2_ROUTER()
3. _UNISWAP_V2_ROUTER()
4. backingAsset()
5. collateral()
6. lendData(address)
7. loansBase(address)
8. loansToken(address)
9. oneTokentoBacking(uint256) - 显示每 1 个代币有多少资产背书可用
10. range()
11. uniswapV2Pair()

</details>

**写入**

<details>

<summary>写入命令</summary>



1. convertAll(uint256,uint256,uint256)
2. extendLoan() - 延长 SmartLoan
3. flashLoan(uint256,address,bytes) - 用于流动性率为 0.08% 的 Smart Flash-Loan
4. liquifyForBacking(uint256)
5. loan(uint256) - 使用此命令获取 SmartLoan
6. repayLoan(uint256) - 使用此命令偿还 SmartLoan
7. setFrontRunRange(uint256)

</details>
