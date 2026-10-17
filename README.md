# Pay USD From Anywhere

If you're a developer outside the US (or in a country Stripe won't touch), the hardest part of building a SaaS isn't building it — it's finding a payment platform that will actually pay you in USD.

This repo is a starter map. Full comparisons of 50 platforms: **https://workspace-zeta-dun.vercel.app**

## The three questions that decide everything

Before you compare fees, answer these in order. They eliminate most options fast.

1. **Your country** — not your customers' country. Yours.
2. **Your entity type** — individual / sole proprietor / registered company. Most MoRs accept individuals; most raw processors don't.
3. **What you sell** — SaaS subscription, one-off digital product, course, license keys. Some platforms refuse certain categories.

## Platforms worth knowing

Verified against official sources where stated.

| Platform | Model | Confirmed facts | Good for |
|---|---|---|---|
| **Polar** | MoR | 5% + $0.50; lower tiers at 3.8%, 3.6%, 3.4% with $20/$100/$400 monthly plans. Onboarding open to individuals. | Subscription SaaS, OSS maintainers |
| **Creem** | MoR | 3.9% + $0.40 per transaction, no monthly fee, no minimum. You don't need a registered company. | Bootstrapped founders, AI tools |
| **Dodo Payments** | MoR | US cards 4% + $0.40; international cards +1.5%; subscriptions +0.5%; ACH/SEPA 1.5% capped at $15. Minimum payout $100 (reducible to $50). Confirmed by their support team: payouts go straight to a Payoneer receiving account. | Developers in India, Nigeria, Pakistan, Bangladesh, Brazil |
| **Payhip** | Platform / MoR | No monthly fee. Accepts sellers globally. Runs its own 50% recurring affiliate program. | Digital products, courses |
| **FastSpring** | MoR (quote-based) | Publishes no rate card — you build a custom quote. Heavier onboarding. | Established software vendors |

## Watch out

- **Lemon Squeezy was acquired by Stripe in 2024.** It still works, but treat it as a Stripe product now, not an indie alternative.
- Stripe alone is often the wrong answer. Stripe's supported-country list is shorter than most people assume — check it before you design around it.
- "Merchant of Record" (MoR) means the platform is the legal seller. It handles VAT/sales tax, fraud and chargebacks for you. That usually removes any need to register a local entity — which is the single biggest unlock for developers in restricted countries.

## Getting the money out

Having a platform pay you is half the job. Getting USD into your bank is the other half.

Payoneer gives you a US receiving account (Citibank, with an ABA routing number) that most platforms can pay into via ACH. Verified from their official fee page (updated 2026-01-01):

- Free to register, no monthly fee
- $29.95 annual fee — only charged if you receive less than $6,000 in any rolling 12 months, and explicitly waived in year one
- Receiving from a US ACH / European bank: 1%
- Receiving via card: up to 3.99% + $0.49
- Withdrawing to a local bank (currency conversion involved): 1.2%–4%, per the range shown in your account

## The honest part

Every number above changes. Platforms revise pricing, and some quietly restrict countries.

Where a row here conflicts with the platform's own pricing page, the platform's page wins. If you spot something stale, open an issue.

---

Full interactive version with filters by country, entity and product type: **https://workspace-zeta-dun.vercel.app**
