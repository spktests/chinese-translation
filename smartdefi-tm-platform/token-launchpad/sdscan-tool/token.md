# 🔶 代币

用于管理 SmartDeFi 代币。可通过 SDscan - Token - Token 合约访问

<mark style="color:orange;">**此页面正在开发中**</mark>

### **读取**

<details>

<summary>读取命令</summary>



1. BackingLogicAddress() - 检查代币的资产背书合约
2. DATA_READ()
3. LGE()
4. LGEAddress()
5. LGELive()
6. LPBURN()
7. UNISWAP_V2_ROUTER()
8. User(address)
9. WETH()
10. _UNISWAP_V2_ROUTER()
11. allFee(uint256) - 需要分别调用。0-5 买入/转账税，6-11 卖出税

    backing: 0,

    &#x20; burn: 1,

    &#x20; liquidity: 2,

    &#x20; growth: 3,

    &#x20; staking: 4,

    &#x20; reflection: 5,

    backing: 6,

    &#x20; burn: 7,

    &#x20; liquidity: 8,

    &#x20; growth: 9,

    &#x20; staking: 10,

    &#x20; reflection: 11


12. allLastBalance(address)
13. allUser(uint256)
14. allowance(address,address) - 检查是否已授权支出（例如，检查代币是否已批准用于其他智能合约）。
15. backingThreshold() - 资产背书合约将从资产背书税中累积的代币转换为资产背书的阈值
16. balance(address,uint256)
17. balanceOf(address) - 检查钱包或合约的余额
18. blockNumber(address,uint256)
19. checkLiquidityLock(address) - 检查流动性是否锁定在 SD 代币合约中
20. checkWhiteListContract(address) - 检查合约是否在白名单中
21. decimals() - 检查代币有多少位小数
22. frontRun(address,uint256)
23. getAllFee(uint256)
24. isExchange(address) - 检查合约是否被指定为交易所状态（应用代币经济学税）
25. lastBalance(address)
26. liqShare()
27. liquidityThreshold() - 流动性合约将从流动性税中累积的代币转换为配对资产的阈值（如果代币与 WBNB 配对，合约将把累积的代币转换为 WBNB）。
28. liquidityUnlockTime(address) - 如果 LP 代币被锁定在 SD Lock 中，检查流动性解锁时间。不涉及第三方代币锁定服务提供商。
29. name() - 代币名称
30. onlySB()
31. owner() - SD 所有者
32. sdFeeRecipient()
33. sdOwner() - 检查 SD 代币所有者
34. sdStake()
35. suggestedAllFee(uint256)
36. suggestedOnlySB()
37. symbol() - 获取代币符号
38. taxFree(address) - 检查钱包或合约地址是否免税
39. timeDelay()
40. tokenFromGift(uint256)
41. totalHolders() - 获取总持有者数量
