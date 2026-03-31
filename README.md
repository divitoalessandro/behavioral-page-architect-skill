# Behavioral Page Architect

A skill for Claude that designs behaviorally optimized product and service detail pages using a research-backed dramaturgical framework.

## What it does

This skill produces a section-by-section page blueprint that guides users through a product or service page — answering their implicit mental questions at each stage and applying evidence-based behavioral design patterns to reduce friction and support good decisions.

The framework uses a universal 5-section dramaturgy:

1. **Arriving** — Quick orientation, confirming the user is in the right place
2. **Understanding** — Delivering relevant context, keeping engagement high
3. **Choosing** — Making the offering tangible with options, pricing, and CTAs
4. **Deep Diving** — Covering details and special cases for undecided users
5. **Closing** — Offering further paths, alternatives, and contact options

Each section includes implicit user questions, behavioral pattern recommendations (with academic citations), content briefs, and component suggestions.

## Key features

- **Context intake** — Asks about product/service, industry, conversion goal, audience, and brand maturity before producing a blueprint
- **40+ research-verified behavioral patterns** — Every pattern is traceable to published research (Kahneman, Cialdini, Tversky, Ariely, Bandura, etc.)
- **Evidence tier system** — Patterns are transparently categorized as Tier 1 (peer-reviewed), Tier 2 (practitioner-validated), or Tier 3 (popular-science origin)
- **Content briefs per section** — Actionable enough for copywriters to start writing
- **Frontend handoff** — Triggers the frontend-design skill for component-level implementation

## Installation

### Claude.ai
1. Download or clone this repository
2. Zip the `behavioral-page-architect/` folder
3. Go to **Settings > Capabilities > Skills**
4. Click **Upload skill** and select the zip

### Claude Code
Place the `behavioral-page-architect/` folder in your skills directory.

## Usage

Ask Claude something like:

- *"Help me design a product page for our SaaS project management tool"*
- *"I need a behaviorally optimized landing page for an insurance product"*
- *"Structure a service detail page for a B2B consulting offering"*
- *"Create a CRO-optimized page blueprint for our e-commerce product"*

Claude will ask a few context questions, then produce a full blueprint with behavioral annotations.

## Repository structure

```
behavioral-page-architect/    # The skill folder (upload this)
├── SKILL.md                  # Skill instructions
README.md                     # This file (repo-level, not part of the skill)
LICENSE                        # MIT License
```

## Author

**Alessandro Di Vito** — Digital Consultant & UX/CX Expert specializing in behavioral design, conversion optimization, and AI-integrated digital strategy.

## License

MIT
