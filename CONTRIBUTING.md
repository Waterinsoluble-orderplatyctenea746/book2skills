# Contributing Guide

Thank you for your interest in contributing to book2skills!

---

## Process for Contributing a New Skill

### Step 1: Choose a Book

Good Skill candidates should meet these criteria:
- **Highly practical** — The book contains specific frameworks, criteria, and decision processes, not just pure theory
- **Time-tested** — Classic works preferred, published at least 5 years ago
- **Actionable** — The book's methodology can be distilled into executable steps for an agent

Before you start, please [submit an Issue](../../issues/new?template=book-request.md) to confirm the book hasn't already been claimed.

### Step 2: Read the Original Book

**You must read the complete original work.** Skills based on summaries or secondhand materials will not be accepted.

While reading, focus on extracting:
- Core frameworks and evaluation criteria
- Decision processes and judgment rules
- What the author explicitly advises against ("what not to do" is often as important as "what to do")
- Specific actionable steps

### Step 3: Create the Skill Folder

```
skills/your-skill-name/
├── SKILL.md              # Required
└── references/           # Recommended, for detailed content
    ├── framework.md
    └── ...
```

**SKILL.md format requirements:**

```yaml
---
name: your-skill-name         # lowercase letters, numbers, hyphens, max 64 characters
description: >                # use folded block syntax to avoid quote issues
  Describe what this Skill does and when to trigger it.
  Include example trigger phrases. Be somewhat "proactive" so
  the agent knows to invoke it when encountering related problems.
---

# Skill Title

(body content)
```

**YAML notes:**
- Do not use double quotes `"` or single quotes `'` directly in description
- Recommended: use `>` folded block syntax for multi-line descriptions
- `name` cannot contain "anthropic" or "claude"

### Step 4: Test

Before submitting a PR, test your Skill in Claude.ai or Claude Code:
- After installing, verify that trigger phrases correctly invoke the Skill
- Test output quality on 2–3 real questions
- Include at least one screenshot of a test case in your PR

### Step 5: Submit a PR

PR title format: `Add skill: [Book Title] — [Author Name]`

PR description should include:
- Basic book information (title, author, publication year)
- What types of questions the Skill can answer (3 example questions)
- Whether you have read the complete original work (yes/no)

---

## Skill Quality Standards

| Standard | Description |
|----------|-------------|
| Faithful to source | Content can be traced to specific chapters; no views added that don't appear in the book |
| Actionable | Users receive specific judgments or recommendations, not vague generalities |
| Clear structure | Uses headings, tables, and lists to organize content for easy agent navigation |
| Valid YAML | `name` and `description` fields are correctly formatted and parseable |
| Reasonable size | SKILL.md kept under 500 lines; detailed content goes in references/ |

---

## File Naming Conventions

- Skill folder name: `kebab-case`, recommended format: `{topic}-{book-keyword}`, e.g. `fisher-investing`, `collins-good-to-great`
- Files in references/: descriptive names, e.g. `framework.md`, `evaluation-criteria.md`, `common-mistakes.md`

---

## Questions?

Feel free to ask in [Discussions](../../discussions), or leave a comment directly on the relevant Issue.
