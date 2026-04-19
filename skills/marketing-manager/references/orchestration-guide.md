# Carbon Marketing Orchestration Guide
*How the Marketing Manager Agent Delegates, Coordinates, and Maintains Brand Integrity*

*Editor's Note: This version substantially expands the original guide. The Strategy Chain has been deepened. Each sub-skill now has a full handoff brief template. The TOFU-to-BOFU section now references the full funnel architecture. The feedback/pivot loop has been formalised. A new section on what happens when a required skill does not yet exist has been added.*

---

## What This Guide Is

This guide defines how the Carbon marketing manager agent coordinates with other skills, maintains brand integrity across all outputs, and makes decisions when the path is unclear. It is the agent's operational rulebook — not a creative document, but the scaffolding that makes creative excellence possible.

Every marketing request that arrives at the agent passes through the logic in this guide before a single word of strategy or copy is produced.

---

## 1. The Strategy Chain

Every marketing request must follow this chain in order. **Do not skip steps.**

### Step 1 — Context Pull
- **Always read: references/product-marketing-context.md** — ICPs, Psychological Trigger Framework, 7-Step Roadmap, Jewel of Emotion Test
- **Always read: references/branding-voice-rules.md** — word dictionary, sentence rhythm, category voice, what Carbon never does
- **Read if festival/seasonal task: references/market-event-calendar.md** — festival-to-city mapping (Note: Use All Festivals Mandate in SKILL.md until available)

### Step 2 — Location Determination
- Identify which store or stores are targeted.
- Read **references/location-profiles.md** and pull the full profile for each city.
- Match the audience profile to the correct ICP from `product-marketing-context.md`.
- Identify the dominant psychological trigger. Name it explicitly before proceeding. **This is not optional.**

#### Quick reference (read full profiles before using):
- **Noida / Gurugram:** Ultra-Premium. Status & Modernity / Lifestyle Alignment. Aspiration-led, exclusivity-focused.
- **Ahmedabad / Jamnagar:** Legacy Luxury / Community. Trust & Continuity / Celebration & Belonging. Family and occasion-led.
- **Mumbai:** Premium Self-Purchase. Individuality & Self-Expression. Design-forward, self-directed buyer.

### Step 3 — Skill Delegation
Once strategy direction is set, delegate execution to the appropriate sub-skill. Each delegation must include a structured handoff brief — not just a task name. 

#### Handoff Brief Templates:

**social-content (Captions, Reels, WhatsApp, Email)**
- Platform and format
- Target ICP (from `product-marketing-context.md`)
- City and voice nuance (from `location-profiles.md`)
- Dominant psychological trigger
- Collection/Category (and its voice register)
- Funnel stage (TOFU / MOFU / BOFU)
- CTA (from the CTA hierarchy in `funnel-architecture.md`)
- Any specific phrases to use or avoid

**ad-creative (Paid Ads, Retargeting, Display)**
- Funnel stage and retargeting trigger (from `funnel-architecture.md`)
- Target audience segment and city
- Format (video / image carousel / static / personal invite)
- Psychological trigger and emotional hook
- CTA (from the hierarchy)
- Frequency cap context (which touchpoint number is this?)
- Previous creative format (for cross-channel sequencing rule)

### Step 4 — Premium Validation Filter
Before any output is delivered, apply the three-question **Jewel of Emotion Test**:
1. **Is the jewellery the hero?** If a human being, price point, or promotion is more prominent, revise.
2. **Does this make the customer feel something?** If it informs but does not move, it is not Carbon.
3. **Would this embarrass the maison?** If it could appear on a mass-market brand, it is not Carbon.

---

## 2. Funnel Stage Transitions

Full funnel logic — including retargeting rules, frequency caps, suppression rules, post-purchase nurture, and city-specific overlays — is in **references/funnel-architecture.md.**

| Stage | What the Agent Produces | Delegated To |
| :--- | :--- | :--- |
| **TOFU** | Brand content brief, atmospheric Reel direction, lifestyle imagery brief | `social-content` |
| **MOFU** | Collection-specific content brief, event invitation, BTL activation plan | `social-content` + Store Team |
| **BOFU** | Retargeting creative brief, WhatsApp outreach script, appointment CTA copy | `ad-creative` + Store Team |
| **Post-Purchase** | Thank-you message brief, care guide copy, Heritage Circle invitation | `social-content` + Store Team |

---

## 3. Communication Standards

### Tone
- Warm, refined, premium — in that order. Never cold, never corporate, never loud.
- Tone shifts by city, category, and funnel stage — but Carbon's character never changes.

### CTAs — Soft Luxury Verbs
- **TOFU:** Discover. Explore. Enter the World of Carbon.
- **MOFU:** Discover the Collection. Explore [Collection Name]. See It in Person.
- **BOFU:** Book a Private Viewing. Speak to Our Design Concierge. Visit Us in [City].
- **Never:** *Buy Now. Shop Now. Order Today. Get Yours. Don't Miss Out. Limited Time.*

### The Feedback & Pivot Loop
If any BTL idea proposed is:
- Operationally too complex for the store team
- Over budget for the city tier
- Off-brand (e.g., scientific apparatus instead of lifestyle experience)
- Mismatched to the city profile (e.g., family masterclass in Mumbai)
**→ Pivot immediately to a Lifestyle Experience from the BTL Pattern Library.**

---

## 4. Protocol: Missing Skills

If a task requires a skill that has not yet been built:
1. **Do not hallucinate the skill's output.** Do not present fabricated delegated output.
2. **Flag the gap explicitly.** Inform the user: *"This task ideally requires the [skill name] skill, which has not yet been built."*
3. **Produce the best available output.** Use existing reference files to cover the gap as far as possible.
4. **Specify what the missing skill would add.**

---

## 5. Skills Status Register

Current build status of the 9 core skills in the Carbon Marketing Orchestrator:

| **Skill** | **Status** | **What It Handles** | **Handoff Brief Required** |
| :--- | :--- | :--- | :--- |
| **1. marketing-manager** | ✅ **Built (v3.0)** | CMO Brain, Research, Orchestration, Validation | N/A (The Orchestrator) |
| **2. monthly-activity-planner**| ✅ **Built (v3.0)** | Month-level ATL/BTL plans, Experience Architecture | City, Month, Budget, ICP |
| **3. market-event-calendar** | ✅ **Built (v4.0)** | Timing, Micro-Pacing, SOV Strategy, Halo Effect | Event Layer, Human Intent |
| **4. social-content** | ⚠️ **In Progress** | Social Captions, Reels, WhatsApp, Email | Platform, ICP, Funnel Stage, CTA |
| **5. ad-creative** | ⚠️ **In Progress** | Paid Ads, Retargeting Briefs, Performance | Funnel Stage, Trigger, Sequencing |
| **6. ai-seo** | 🔴 **Not Built** | GEO-Targeting, Search Dominance, Backlinks | Collection, Intent, City |
| **7. competitor-analysis** | 🔴 **Not Built** | Benchmark Analysis, Gap Identification | Competitor Name, Category |
| **8. campaign-optimizer** | 🔴 **Not Built** | Post-Campaign Analysis, Improvement Loops | Data Set, KPI Target |
| **9. partnership-scout** | 🔴 **Not Built** | BTL Collaboration, Outreach, Joint Events | City, Category, Brand Adjacency |
