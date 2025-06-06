# 🎁 质押

<figure><img src="../../.gitbook/assets/Screenshot_18.png" alt=""><figcaption></figcaption></figure>

### 持有者的被动奖励

加密货币投资者总是在寻找最大化其持仓并产生被动奖励的方法，而质押协议正提供了这样的机会。它允许持有者质押他们的代币，并从去中心化交易所（如 PancakeSwap 或 Uniswap）的交易量中赚取奖励。

### 质押合约功能

<table data-card-size="large" data-column-title-hidden data-view="cards"><thead><tr><th></th><th></th><th data-hidden></th></tr></thead><tbody><tr><td><strong>质押合约定制</strong></td><td>所有者可以自定义他们的质押，例如存入和提取费用、费用分配、解除质押延迟以及额外奖励。</td><td></td></tr><tr><td><strong>自动奖励分配</strong></td><td>奖励会自动分配和复利，这意味着用户无需手动领取或再投资他们的收益。</td><td></td></tr><tr><td><strong>可升级合约</strong></td><td>质押合约将在用户和 SD 项目所有者无需采取任何行动的情况下进行升级。</td><td></td></tr><tr><td><strong>奖励来源</strong></td><td>奖励可以来自交易，也可以来自所有者手动注入的其他代币奖励<em>（最多 30 种不同的奖励）</em></td><td></td></tr><tr><td><strong>SDSS 代币</strong></td><td>质押后，用户会收到 SD 质押份额 (SDSS) 来代表他们在质押池中的所有权。为安全起见，SDSS 不可转让</td><td></td></tr><tr><td><strong>牺牲功能</strong></td><td>用户可以选择在解除质押时销毁一定比例的质押奖励，以帮助减少流通代币供应量</td><td></td></tr><tr><td>无锁定期限的灵活性允许您随时解除质押，或者项目开发者可以为其项目选择自定义期限。</td><td></td><td></td></tr><tr><td>开发者可以决定他们的项目是否收取存入和提取费用，以更好地适应其代币经济学</td><td></td><td></td></tr></tbody></table>

### **质押奖励来源和分配**

质押奖励来源于 SmartDeFi 项目的链上交易活动；它们会自动复利，并随时可供用户使用。\
\
此外，项目所有者可以手动注入其他代币/币种奖励发送给质押者。\
其他代币奖励按轮次发放，并受一定的累积阈值限制。开发者可以修改奖励的累积阈值，不同类型的奖励可能有所不同。\
\
例如，如果阈值为 1 wBNB，则当奖励池累积到 1 wBNB 时发放奖励。

{% hint style="warning" %}
在首次质押后的前 30 天内解除质押或增加质押池将导致 50% 的奖励损失。\
\- 所述被没收的奖励随后将分配给其他利益相关者。&#x20;
{% endhint %}

### **什么是 SDSS**

质押后，您的 SD 代币将被存入质押合约，作为回报，您将获得称为 SmartDeFi 质押份额 (SDSS) 的新代币。这些份额代表您在质押池中的所有权。可以将 SDSS 视为系统确认您已成功质押的收据。您需要向系统出示此收据，才能让您解除质押并取回您的 SD 代币。

* SDSS 不是 1:1 的比例
* SDSS 会随着每次获得的代币奖励而更新
* 总 SDSS / 总 SD = 比率
* 无法将 SDSS 转移到另一个钱包。

### 可选的“牺牲”

根据社区要求，新的质押合约引入了牺牲功能，供那些希望帮助销毁工作并减少流通代币供应量的人使用。

解除质押时，质押者可以销毁其质押奖励的指定百分比，从而有效地将其从流通供应中移除。

要激活此功能，您必须指定要牺牲的百分比和要解除质押的数量。

{% hint style="success" %}
在解除质押之前的任何时候，您都可以通过在牺牲设置中将其设置为 0% 来关闭牺牲功能。
{% endhint %}
