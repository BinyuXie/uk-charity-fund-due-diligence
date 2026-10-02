# UK Charity Multi-Asset Fund Due Diligence & Manager Selection

## Role played

Act as an analyst preparing a **preliminary, desk-based manager shortlist** for the investment committee of a hypothetical UK education charity. The exercise does not claim a real client mandate, manager interviews, operational due diligence, regulated advice or a recommendation to transact.

## Fictional client

**Northbridge Education Charity** is a fictional case created for this project.

- Long-term investment pool: £10 million
- Separate liquidity reserve: £450,000, equal to 18 months of planned spending
- Annual spending: £300,000, or 3% of the long-term pool
- Investment horizon: more than 10 years
- Discussion objective: UK CPI + 3% a year after fund costs over rolling five-year periods
- Risk governance: a fall near 15% triggers trustee review; it is not a guaranteed loss limit or an automatic sale rule
- Liquidity: daily or weekly dealing, with the reserve held outside the selected fund
- Mission review: trustees require explicit look-through assessment of tobacco, controversial weapons and investments that could conflict with the education mission

CPI + 3% net is internally consistent with a 3% spending rule if achieved because it would approximately preserve real capital before other cash flows. It is an objective, not a forecast. The reserve supports near-term spending while markets recover; it does not protect the invested pool from loss.

## Research question

Which reviewed UK charity multi-asset fund is the strongest candidate for further due diligence when return objective, downside risk, implementation cost, mission alignment and governance are considered together? What evidence is still missing before trustees could make a real appointment?

## Candidate scope

The completed case study compares three charity-specific vehicles using exact GBP accumulation share classes:

| Short name | Fund and share class | ISIN |
|---|---|---|
| Cazenove | SUTL Cazenove Charity Multi-Asset Fund, Class Z Accumulation GBP | GB00BF783Y68 |
| Sarasin | Sarasin Endowments Fund, A Accumulation GBP | GB00BYZJN999 |
| M&G | M&G Charity Multi Asset Fund, Sterling Class Accumulation | GB00BK1KFR05 |

The screen required charity eligibility, a documented GBP accumulation share class, daily dealing, at least five years of published history and current official information on objectives, costs and implementation. The three-fund set is deliberately manageable and is not a complete market universe. The conclusion is therefore the best **within the reviewed set**, not the best fund available in the UK.

## Decision process

### Stage 1: pass, review and evidence-gap screen

- Eligible UK charity investor
- Exact GBP accumulation share class
- Daily dealing and workable settlement
- At least five years of published live share-class history
- Objective that could plausibly support spending and real value
- Mission approach sufficiently explicit for trustee review
- Public evidence sufficient for final appointment

### Stage 2: evidence-anchored scorecard

Each fund receives a whole-number score from 1 to 5. A score records the strength of evidence against this fictional mandate; it is not a forecast of returns or proof of manager skill.

| Dimension | Base weight |
|---|---:|
| Client objective fit | 25% |
| Risk and downside evidence | 25% |
| Diversification and process | 15% |
| Fees and implementation | 15% |
| Mission and stewardship | 15% |
| Governance and reporting | 5% |

The model also recalculates under preservation-first, cost-first and mission-first priorities. This tests whether the recommendation depends on trustee preferences rather than pretending the weights are objective facts. The cost-first case is deliberately an extreme stress test with 45% assigned to fees, not a proposed default policy.

## Evidence boundary

The analysis uses 17 official sources: Charity Commission guidance plus fund factsheets, KIID documents, prospectuses, annual reports, cost disclosures, sustainability materials and official product pages. Data dates and definitions are retained because they are not fully uniform.

The public documents do **not** provide a consistent monthly return series for all exact share classes. The project therefore does not estimate comparable volatility, maximum drawdown, recovery time or manager alpha. Published target-horizon returns and limited stress-period figures are treated as evidence for questions, not as a performance league table. Cazenove's manager-disclosed ten-year target series also transitions from RPI to CPI in June 2018 and includes predecessor history, so it is not presented as a homogeneous CPI+4 record. The missing risk series, full look-through costs and operational evidence remain conditions for the next due-diligence stage.

## Decision rule and completed outcome

- Do not appoint any manager from public documents alone.
- Start the next-stage manager discussion with Cazenove as the balanced candidate.
- Retain Sarasin as the mission-led alternative and M&G as the cost-led comparator.
- Do not recommend a two-manager split until comparable risk data show genuinely complementary return drivers; ranking sensitivity alone is not enough to justify added fees and governance.

Under the base weights, Cazenove scores 70, while M&G and Sarasin each score 63. Cazenove remains first under the preservation-first case, M&G leads the deliberately extreme cost-first case and Sarasin leads the mission-first case. The change in leader is a decision finding, not a flaw to hide.

## Outputs

- `output/UK_Charity_Fund_Selection.xlsx`: mandate, suitability screen, fund evidence, scorecard, sensitivity analysis, manager questions, monitoring triggers and source register
- `data/fund_evidence.json`: structured evidence, scoring assumptions and source links
- `INVESTMENT_MEMO.md`: committee recommendation and conditions before appointment
- `INTERVIEW_GUIDE.md`: concise explanation, challenges, limitations and defensible CV wording
- `README.md`: public project overview and review instructions
