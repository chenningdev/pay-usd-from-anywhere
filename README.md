# Pay USD From Anywhere随时随地用美元收款

If you're a developer outside the US (or in a country Stripe won't touch), the hardest part of building a SaaS isn't building it — it's finding a payment platform that will actually pay you in USD.如果你是美国以外的开发者（或身处Stripe不予支持的国家），构建SaaS时最棘手的问题并非开发本身，而是找到一个能够真正以美元向你付款的支付平台。

This repo is a starter map. Full comparisons of 50 platforms: **https://workspace-zeta-dun.vercel.app**本仓库是一个入门级地图。50个平台的完整对比：**https://workspace-zeta-dun.vercel.app**

## The three questions that decide everything##决定一切的三个问题决定一切的三个问题##决定一切的三个问题

Before you compare fees, answer these in order. They eliminate most options fast.在比较费用之前，请按顺序回答以下问题。它们能迅速排除大多数选项。在比较费用之前，请按顺序回答以下问题。它们能迅速排除大多数选项。

1. **Your country** — not your customers' country. Yours.1. **您所在的国家**— 不是您的客户所在国家，而是您自己的国家。
2. **Your entity type** — individual / sole proprietor / registered company. Most MoRs accept individuals; most raw processors don't.2. **您的实体类型**— 个人/个体工商户/注册公司。大多数MoR接受个人；而大多数原料加工企业则不接受。**您的实体类型**— 个人/个体工商户/注册公司。大多数支付处理商接受个人；而大多数原始支付处理商则不接受。
3. **What you sell** — SaaS subscription, one-off digital product, course, license keys. Some platforms refuse certain categories.3. **您销售的产品**— SaaS 订阅、一次性数字产品、课程、许可证密钥。某些平台会拒绝特定品类。

## Platforms worth knowing (verified against official sources)##值得了解的平台（已对照官方资料核实）值得了解的平台（已对照官方资料核实）##Platforms worth knowing (verified against official sources)

| Platform | Model | Confirmed facts | Good for ||平台|模式|已确认的事实|适用场景|| 平台 | 模式 | 已确认的事实 | 适用场景 |
|---|---|---|---|
| **Polar** | MoR | 5% + $0.50; lower tiers at 3.8%, 3.6%, 3.4% with $20/$100/$400 monthly plans. Onboarding open to individuals. | Subscription SaaS, OSS maintainers || **极地**| MoR | 5% + 0.50美元；较低等级分别为3.8%、3.6%、3.4%，对应每月20美元、100美元、400美元的套餐。个人用户也可申请入驻。| 订阅制SaaS，开源软件维护者 ||**极地** |MoR|5% + 0.50美元；较低档位分别为3.8%、3.6%、3.4%，对应每月20美元、100美元、400美元的套餐。现已面向个人开放入驻。|订阅制SaaS，面向开源维护者|
| **Creem** | MoR | 3.9% + $0.40 per transaction, no monthly fee, no minimum. You don't need a registered company. | Bootstrapped founders, AI tools || **Creem**| MoR | 每笔交易收取3.9% + 0.40美元，无月费，无最低限额。您无需注册公司。| 自筹资金的创始人、AI工具 ||**Creem** |MoR|每笔交易收取3.9% + 0.40美元，无月费，无最低限额。您无需注册公司。|初创创始人、AI工具|
| **Dodo Payments** | MoR | US cards 4% + $0.40; international cards +1.5%; subscriptions +0.5%; ACH/SEPA 1.5% capped at $15. Minimum payout $100 (reducible to $50). **Confirmed by their support team: payouts go straight to a Payoneer receiving account.经其支持团队确认：款项将直接汇入Payoneer收款账户。**| MoR | 美国卡4% + 0.40美元；国际卡加1.5%；订阅服务加0.5%；ACH/SEPA手续费1.5%，最高不超过15美元。最低提现金额100美元（可降至50美元）。**Confirmed by their support team: payouts go straight to a Payoneer receiving account.经其支持团队确认：款项将直接汇入Payoneer收款账户。** | Developers in India, Nigeria, Pakistan, Bangladesh, Brazil || **多哆支付**| 印度、尼日利亚、巴基斯坦、孟加拉国、巴西的开发者 ||**多哆支付** |MoR|美国卡4% + 0.40美元；国际卡加1.5%；订阅服务加0.5%；ACH/SEPA 1.5%，最高不超过15美元。最低提现金额为100美元（可降至50美元）。**经其客服团队确认：款项将直接汇入Payoneer收款账户。** |印度、尼日利亚、巴基斯坦、孟加拉国、巴西的开发者|
| **Payhip** | Platform / MoR | No monthly fee. Accepts sellers globally. Runs its own 50% recurring affiliate program. | Digital products, courses || **Payhip** |平台 / MoR|无月费。全球范围内接受卖家入驻。自主运营50%的持续性联盟推广计划。|数字产品、课程|| **Payhip**| 平台 / MoR | 无月费。全球范围内接受卖家入驻。自主运营50%的持续性联盟推广计划。| 数字产品、课程 ||**Payhip**|平台 / MoR|无月费。全球范围内接受卖家入驻。自主运营50%的持续性联盟推广计划。|数字产品、课程|
| **FastSpring** | MoR (quote-based) | Publishes **no** rate card — you build a custom quote. Heavier onboarding. | Established software vendors || **FastSpring** |MoR（基于报价）|发布**无**费率表——需自行制定定制化报价。入驻流程较为复杂。|成熟软件厂商||**FastSpring| MoR（基于报价）| 发布无费率表——需自行制定定制化报价。入驻流程较为复杂。|成熟软件厂商|

## Watch out##请注意##请注意##

- **Lemon Squeezy was acquired by Stripe in 2024.** It still works, but treat it as a Stripe product now, not an indie alternative.- **Lemon Squeezy已于2024年被Stripe收购。**目前仍可正常使用，但请将其视作Stripe的产品，而非独立的替代方案。它仍然可以使用，但请将其视为Stripe的产品，而非独立的替代方案。- **Lemon Squeezy已于2024年被Stripe收购。**目前仍可正常使用，但请将其视作Stripe的产品，而非独立的替代方案。
- Stripe alone is often the wrong answer. Stripe's supported-country list is shorter than most people assume — check it before you design around it.-仅靠 Stripe 往往并非最佳选择。Stripe 支持的国家/地区列表比大多数人想象的要少——在据此进行产品设计之前，请务必先核实。仅靠 Stripe 往往并非最佳选择。Stripe 支持的国家/地区列表比大多数人想象的要少——在据此进行产品设计之前，请务必先核实。
- "Merchant of Record" (MoR) means **the platform is the legal seller**. It handles VAT/sales tax, fraud and chargebacks for you. That usually removes any need to register a local entity — which is the single biggest unlock for developers in restricted countries.-“注册商户”（MoR）是指**该平台即为合法销售方**它会为您处理增值税/销售税、欺诈和拒付等问题。这通常使您无需注册当地实体——而这正是限制国家/地区开发者面临的最大障碍之一。“注册商户”（MoR）是指。它为您代为处理增值税/销售税、欺诈及拒付等事务。这通常使您无需在本地注册实体——而这正是身处受限国家的开发者所面临的最大障碍得以解除的关键所在。

## Getting the money out##如何提取资金如何提取资金如何提取资金##如何提取资金如何提取资金

Having a platform pay you is half the job. Getting USD into your bank is the other half.让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。让平台支付给你，只是完成了一半的工作。而将美元转入你的银行账户，则是另一半。

Payoneer gives you a **US receiving account** (Citibank, with an ABA routing number) that most platforms can pay into via ACH. Verified from their official fee page (updated 2026-01-01):Payoneer 为您提供一个**美国收款账户**（花旗银行，带有ABA路由号码），大多数平台均可通过 ACH 方式向该账户付款。经其官方费用页面核实（更新于 2026-01-01）：Payoneer 为您提供一个美国收款账户**（花旗银行，带有ABA路由号码），大多数平台均可通过 ACH 方式向该账户付款。经其官方费用页面核实（更新于 2026-01-01）：

- Free to register, no monthly fee-免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费免费注册，无月费-免费注册，无月费-免费注册，无月费
- $29.95 annual fee — **only** charged if you receive less than $6,000 in any rolling 12 months, and explicitly waived in year one-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收——年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收-年费29.95美元——**仅在任意连续12个月内收款不足6,000美元时收取，且首年明确免收
- Receiving from a US ACH / European bank: **1%**-通过美国ACH或欧洲银行收款：**1%**-通过美国ACH或欧洲银行收款：
- Receiving via card: up to 3.99% + $0.49-通过银行卡收款：最高3.99% + 0.49美元-通过银行卡收款：最高3.99% + 0.49美元通过银行卡收款：最高3.99% + 0.49美元-通过银行卡收款：最高3.99% + 0.49美元通过银行卡收款：最高3.99% + 0.49美元-通过银行卡收款：最高3.99% + 0.49美元-通过银行卡收款：最高3.99% + 0.49美元-通过银行卡收款：最高3.99% + 0.49美元
- Withdrawing to a local bank (currency conversion involved): 1.2%–4%, per the range shown in your account-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准-提现至本地银行（涉及货币兑换）：1.2%–4%，具体费率以您账户显示的范围为准

## The honest part##诚实透明的部分

Every number above changes. Platforms revise pricing, and some quietly restrict countries.以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。以上所有数字均可能发生变化。各平台会调整定价，且部分平台还会悄然限制某些国家/地区的使用。

Where a row here conflicts with the platform's own pricing page, **the platform's page wins.** If you spot something stale, open an issue.当此处某一行与平台自身的定价页面发生冲突时，**以平台页面为准。**如果您发现任何过时的信息，请提交问题。**当此处某一行与平台自身的定价页面发生冲突时，**以平台页面为准。如果您发现任何过时的信息，请提交问题。当此处某一行与平台自身的定价页面发生冲突时，**以平台页面为准。**如果您发现任何过时的信息，请提交问题。当此处某一行与平台自身的定价页面发生冲突时，**以平台页面为准。如果您发现任何过时的信息，请提交问题。

---

Full interactive version with filters by country / entity / product type: **https://workspace-zeta-dun.vercel.app**支持按国家/实体/产品类型筛选的完整交互式版本：**https://workspace-zeta-dun.vercel.app**Full interactive version with filters by country / entity / product type:**https://workspace-zeta-dun.vercel.app**带有按国家/实体/产品类型筛选的完整交互式版本：**https://workspace-zeta-dun.vercel.app**支持按国家/实体/产品类型筛选的完整交互式版本：带有按国家/实体/产品类型筛选的完整交互式版本：支持按国家/实体/产品类型筛选的完整交互式版本：**https://workspace-zeta-dun.vercel.app**
