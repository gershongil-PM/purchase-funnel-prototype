# Purchase Funnel Prototype

A clickable concept prototype of a purchase funnel for people starting a small business. Open `index.html` in a browser; there is no build step.

## The flow

1. **Your business:** name, optional tagline, type of business.
2. **Your stage:** just an idea, already selling, or registered. The answer drives the plan recommendation.
3. **Your logo:** four generated logos, filtered by type (icon, name, initials), shown on a business card and a profile picture.
4. **Your plan:** three plans with a recommended one and a reason, a billing toggle (monthly, yearly, 2 years, 3 years) with savings, and optional add-ons. Nothing is pre-selected.
5. **Launch:** a checklist of next steps (LLC, tax ID, website, business bank account).

## The experiment

One hypothesis runs through the whole flow: personalizing the plan recommendation and its supporting messaging based on users' business stage and stated needs will increase purchase conversion compared with a generic recommendation.

- **Control (A):** everyone sees the same plan marked Recommended.
- **Treatment (B):** the recommended plan and a one-line reason adapt to the stage answer.
- **Primary metric:** plan-to-purchase conversion rate = unique users completing a purchase ÷ unique users exposed to the plan screen.
- **Decision rule:** ship B if it produces a statistically significant improvement in purchase conversion, with no material deterioration in refund rate, early cancellation rate, or revenue per purchaser. Sample size and duration are set before launch.
- **Guardrails:** refunds in the first 14 days, early cancellations, average revenue per purchaser.

The PM notes panel (toggle in the top bar) holds the full experiment brief and a switch to preview A or B. For each screen it explains the screen's role in the hypothesis, its business rules, and patterns seen in the market, with public sources. The experiment has not been run; it shows how the hypothesis would be validated.

## Notes

- Independent concept, not affiliated with any company mentioned in the notes.
- Prices are examples. The experiment is a proposal, not a result.
