# Growth Audit — Babbel

**Live:** https://bterzic123.github.io/babbel-flow-rebuild-v2/

Babbel asks every new learner which language, why, what they want to do, their level, their skills and how many minutes a day. The plan screen reads some of it back. Then come name, email and Sign in with Apple, and a paywall titled “Choose a plan that works for you” that says none of it. The 7-day free trial only appears after the paywall is closed.

This audit carries the learner's plan to the price, in Babbel's own design and at Babbel's own prices. The prototype runs three phones side by side, one per Meta ad group running today: three weeks to speaking, the Group Plan, and Lifetime.

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Ask for the account after the price | CR +8% · ARPU +17% |
| 02 | Make the paywall headline their plan | CR +15–20% |
| 03 | Let the wait read their answers back | CR +10–15% |
| 04 | Ask for reminders once they're in | CR +10–15% |
| 05 | Show the 7-day free trial on the paywall, not behind the X | CR +3–8% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps, not measured lift for Babbel.

Screens, copy, images, plans, prices and testimonials come from the Babbel iOS app as recorded on 11 November 2026 (euro storefront). The rating, review count and subscriptions sold come from the US App Store listing. The ads come from the Meta Ad Library, Babbel advertiser page, active ads on 11 November 2026.

## Run locally

```bash
python3 -m http.server 8921
```

Then open http://127.0.0.1:8921/ (add `?view=proto` to land on the prototype).
