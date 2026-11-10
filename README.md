# Rohan Khiani

I build AI for finance. Financial analysis and financing shouldn't depend on your income or who you know.

Junior at the North Carolina School of Science and Mathematics (Class of 2028) · founder of Novaris · sole author of a NeurIPS 2026 workshop paper.

## Now

**Novaris**: financial tools for small and mid-sized contractors that big firms already have: lien waivers subs sign on their phone, a payment link for each sub, and a 13-week cash forecast. Built on Next.js, Supabase, Plaid and Stripe; I direct the build and AI writes most of the code. Top 3 of 5 finalists at the NGEN RTP Student Entrepreneurship Conference.

**Research: *Blinding the AI Co-Scientist: Mechanical Pre-Commitment for AI-Assisted Empirical Research*** (sole author, NeurIPS 2026 Workshop on AI-Native Academia). The protocol locks an analysis plan before AI-assisted research ever sees real data, so the common forms of result-fishing become technically impossible. On my own event study of whether company news changes a stock's risk (7,760 U.S. companies, including 2,553 failed ones most studies leave out), it rejected my headline result, and I kept the rejection.

## Open-source fintech

Five public projects, each with a real engine, a live demo, a test suite and CI. Every README dates its measurements and names the test or command that reproduces each claim.

| Project | What it is | |
|---|---|---|
| **[CreditLens](https://github.com/ROROK20/CreditLens)** | Explainable credit scoring on synthetic data: Shapley attributions that sum to the served probability, and a fairness audit with confidence intervals that says INCONCLUSIVE when it should. | [demo](https://creditlens-delta.vercel.app) |
| **[AlphaForge](https://github.com/ROROK20/AlphaForge)** | Python backtester with ML signals that never score a bar they trained on, per-side costs, an optional next-bar fill, VaR/CVaR and Markowitz optimization. | [demo](https://alphaforge-two-beta.vercel.app) |
| **[PayKit](https://github.com/ROROK20/PayKit)** | Zero-runtime-dependency TypeScript payments SDK: idempotent charging, fail-closed HMAC webhooks, reconciliation, rule-based fraud scoring. | [demo](https://paykit-theta.vercel.app) |
| **[RiskCanvas](https://github.com/ROROK20/RiskCanvas)** | Portfolio risk: VaR, expected shortfall, three Monte Carlo engines and six equity-shock crisis scenarios calibrated to cited S&P 500 closes. | [demo](https://riskcanvas-roan.vercel.app) |
| **[FinSight](https://github.com/ROROK20/FinSight)** | SEC EDGAR 10-K financials to a cited DCF model value beside the price. No rating, no price target. | [demo](https://finsight-kappa-five.vercel.app) |

The hosted demos run without a backend and say so on screen; `docker compose up --build` in any repo runs the real engine. Data is synthetic or bundled, and none of it is financial advice.

## Other builds

- **[Two Letters](https://two-letters.vercel.app)** (Congressional App Challenge): a free site that tells Mecklenburg County homeowners whether a cash offer for their home is fair, using recorded sales of similar homes and county records on the buyer. 50 beta testers.
- **FinCAN**: a PyTorch model for predicting stock moves. 4th in Technology at the NC Region 6 Science & Engineering Fair (state qualifier).

## How I build

I run a two-seat AI workflow I designed: one Claude Code session writes the code, a second re-checks every claim against evidence before anything ships, and each defect it catches becomes a permanent test. That's why the numbers in these READMEs are dated and reproducible, and why the commits are co-authored with Claude. I've presented the workflow at an Anthropic-hosted event in Durham.

## Recognition

- Top 3 of 5 finalists, NGEN RTP Student Entrepreneurship Conference (2026), with Novaris
- Invited attendee, Y Combinator × Duke, the youngest there
- Stanford AI4ALL (16% acceptance), team lead on NLP models for disaster response
- 1st place, a high-school hackathon
- Reviewer, NeurIPS 2026 workshop
- Technology Sector Lead, a ~$170K student-run investment fund (+11.8% while I led it)
- Eagle Scout

## Stack

Python (PyTorch, scikit-learn, pandas, NumPy/SciPy, FastAPI) · TypeScript (Next.js, React, Node) · SQL / Postgres · Stripe, Plaid · causal inference

## Contact

[rskv.khiani@gmail.com](mailto:rskv.khiani@gmail.com) · [rohankhiani.vercel.app](https://rohankhiani.vercel.app) · [LinkedIn](https://www.linkedin.com/in/rohan-khiani-b14147300/)

I'd love to talk with anyone working on AI, finance or both, especially about research mentorship and internships.
