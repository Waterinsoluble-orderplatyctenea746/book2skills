---
name: howard-marks-most-important-thing
description: |
  Apply Howard Marks's investment philosophy to evaluate stocks, assess risk,
  and identify buy/sell timing. Use when asked about stock valuation, investment
  research, market risk, portfolio positioning, or any question where an investor
  needs a framework — e.g. "Is NVIDIA worth buying?", "What should I research
  before investing in X?", "Is now a good time to invest?"
  Trigger phrases: "is X worth buying", "should I invest in", "analyze this stock",
  "assess the risk of", "is the market expensive", "when should I buy/sell",
  "what should I research before investing", "is now a good time to invest".
compatibility: claude.ai, Claude Code, API with code execution
license: |
  Skill distillation for personal and educational use only.
  This skill summarizes analytical frameworks from "The Most Important Thing Illuminated"
  (Columbia University Press, 2013) by Howard Marks. It does not reproduce book passages
  verbatim. Do not use for commercial redistribution. All intellectual property belongs
  to the respective authors and publisher.
---

# Howard Marks — The Most Important Thing

Source: *The Most Important Thing Illuminated* (Columbia University Press, 2013),
annotated by Christopher C. Davis, Joel Greenblatt, Paul Johnson, and Seth A. Klarman.

**Core principle:** Successful investing requires simultaneous attention to all
dimensions below. Never apply just one lens. For full detail on any dimension,
read `references/dimensions.md`. For query-type response templates, read
`references/query-playbook.md`. For condensed decision rules, read
`references/reminders.md`.

---

## The 11 Dimensions (summary — load references/dimensions.md for full detail)

| # | Dimension | One-line rule |
|---|-----------|---------------|
| 1 | **Second-level thinking** | Your view must differ from consensus AND be more correct. |
| 2 | **Intrinsic value** | Estimate what the business is worth before touching price. |
| 3 | **Price vs. value** | No asset is good or bad regardless of price. Buy things well, not good things. |
| 4 | **Risk** | Risk = probability of permanent loss, not volatility. |
| 5 | **Market cycles** | Everything is cyclical. "This time it's different" are the most dangerous words. |
| 6 | **The pendulum** | Sentiment swings between euphoria and despair — exploit the extremes. |
| 7 | **Psychology** | Biggest errors come from greed, fear, FOMO, herding — not bad analysis. |
| 8 | **Contrarianism** | Best opportunities are found among things most others won't do. |
| 9 | **Finding bargains** | Perception must be far worse than reality for a true bargain to exist. |
| 10 | **Patient opportunism** | If nothing offers adequate margin of safety, cash is a valid position. |
| 11 | **Defensive investing** | First goal: don't lose. Asymmetry (more upside than downside) is the target. |

---

## How to respond to investor queries

### Query type 1 — "Is [Stock X] worth investing in now?"

Run all 7 steps. Read `references/query-playbook.md` → Query Type 1 for full detail.

1. **Second-level check** — What does consensus assume? How does the price reflect that?
2. **Intrinsic value** — Estimate value range (P/FCF, EV/EBITDA, DCF). What does price imply?
3. **Price vs. value** — Cheap / fair / expensive? What is the margin of safety?
4. **Risk** — Business risk, valuation risk, leverage risk, macro risk. What causes permanent loss?
5. **Cycle & sentiment** — Fearful, neutral, or euphoric? Where is the pendulum?
6. **Contrarian test** — Universally loved → caution. Widely hated → look closer.
7. **Verdict** — Always conditional: "At price X, given assumptions Y, risk-reward appears Z."

### Query type 2 — "What should I research before investing in [Company X]?"

Six areas: (1) business model & moat, (2) free cash flow & balance sheet,
(3) management & capital allocation, (4) valuation (absolute + relative + implied growth),
(5) sentiment & ownership structure, (6) bear case — what has to be true for this to fail?

Read `references/dimensions.md` → Dimension 8 for the full due diligence checklist.

### Query type 3 — "When should I buy / sell [Stock X]?"

- **Buy:** Price meaningfully below value + fearful/indifferent sentiment + sound fundamentals.
- **Sell:** Price at or above value + euphoric sentiment, OR thesis is broken.
- **Wait:** Price is fair, margin of safety is thin, no clearly better alternative yet.

### Query type 4 — "Is now a good time to invest in general?"

Assess: credit availability, risk premiums, leverage in system, valuations, sentiment.
→ Cheap + fearful = aggressive. Fair + neutral = selective. Expensive + euphoric = defensive.

Read `references/query-playbook.md` → Query Type 4 for full market thermometer checklist.

---

## Output format

Structure every stock analysis as:

```
## [Stock]: Investment Assessment

### 1. Second-level thinking
### 2. Intrinsic value estimate
### 3. Price vs. value
### 4. Risk factors
### 5. Cycle / sentiment position
### 6. Contrarian signal
### 7. Verdict (conditional — never binary)
```

---

## Non-negotiable rules

- Never separate price from value.
- Always ask: what does everyone else think, and how does my view differ?
- Risk = permanent loss, not short-term volatility.
- Cycles always prevail — every trend eventually reverses.
- Margin of safety is not optional.

*Full principles in `references/reminders.md`.*
