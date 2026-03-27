# Financial Statement Analysis (肖星·一本书读懂财报)

A Claude skill that applies Tsinghua Professor Xiao Xing's integrated three-statement framework to analyze company financials. Designed for investors, managers, and MBA students who want to read balance sheets, income statements, and cash flow statements the way a seasoned analyst would — and identify whether a company truly creates value using the ROIC vs. WACC test.

## What It Does

- **Three-statement analysis**: Reads balance sheet structure, income waterfall, and cash flow archetypes together as one system
- **ROIC vs. WACC verdict**: Tests whether a company genuinely creates shareholder value — not just reports profit
- **Ratio toolkit**: Profitability, efficiency, liquidity, and solvency ratios benchmarked against industry norms
- **Risk detection**: Flags hidden liabilities, earnings quality issues, and cash flow manipulation patterns
- **Industry context**: Interprets every number relative to industry structure and strategic positioning

## When to Use It

Trigger this skill when you ask:
- "Analyze this company's financials"
- "Is this a good company / worth investing in?"
- "Read this balance sheet" / "What does this income statement tell me?"
- "ROIC vs WACC" / "Is this company profitable?"
- "Compare these two companies' financial statements"
- "What does this accounting item mean?"
- "Cash flow health check"

## Installation

```bash
npx skills add simbajigege/book2skills/skills/financial-statements-analysis-xiao-xing
```

1. Download or clone this folder.
2. In Claude.ai, go to **Settings → Skills** and upload the skill folder.
3. The skill will appear in your available skills list.

## File Structure

```
financial-statements-analysis-xiao-xing/
├── SKILL.md          # Main skill instructions
├── README.md         # This file
└── LICENSE.txt       # Usage license
```

## License

Skill distillation for personal/educational use. Do not reproduce source passages verbatim.
