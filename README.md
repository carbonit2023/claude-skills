# Carbon AI Marketing Orchestrator

A collection of elite AI agent skills focused on luxury marketing orchestration. Built for the Carbon ecosystem to help with market reconnaissance, conversion optimization, geo-intent discovery, and high-end BTL partnerships. Works with Claude Code, Cursor, Windsurf, and any agent that supports the [Agent Skills spec](https://agentskills.io).

Built for [Carbon](https://github.com/carbonit2023). This repository is a specialized fork of the original Marketing Skills by Corey Haines, transformed into a 9-core luxury orchestration system.

**Contributions welcome!** Found a way to improve a skill or have a new one to add? [Open a PR](#contributing).

Run into a problem or have a question? [Open an issue](https://github.com/carbonit2023/claude-skills/issues) — we're happy to help.

## What are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, your agent can recognize when you're working on a luxury marketing task and apply the right frameworks and brand DNA.

## How Carbon AI Skills Work Together

The Carbon AI Marketing Orchestrator uses a 9-core architecture of elite, luxury-aligned skills that cross-reference each other to maintain brand integrity and execute geo-fenced growth.

```
                           ┌──────────────────────────────────────────┐
                           │       product-marketing-context          │
                           │    (Read by all elite Carbon skills)     │
                           └──────────────┬───────────┬───────────────┘
                                          │           │
                   ┌──────────────────────┴───────────┴─────────────────────┐
                   │                                                        │
         ┌─────────▼──────────┐                                   ┌─────────▼──────────┐
         │ marketing-manager  │◄──────────────────────────────────┤ market-event-cal   │
         │ (Master Orchestrator)                                  │ (Timing & Intent)  │
         └─────────┬──────────┘                                   └─────────┬──────────┘
                   │                                                        │
    ┌──────────────┼──────────────┬──────────────┬──────────────┬───────────┼──────────────┐
    ▼              ▼              ▼              ▼              ▼           ▼              ▼
┌────────────┐ ┌────────────┐ ┌────────────┐ ┌────────────┐ ┌─────────┐ ┌──────────┐ ┌────────────┐
│ Intelligence│ │ Discovery  │ │ Conversion │ │ Communication││ Planning│ │ Analysis │ │ Partnership│
├────────────┤ ├────────────┤ ├────────────┤ ├────────────┤ ├─────────┤ ├──────────┤ ├────────────┤
│competitor- │ │ ai-seo     │ │ ad-creative│ │ social-    │ │ activity│ │ campaign-│ │ partnership│
│ analysis   │ │            │ │            │ │ content    │ │ planner │ │ optimizer│ │ scout      │
└────────────┘ └────────────┘ └────────────┘ └────────────┘ └─────────┘ └──────────┘ └────────────┘
```

See each luxury skill's **Orchestration Guide** for the full 9-core dependency map.

## Available Skills

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [ab-test-setup](skills/ab-test-setup/) | Plan, design, or implement an A/B test or experiment. |
| [ad-creative](skills/ad-creative/) | **(Elite Core)** Performance Marketing Architect. Designs luxury conversion funnels and retargeting logic. |
| [ai-seo](skills/ai-seo/) | **(Elite Core)** Geo-Intent Discovery Engine. captures high-value local search intent (AEO, GEO, LLMO). |
| [analytics-tracking](skills/analytics-tracking/) | Set up, improve, or audit analytics tracking and measurement. |
| [aso-audit](skills/aso-audit/) | Audit or optimize an App Store or Google Play listing. |
| [campaign-optimizer](skills/campaign-optimizer/) | **(Elite Core)** Performance Intelligence Engine. Audits data and diagnoses funnel breakages. |
| [churn-prevention](skills/churn-prevention/) | Reduce churn, build cancellation flows, and recover failed payments. |
| [cold-email](skills/cold-email/) | Write B2B cold emails and follow-up sequences that get replies. |
| [community-marketing](skills/community-marketing/) | Build and leverage online communities to drive product growth. |
| [competitor-analysis](skills/competitor-analysis/) | **(Elite Core)** Live Intelligence Engine. Identifies the Luxury Gap and executes SOV Fatigue Strikes. |
| [content-strategy](skills/content-strategy/) | Plan a content strategy, editorial calendar, or content pillars. |
| [copy-editing](skills/copy-editing/) | Edit, review, or improve existing marketing copy for tone and rhythm. |
| [copywriting](skills/copywriting/) | Write, rewrite, or improve marketing copy for any page or long-form asset. |
| [customer-research](skills/customer-research/) | Conduct, analyze, or synthesize customer research and personas. |
| [email-sequence](skills/email-sequence/) | Create or optimize email sequences and lifecycle marketing flows. |
| [form-cro](skills/form-cro/) | Optimize lead capture forms, contact forms, and surveys. |
| [free-tool-strategy](skills/free-tool-strategy/) | Plan or build free tools (calculators, etc.) for marketing purposes. |
| [launch-strategy](skills/launch-strategy/) | Plan a product launch, feature announcement, or GTM strategy. |
| [lead-magnets](skills/lead-magnets/) | Create or optimize lead magnets for email capture. |
| [market-event-calendar](skills/market-event-calendar/) | **(Elite Core)** Timing and Intent Engine. Maps Indian cultural moments to CM-level strategy. |
| [marketing-ideas](skills/marketing-ideas/) | 140 SaaS marketing ideas and high-level growth triggers. |
| [marketing-manager](skills/marketing-manager/) | **(Elite Core)** Master Orchestrator & CMO. Acts as the final decision-maker and quality controller (v4.0). |
| [marketing-psychology](skills/marketing-psychology/) | Apply psychological principles and mental models to marketing. |
| [monthly-activity-planner](skills/monthly-activity-planner/) | **(Elite Core)** Experience Architect. Generates practical BTL/ATL/TTL activity plans. |
| [onboarding-cro](skills/onboarding-cro/) | Optimize post-signup onboarding and user activation. |
| [page-cro](skills/page-cro/) | Optimize, improve, or increase conversions on any marketing page. |
| [paid-ads](skills/paid-ads/) | Help with technical setup for Google, Meta, LinkedIn campaigns. |
| [partnership-scout](skills/partnership-scout/) | **(Elite Core)** Offline Dominance Engine. Architects elite BTL brand collaborations. |
| [paywall-upgrade-cro](skills/paywall-upgrade-cro/) | Create or optimize in-app paywalls and upgrade screens. |
| [popup-cro](skills/popup-cro/) | Create or optimize popups, modals, and overlays. |
| [pricing-strategy](skills/pricing-strategy/) | Help with pricing decisions, packaging, or monetization strategy. |
| [product-marketing-context](skills/product-marketing-context/) | The foundation for all skills — contains ICP, positioning, and messaging. |
| [programmatic-seo](skills/programmatic-seo/) | Create SEO-driven pages at scale using templates and data. |
| [referral-program](skills/referral-program/) | Create, optimize, or analyze referral and affiliate programs. |
| [revops](skills/revops/) | Help with revenue operations and lead lifecycle management. |
| [sales-enablement](skills/sales-enablement/) | Create sales collateral, pitch decks, and objection docs. |
| [schema-markup](skills/schema-markup/) | Add or optimize schema markup and structured data. |
| [seo-audit](skills/seo-audit/) | Audit, review, or diagnose SEO issues on your site. |
| [signup-flow-cro](skills/signup-flow-cro/) | Optimize signup, registration, and account creation flows. |
| [site-architecture](skills/site-architecture/) | Plan or restructure website page hierarchy and navigation. |
| [social-content](skills/social-content/) | **(Elite Core)** Luxury Content Engine. Generates Reels, Captions, and WhatsApp broadcasts. |
<!-- SKILLS:START -->

## Installation

### Option 1: CLI Install (Recommended)

Use [npx skills](https://github.com/vercel-labs/skills) to install skills directly:

```bash
# Install all skills
npx skills add carbonit2023/claude-skills

# Install specific skills
npx skills add carbonit2023/claude-skills --skill social-content ad-creative
```

This automatically installs to your `.agents/skills/` directory (and symlinks into `.claude/skills/` for Claude Code compatibility).

### Option 2: Claude Code Plugin

Install via Claude Code's built-in plugin system:

```bash
# Add the marketplace
/plugin marketplace add carbonit2023/claude-skills

# Install all Carbon marketing skills
/plugin install carbon-skills
```

### Option 3: Clone and Copy

Clone the entire repo and copy the skills folder:

```bash
git clone https://github.com/carbonit2023/claude-skills.git
cp -r claude-skills/skills/* .agents/skills/
```

### Option 4: Git Submodule

Add as a submodule for easy updates:

```bash
git submodule add https://github.com/carbonit2023/claude-skills.git .agents/carbon-skills
```

Then reference skills from `.agents/carbon-skills/skills/`.

### Option 5: Fork and Customize

1. Fork this repository
2. Customize skills for your specific needs
3. Clone your fork into your projects

### Option 6: SkillKit (Multi-Agent)

Use [SkillKit](https://github.com/rohitg00/skillkit) to install skills across multiple AI agents (Claude Code, Cursor, Copilot, etc.):

```bash
# Install all skills
npx skillkit install carbonit2023/claude-skills

# Install specific skills
npx skillkit install carbonit2023/claude-skills --skill social-content ad-creative
```

## Upgrading from v1.0

Skills now use `.agents/` instead of `.claude/` for the product marketing context file. Move your existing context file:

```bash
mkdir -p .agents
mv .claude/product-marketing-context.md .agents/product-marketing-context.md
```

## Usage

Once installed, just ask your agent to help with luxury marketing tasks:

```
"Launch a counter-strategy for the upcoming festive season in Ahmedabad"
→ Uses marketing-manager orchestrator

"Design a 4-stage ad funnel for our new collection"
→ Uses ad-creative skill

"Find elite BTL partners in Gurugram"
→ Uses partnership-scout skill
```

## Contributing

Found a way to improve a skill? Have a new skill to suggest? PRs and issues welcome!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding or improving skills.

## License

[MIT](LICENSE) - Use these however you want.
