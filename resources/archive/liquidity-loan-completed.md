# 💼 流动性贷款 [已完成]

## 还款总额 = 100% 已偿还 (2024 年 10 月 16 日)。



### 2023 年 3 月 13 日，FEG 获得了一笔 200 ETH 的贷款，转换为 BNB，用于在迁移后为新的代币合约补充 FEGbsc 流动性池。

## 贷款详情：

* 这笔贷款将以 200 ETH（发放时的形式）偿还。
* 将向 LP 提供者支付 50,000 美元的固定利息费用。

## 贷款偿还合约：

FEG (Feed Every Gorilla) 团队建立了一份新合约，制定了分配 FEG 50% 流动性的计划，包括 FEGeth 和 FEGbsc 代币。根据这项安排，流动性提供者 (LP) 贷款人可以每两周领取一部分流动性。

**合约主要特点：**

1. **每两周领取：** LP 贷款人有权每两周从每个链（FEGeth 和 FEGbsc）领取分配的 50% 流动性的最多 10%。\
   \- 注意：从 FEGbsc 流动性中提取的 BNB 将转换为 ETH，以保持准确的还款计数。
2. **战略性流动性管理：** 这种分阶段领取过程旨在为 FEG 代币的价格潜在上涨提供足够的时间。目标是使用少于分配的总 50%，剩余的流动性最终将返还给 FEG 流动性池，从而保持和稳定整体流动性。

## LP 合约已实施

LP 合约现已全面审计和测试。FEG 开发人员已成功实施该合约，并将一部分 LP 转入其中，具体交易如下：\
\
\- FEGbsc LP 移至贷款合约：

合约 1

https://bscscan.com/tx/0xbcd70a4e92518d83646fcd58753a76ddb0f8c333d4f6bd5400cd9697f6f676cc

合约 2

https://bscscan.com/tx/0x970b49dedcefbd8e8f194bd3223c4572401c2d02a61c6322a4f977edbb3b24d0&#x20;

\
\- FEGeth LP 移至贷款合约：

https://etherscan.io/tx/0x0c7a7916a0c12460dec959415d87ad273855c164e0149af8a5088cf1228ad976

***

## 利息偿还交易

2024 年 4 月 3 日

25,000 美元

https://etherscan.io/tx/0x33fa125ac18283d9d7d6ff39070b106d753a4467a30889bfb04551baa864833a

https://bscscan.com/tx/0xfefb48093e81c7de21285f93b839f46155ef30bbbf5a1244695c9709c6812689

https://bscscan.com/tx/0x7898a88b172511079401bae4a94a25c69cc9a525d0df1007c882da5b7cd6a3d0

## **解决流动性减少问题：“绑定”流动性解决方案**

为了应对这些提款可能导致的流动性减少，FEGrox 开发了一种创新的“绑定”合约。该合约允许用户贡献 ETH 或 BNB，这些资金将与贷款人提取流动性后未配对的 FEG 代币配对。

**绑定合约详情：**

* **期限：** 债券期限为一年。
* **债券回报：** 在此期限结束时，用户将收回他们“绑定”的 ETH 或 BNB，以及他们为该配对贡献的等值 FEG 代币。
* **风险意识：** 参与者应意识到无常损失的可能性，这是所有流动性提供者的常见风险。

“绑定”合约代表了一种战略性方法，旨在增强流动性池并减轻贷款人提取流动性的影响。这种方法不仅有助于维持健康的流动性水平，还允许用户为 FEG 生态系统做出贡献并从中受益。

有关此“绑定”机制的进一步信息将在适当时候发布，包括其测试和审计的详细信息。这一积极措施表明了 FEG 致力于为其用户和投资者维持强大的流动性和稳定的生态系统。

***

## 代币经济学

[代币经济学](../../feg-smartdefi-tm/about-feg-token/feg-tokenomics.md) 进行了调整以满足项目需求，包括提高总税收以纳入流动性注入税，这将有助于在贷款偿还期间稳定流动性。

***

## ETH 贷款和 ETH 到 BNB 转换交易

|                                                                                200 ETH 由贷款人发送                                                                                |                                                                                 ETH 到 BNB 转换                                                                                 |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [https://bscscan.com/tx/0x8ad053c6ced51d6a02ab253e49de1c32637090e0bba8076552fc91c4090826fb](https://bscscan.com/tx/0x8ad053c6ced51d6a02ab253e49de1c32637090e0bba8076552fc91c4090826fb) | [https://bscscan.com/tx/0xebb747ffeebdf4f498bd8d0585b6c66f9da9f68f9d58ecf2fac6a8a83aec3a7c](https://bscscan.com/tx/0xebb747ffeebdf4f498bd8d0585b6c66f9da9f68f9d58ecf2fac6a8a83aec3a7c) |
| [https://bscscan.com/tx/0x0ba3162a4b4096d86e37af4c128ecf54d9dd43504fcb5b5d7bc316f9b938e964](https://bscscan.com/tx/0x0ba3162a4b4096d86e37af4c128ecf54d9dd43504fcb5b5d7bc316f9b938e964) | [https://bscscan.com/tx/0xd0f0d3ffea907594f29e1f3e03a7d0c212faf65521e92ab623f60da9d0e8516d](https://bscscan.com/tx/0xd0f0d3ffea907594f29e1f3e03a7d0c212faf65521e92ab623f60da9d0e8516d) |
| [https://bscscan.com/tx/0x6a1d461e5b472ee10790ddc53127daca73a46013ea4dfae7b0a2a828bb5370c1](https://bscscan.com/tx/0x6a1d461e5b472ee10790ddc53127daca73a46013ea4dfae7b0a2a828bb5370c1) | [https://bscscan.com/tx/0xb4c6a34096ddfac65dfd585f6ef91cdb65d8a128b22106be8a10a605b92dc351](https://bscscan.com/tx/0xb4c6a34096ddfac65dfd585f6ef91cdb65d8a128b22106be8a10a605b92dc351) |
| [https://bscscan.com/tx/0x3dcb86988985690beea21605ece7deec3ffc71a1eccbdf1cab5a1a6ef08cef00](https://bscscan.com/tx/0x3dcb86988985690beea21605ece7deec3ffc71a1eccbdf1cab5a1a6ef08cef00) | [https://bscscan.com/tx/0x9386d633161551c3a59942feaab9c7d00aae7a0770a05bd40ec35682a58aa489](https://bscscan.com/tx/0x9386d633161551c3a59942feaab9c7d00aae7a0770a05bd40ec35682a58aa489) |
| [https://bscscan.com/tx/0x909d5fbbeb5dacceaddc505611dd770e8ee3faf6384f97248cc1b2df5484e0b1](https://bscscan.com/tx/0x909d5fbbeb5dacceaddc505611dd770e8ee3faf6384f97248cc1b2df5484e0b1) | [https://bscscan.com/tx/0x3bb7e146c824775c32f323921fdfeffc9b4b6941914aa3c186c0f47fbcd2e366](https://bscscan.com/tx/0x3bb7e146c824775c32f323921fdfeffc9b4b6941914aa3c186c0f47fbcd2e366) |
|                                                                                                                                                                                        | [https://bscscan.com/tx/0xb1abab7d58c29b9e9ef491f9839e74b6bfb5aba636bac25d4e468cfa29d732e6](https://bscscan.com/tx/0xb1abab7d58c29b9e9ef491f9839e74b6bfb5aba636bac25d4e468cfa29d732e6) |
|                                                                                                                                                                                        | [https://bscscan.com/tx/0x6369aaff0a8482c1c561aa4778fc927857cfa4498dd685703609f6a3a7f122ee](https://bscscan.com/tx/0x6369aaff0a8482c1c561aa4778fc927857cfa4498dd685703609f6a3a7f122ee) |

***

## 如何计算由代币经济学驱动的流动性注入

我们让用户可以直接在区块链上查看存储的资金；因此，通过税收为偿还贷款而收集的资金直接保存在代币合约内部。\
这些资金以 LP 代币的形式存储在 FEG 合约内部。\
\
**BSC LP 合约地址**：\
[https://bscscan.com/address/0xF53a1d602281B1ce2A92A1763364d2981269a72C](https://bscscan.com/address/0xF53a1d602281B1ce2A92A1763364d2981269a72C)\
**ETH LP 合约地址**：\
[https://etherscan.io/address/0x60EF1e0Bf9218Cdc1769a43c4B0B111ed38BB418](https://etherscan.io/address/0x60EF1e0Bf9218Cdc1769a43c4B0B111ed38BB418)\
\
要计算这些 LP 代币内部收集了多少 BNB/ETH：\
1. 点击代币下拉按钮查看 LP 合约中的 BNB 或 ETH 总量\
2. 在“代币追踪器”下点击 Pancake LP (BSC) 或 Uniswap V2 (ETH)。\
3. 点击“持有者”选项卡\
4. 找到 FEG 合约地址 (`0xbededDf2eF49E87037c4fb2cA34d1FF3D3992A11`)，它应该是排名第二的钱包持有者\
5. 向右滚动并记下排名第二的钱包（FEG 合约）持有的百分比\
6. 将该百分比乘以 LP 合约中的 BNB 或 ETH 总量，即可得出已产生的贷款偿还金额。

<figure><img src="../../.gitbook/assets/Screenshot_8 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Screenshot_9 (1).png" alt=""><figcaption></figcaption></figure>

***

## 贷款偿还交易（合约创建前）

首次偿还 20 ETH 于 2023 年 5 月 8 日完成。\
详情如下：&#x20;

{% code overflow="wrap" %}
```
12 wETH (ERC-20)
https://etherscan.io/tx/0xd9ed4d7c807a6b4a5ec5a24a4e9ce86bf08933a5c914d18c4765272c87396615

8 wETH (BEP-20)
https://bscscan.com/tx/0x559a180c15bde77651cb0dc6124201f735c76122a9970eb266da1174860a0139


📃流动性移除交易：

ETH:
从 FEG 合约移除：
https://etherscan.io/tx/0x52a52b5991450df3055b561af1c224601fc807f8cf4b11cfb7b44c350f3bdd00

从 Uniswap 移除：
https://etherscan.io/tx/0x0a91ad950c81d6b576a6d5c89b6c9d22b7fe5a5f7cdd81e36a10e2a769ca6722

BSC:
从 FEG 合约移除：
https://bscscan.com/tx/0xcec80058ac478d7742614b799a353fcbfb840c7653009df51f16442b97713064

从 PancakeSwap 移除：
https://bscscan.com/tx/0x2958802bc5897da99ac5638fcf5c480e50ce79ee127f55995ab8ab564fbb5a12

```
{% endcode %}
