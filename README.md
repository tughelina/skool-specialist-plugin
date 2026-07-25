# Skool Specialist — Claude Skill / Plugin

An expert assistant for building and marketing **Skool** communities: About pages that convert, Discovery ranking, Google SEO, the 11 Discovery keywords, community architecture, and challenge/workshop launches.

Works in **Claude.ai** (browser + desktop) and **Claude Code** — no coding required to use it.

---

## Install (for members / clients)

In Claude (Claude.ai or Claude Code), run:

```
/plugin marketplace add <YOUR-GITHUB-USERNAME>/skool-specialist-plugin
/plugin install skool-specialist@skool-specialist-marketplace
```

Then reload if prompted:

```
/reload-plugins
```

Now just ask Claude anything about your Skool community — e.g. *"Write my Skool About page for [audience]"* or *"Why isn't my group ranking in Discovery?"*

> Replace `<YOUR-GITHUB-USERNAME>` with the account that hosts this repository.

---

## What it does
- Writes/optimizes the **About page as a sales page** (Hook → Transformation → Proof → one CTA)
- **Discovery ranking** guidance (Growth · Engagement · Retention) — honestly separating official vs. practitioner knowledge
- **Google SEO** for public Skool pages (group name, keywords, backlinks, weekly posts)
- The **11 Discovery keywords** tailored to your audience
- Community architecture, pricing tiers, onboarding rituals, retention

## What's inside
```
skool-specialist-plugin/
├── .claude-plugin/
│   ├── plugin.json         # plugin manifest
│   └── marketplace.json    # marketplace listing
└── skills/
    └── skool-specialist/
        ├── SKILL.md        # the skill
        └── reference.md    # sourced research base
```

## Note
Skool changes frequently. The skill flags time-sensitive facts and verifies them via web search when it matters. Built-in knowledge is as of 2025/2026.

---
Built by Chantal Perrinjaquet · SoulStrategy.
