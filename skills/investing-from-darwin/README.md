# Investing From Darwin

A Claude skill that applies Darwinian evolutionary principles to long-term stock investing. Based on Pulak Prasad's *What I Learned About Investing from Darwin* (2023), this skill encodes the investment framework of Nalanda Capital — a fund managing $5B+ in Indian equities with 20%+ annualized returns since 2007.

## What It Does

- **Rejects dangerous companies** using a Type I error checklist (governance failures, high leverage, turnarounds, fast-changing industries)
- **Screens for quality** using historical Return on Capital Employed (ROCE) as a single cascading filter
- **Assesses robustness** across 7 dimensions to identify businesses that can survive shocks and evolve
- **Classifies signals** as honest (costly to fake) or dishonest (cheap to produce) — so you weigh the right evidence
- **Guides buy/hold/sell decisions** using the GKPI framework (Good Karma, Patience, Inertia) — buy rarely, hold forever, sell only for fundamental deterioration

## When to Use It

Trigger phrases that activate this skill:
- "Evaluate this stock Darwin-style"
- "Should I buy or avoid this company?"
- "Assess the business quality of [company]"
- "Is this a good long-term investment?"
- "Analyze the robustness of this business"
- "Is this an honest or dishonest signal about [company]?"
- "Should I sell [company]?"

## Installation

```bash
npx skills add simbajigege/book2skills/skills/investing-from-darwin
```

1. Download or clone this folder.
2. In Claude.ai, go to **Settings → Skills** and upload the skill folder.
3. The skill will appear in your available skills list.

## File Structure

```
investing-from-darwin/
├── SKILL.md          # Main skill instructions
├── README.md         # This file
└── LICENSE.txt       # License information
```

## License

Skill distillation for personal/educational use. Do not reproduce source passages verbatim.
