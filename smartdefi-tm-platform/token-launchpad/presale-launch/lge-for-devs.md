# 👤 面向开发者的 LGE

{% hint style="info" %}
此页面正在根据最新实施情况进行更新&#x20;
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=7SpIEcXtqYY" %}

假设您没有私人资金来为您的 SmartDeFi 项目添加流动性，在这种情况下，您可以使用流动性生成事件系统（简称 LGE，或像我这样的普通人所称的“预售”）从投资者那里收集流动性。

## 步骤 1 - 部署 LGE

<figure><img src="../../../.gitbook/assets/deploy LGE jan.jpg" alt=""><figcaption></figcaption></figure>

正如您所注意到的，LGE 部署器有相当多的选项供您自定义，让我们快速浏览一下它们：

**• 用于 LGE 的代币** （SD 代币数量）\
在这里，您可以决定希望将多少 SD 代币供应量用于预售。建议您投入 100% 的供应量。

**• 汇率** （每个 BNB 的 SD 代币数量）\
您在此处选择的代币数量将决定人们在预售期间和之后立即购买您的代币的价格。\
\- 注意：您在“资产背书份额”字段中选择的任何设置也会影响价格。

**• 最大购买量** （BNB/ETH）\
投资者可以用来购买您的预售的最大 BNB/ETH 数量。

**• 开始日期和时间** \
您可以选择预售可以激活和运行的确切日期和小时。

**• 持续时间** （天）\
您希望预售在自动关闭之前运行的天数。

**• 归属延迟** （天）\
系统可以分批释放锁定的流动性，您可以决定每批之间有多少天。

**• 归属率** （%）\
您可以决定在每个解锁批次阶段释放多少锁定的流动性。

**• 资产背书份额** （%）\
当 LGE 完成预售时，可以将收集到的 BNB/ETH 的一定百分比注入资产背书，以创建更稳定的代币。建议设置为 50%，以便一旦释放，代币的价格最初将与其资产背书价值相似。

**• 开发者份额** （%）\
系统可以给予 SD 所有者一定百分比的流动性并进行归属，就像对普通投资者进行归属一样。项目可以将此份额用于任何需要，例如营销、CEX 上市等。

**• FEG 份额** （%）\
系统会将收集到的 BNB/ETH 放入两个流动性池中，一个用于 SD/BNB，一个用于 SD/FEG。您可以选择如何拆分这两个流动性池。这也确保了您的投资者在预售结束后立即有机会进行套利，从而通过税收为您带来更多收入。

现在您已经为 LGE 选择了所有首选设置，是时候点击底部的“_批准_”按钮，接受您从钱包应用程序收到的任何批准，并支付执行交易所需的区块链 Gas 费。\
\
完成后，您会看到一个名为“_部署_”的新按钮，点击它并接受钱包批准，然后就完成了，您的 LGE 现在已部署并准备好根据您选择的设置运行。

### 1.1 在 LGE 激活前编辑

<figure><img src="../../../.gitbook/assets/edit presale after.jpg" alt=""><figcaption></figcaption></figure>

创建预售后，您有一个宽限期，可以在预售实际开始前对其进行编辑。\
在您的代币仪表板中，点击“编辑 LGE”，这将打开一个新的弹出菜单，您会注意到您刚才进行的所有设置，并且每个设置旁边都有一个“编辑”按钮，点击它即可编辑您需要的任何内容。\
请记住，一旦预售开始并上线，您将无法进行任何编辑。

### 1.2 预售白名单地址

<figure><img src="../../../.gitbook/assets/whitelist address.jpg" alt=""><figcaption></figcaption></figure>

当您在预售上线前对其进行编辑时，您可以选择为您的预售添加白名单，这意味着您可以添加一些 VIP 钱包地址，这些地址将在预售上线后获得预售的保证名额，这意味着预售将对公众锁定，直到 VIP 购买预售为止。\
每个 VIP 只能像其他任何用户一样投资相同数量的 ETH/BNB 参与预售，因此最大金额对每个人都有相同的上限。\
您首先需要启用白名单，然后添加您希望的地址，最后点击“白名单地址”按钮。\
在所有白名单地址购买预售后，预售将自动向公众开放，每个人都可以开始投资。\
预售将对公众锁定，直到所有白名单地址都购买预售为止。\
作为开发者，如果需要，您也可以从白名单中移除人员。如果您决定这样做，您也可以在启用白名单一段时间后完全禁用它，例如，如果其中一个白名单钱包变得不活跃并且没有购买预售，从而使普通用户无法参与预售。因此，如果您遇到一个或多个用户的问题，您可以选择将人员从白名单中移除或完全禁用它。

## 步骤 2 - 结束 LGE 并启动项目

如果您作为开发者在 LGE 结束后 72 小时内未开放交易，那么您的投资者将能够取消他们对 LGE 的参与并可以收回他们投资的资金。

如果 72 小时限制过去，人们开始从预售池中提取资金，并且金额低于软顶，开发者仍然能够启动项目进行交易。

预售可以通过 3 种方式结束：

### 2.1 预售售罄并达到硬顶

如果您成功筹集到了您设定的所有 BNB，那么您的预售将在达到硬顶的那一刻结束，无论这是否发生在预售开始仅 1 天后，而您的初始时间限制设定为 90 天。\
一旦预售结束，您作为开发者将需要通过我们的用户界面手动开放交易，此时系统会自动在 Pancakeswap 上为 BNB 或在 Uniswap 上为 ETH 和 BASE 设置您的流动性池。\
之后，您或您的投资者将需要前往 FEGex 上的预售页面，并点击“启用份额”按钮，以便您的投资者可以根据您设定的时间表开始领取他们的份额。

### 2.2 预售结束且仅达到软顶

<figure><img src="../../../.gitbook/assets/closed with softcap (1).jpg" alt=""><figcaption></figcaption></figure>

一旦预售的时间限制到达，并且它成功筹集到了软顶所需的金额，则认为预售成功，并将被放置在“已完成”子类别中。\
此时，任何人（无论是否为投资者）都可以前来点击“强制结束预售”。\
系统会自动在 Pancakeswap 上为 BNB 或在 Uniswap 上为 ETH 和 BASE 设置您的流动性池。\
之后，您或您的投资者将需要前往 FEGex 上的预售页面，并点击“启用份额”按钮，以便您的投资者可以根据您设定的时间表开始领取他们的份额。

### 2.3 预售结束但未达到软顶

<figure><img src="../../../.gitbook/assets/presale failed (1).jpg" alt=""><figcaption></figcaption></figure>

如果您的时间限制已到，但您未能筹集到足够的资金达到软顶，预售将自动移至“失败”子类别。\
此时，任何投资者都可以点击“中止预售”按钮，然后点击“退出预售”按钮，点击此按钮将导致您的预售资金以包装的 BNB/ETH 形式返还到您的钱包。

### 2.4 预售结束的特殊条件

预售结束后，开发者有 72 小时的宽限期来启动其项目的交易，否则，如果他们不这样做，在那之后投资者可以前来开始提取他们的投资。

如果达到软顶/硬顶但开发者在所述 72 小时后未部署交易，如果大多数投资者提取了他们的资金并且筹集的资金低于软顶水平（但非零），开发者仍然可以使用剩余资金部署预售。

如果达到软顶/硬顶但随后项目未启动且所有人都离开了（没有剩余资金），开发者稍后可以使用 endLGE 和 abortLGE 并使用新设置重新启动新的预售。

如果未达到软顶，开发者可以使用 abortLGE 并使用新设置创建新的 LGE。

## 示例

假设您刚刚创建了一个包含 100,000 个代币的项目，并将它们全部投入了预售。

假设您的硬顶是 1000 BNB。您需要弄清楚的第一件事是资产背书份额，对于此示例，假设为 35%。\
1,000 的 35% = 350 BNB 用于资产背书。\
因此 1,000-350= 650 BNB，这是将剩余用于 LP 的金额。

现在数学运算的第二部分开始了。\
这剩余的 650 BNB 将在 BNB 池和 FEG 池之间分配。\
假设 FEG 将占有 30% 的份额，这自动意味着 BNB 池将占 70%。\
因此 650 的 30% = 195 BNB，这是将用于购买 FEG 并设置 SD/FEG 池的 BNB 数量。\
650-195= 455 BNB，这是 SD/BNB 池中的 BNB 数量。

现在是最后一部分。\
假设您希望项目有 5% 的开发者份额。这意味着开发者将获得 SD/FEG 池的 5% 和 SD/BNB 池的 5%。\
因此开发者将收到：\
\- 价值 22.75 BNB 的 SD/BNB 归属 LP (455 * 5%)\
\- 价值 9.75 BNB 的 SD/FEG 归属 LP (195 * 5%) \
这些数字在预售结束的那一刻有效。之后交易将开始，当流动性池增加时，5% 开发者份额的美元价值也会增加。

## 开发者份额

作为您项目的开发者，您可以在设置 LGE 时选择激活开发者份额，最高可达预售中收集到的总 BNB 的 50%。\
预售结束后，您将有权按照与其他投资者相同的时间表领取您的份额，但有一个例外。\
与普通投资者不同，作为开发者，您可以领取更大的首次归属份额。首次归属份额的公式为 amt * (51 - devshare) / 10。“amt”是每个人在开始时从归属时间表中获得的金额，确保每个人都有一个公平的开始。\
这意味着您的开发者份额百分比越小，您的首次归属领取额就越大，因此，例如，如果您的开发者份额为 20%，则公式为 (51-20)/10 = 3.1x，这意味着与其余投资者相比，您的归属率在首次领取时将是您的 3.1 倍。
