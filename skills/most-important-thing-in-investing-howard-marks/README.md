# Howard Marks — The Most Important Thing

A Claude skill that applies Howard Marks's investment philosophy — distilled from *The Most Important Thing Illuminated* — to evaluate stocks, assess risk, and guide buy/sell timing decisions. Designed for individual investors and analysts who want a structured, second-level thinking framework rather than surface-level stock tips.

## What It Does

- **Stock evaluation**: Runs a 7-step analysis covering second-level thinking, intrinsic value, price vs. value, risk, market cycle position, contrarian signals, and a conditional verdict.
- **Due diligence guidance**: Provides a structured checklist across business fundamentals, competitive moat, management quality, valuation, and sentiment for any company.
- **Buy/sell timing**: Applies green/yellow/red light frameworks to buying and selling decisions grounded in value and sentiment — not price momentum.
- **Market environment assessment**: Uses a full market thermometer (credit spreads, valuations, sentiment) to determine appropriate portfolio posture.

## When to Use It

This skill activates on questions like:

- "Is [Stock X] worth buying right now?"
- "Should I invest in [Company Y]?"
- "What should I research before investing in [Company Z]?"
- "When should I buy / sell [Stock X]?"
- "Is the market expensive right now?"
- "Is now a good time to invest?"
- "Assess the risk of [Asset]"
- "Analyze [Stock] using value investing principles"

It also activates when an investor appears to be exhibiting classic psychological traps (FOMO, recency bias, momentum chasing) — the skill will name the trap explicitly and reframe the question through Marks's lens.

## Installation

1. Download or clone this folder.
2. In Claude.ai, go to **Settings → Skills** and upload the skill folder.
3. The skill will appear in your available skills list.

## File Structure

```
howard-marks-most-important-thing/
├── SKILL.md                        # Main skill instructions and query routing
├── README.md                       # This file
├── LICENSE.txt                     # License and copyright notice
└── references/
    ├── dimensions.md               # Full detail on all 11 investment dimensions
    ├── query-playbook.md           # Step-by-step response templates for each query type
    └── reminders.md                # 10 non-negotiable principles + classic mistake patterns
```

## Source

This skill distills analytical frameworks from:

> Howard Marks, *The Most Important Thing Illuminated* (Columbia University Press, 2013), with commentary by Christopher C. Davis, Joel Greenblatt, Paul Johnson, and Seth A. Klarman.

## License

This skill is a distillation of investment frameworks for personal and educational use. It does not reproduce book passages verbatim. See `LICENSE.txt` for full terms.
