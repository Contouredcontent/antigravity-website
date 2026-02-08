# AI Workflow Plan for Email Marketing Agency

> **Created:** January 25, 2026  
> **Purpose:** Summary of our planning discussion for your AI tool stack and automation ideas.

---

## Your Questions Answered

### 1. Can I use any model with a skill?
**Yes.** Skills are just instruction files. They work with any model available in Antigravity (Claude Opus 4.5, Claude Sonnet, Gemini Pro, etc.). You can switch models anytime and the skill's context will still apply.

### 2. Will different models "get it" if I switch?
**Yes.** The skill file is loaded fresh each time you reference it. The model reads your full instructions before responding. Think of it like handing someone a detailed brief—whoever reads it will follow it.

### 3. How do I save/start chats in Antigravity?
- **Chats auto-save.** Every conversation is automatically saved.
- **Start a new chat:** Click the `+` button in the sidebar or use `Cmd/Ctrl + N`.
- **Switch between chats:** Use the sidebar to browse previous conversations.
- **Resume a chat:** Just click on it in the sidebar.

### 4. Is a very long skill file OK?
**Yes.** A long, detailed markdown file is ideal. The more specific your instructions, the better the output. I can handle skill files that are thousands of words long. Include all your prompts, best practices, and frameworks.

### 5. Would I just say the brand name and you do the rest?
**Yes.** Once the skill is set up, your workflow would be:
1. You: *"Using the email copywriting skill, write a welcome sequence for [Brand Name]."*
2. I browse their site, socials, and news.
3. I reference your economic research framework.
4. I output custom copy following your exact instructions.

### 6. Could Claude Code do a daily beauty magazine digest?
**Yes.** You'd build a script that:
1. Visits a list of beauty industry publications (e.g., Glossy, Beauty Independent, WWD Beauty).
2. Pulls headlines, key stats, and quotes.
3. Filters for relevance (economy, consumer behavior, pricing).
4. Outputs a `daily_digest_YYYY-MM-DD.md` file.

### 7. Would that be credit intensive?
**It depends on frequency and depth:**
| Frequency | Estimated Cost |
|---|---|
| Weekly digest (10 sources) | Low (~$1-3/week on Opus) |
| Daily digest (10 sources) | Moderate (~$5-15/week on Opus) |
| Daily + deep analysis | Higher (~$20-40/week) |

**Tip:** Use Sonnet for scraping/summarizing (cheaper), then Opus only for the final synthesis.

### 8. Better personalization angle?
You're right—generic personalization ("saw your golden retriever") is dead. Your angle is smarter:
- **Price change tracking:** "Noticed you just raised prices on X—here's how to frame that in email."
- **Product drop triggers:** "You just launched X—here's a 3-email sequence for it."
- **Pop-up audit:** "Your pop-up is leaving $X on the table—here's the fix."

This is **value-based personalization**, not data-scraping personalization. Much stronger positioning.

---

## Your AI Stack (Agreed)

| **Thinking + Strategy** | Antigravity + Skills | Brand research, economic analysis, email copywriting, pop-up audits, SOPs, performance tracking |
| **Batch Automation** | Claude Code | Weekly/daily digests, bulk processing, social listening, scheduled pipelines, cross-brand analysis |

---

## Antigravity Use Cases (Thinking + Strategy Layer)

| Use Case | What It Does |
|---|---|
| **Economic + Psychology Analysis** | Run brands through your proprietary framework to generate structured strategic insights. |
| **Email Copywriting** | Enter a brand name/URL → get fully researched, on-brand email sequences. |
| **Pop-Up Audit** | Upload a pop-up image → get Gamma-formatted slides based on your scoring rules. |
| **Research Synthesis** | Update your economic research master file by synthesizing weekly industry digests into durable insights. |
| **Performance Ledger** | Record every email's "DNA" (angle, copy, layout, send time) to identify what truly scales. |
| **SOPs + Strategic Docs** | Draft SOPs, sales prep docs, and strategic deliverables using your stored frameworks. |
| **Content Repurposing** | Synthesize research and client work into platform-specific content (tweets, LinkedIn posts, IG captions). |

### Skills to Build

| Skill | Purpose |
|---|---|
| `economic_research_skill.md` | Your proprietary framework for analyzing brands through an economic/psychology lens. References a master research doc you update weekly. |
| `email_performance_ledger_skill.md` | **[NEW]** Framework for logging email data: Purpose, Style, Layout, Economic Angle, Klaviyo Label, Performance Context. |
| `email_copywriting_skill.md` | Your full copywriting methodology. Enter a brand name, get custom email copy. |
| `popup_audit_skill.md` | Upload a pop-up image, get Gamma-formatted slides with conditional logic. |
| `content_repurposing_skill.md` | Turn research and client work into platform-specific social content. |

---

## Claude Code Use Cases (Batch Automation Layer)

| Use Case | What It Does |
|---|---|
| **Weekly Competitive Intel** | Track Dream 100 brand changes (pricing, drops, positioning) and output a markdown report. |
| **Beauty Industry Digest** | Pull relevant economic and consumer behavior signals from industry publications (daily or weekly). |
| **Cross-Brand Comparison** | Analyze your Performance Ledgers across different brands to find universal winning patterns. |
| **Bulk Research/Copy Processing** | Process CSVs of brand URLs to run bulk research or copy frameworks at scale. |
| **Social Listening (Candle Biz)** | Search TikTok/IG for candle-related keywords, extract top posts, analyze comment themes, output content angle ideas. |
| **Creator Analysis (Candle Biz)** | Identify high-performing candle creators, analyze formats/hooks/engagement, generate SR-specific content adaptations. |

### Scripts to Build

| Script | Purpose |
|---|---|
| `weekly_competitive_intel.py` | Visits Dream 100 sites, tracks changes, outputs report. |
| `beauty_digest.py` | Scrapes publications, filters for relevance, outputs digest. |
| `bulk_brand_research.py` | Takes CSV of URLs, runs frameworks, outputs batch results. |
| `candle_social_listening.py` | Searches TikTok/IG for keywords, analyzes engagement, outputs content ideas. |
| `candle_creator_analysis.py` | Finds top creators, analyzes their patterns, generates adapted content. |

---

## Personalization Triggers (Your Unique Angle)

Instead of generic scraping, your cold email triggers are:

| Trigger | What You Offer |
|---|---|
| **Pop-up error detected** | "Your pop-up has [X error]. Here's a free redesign." |
| **Price change detected** | "You just raised prices—here's how to communicate that via email." |
| **New product drop** | "Congrats on launching [X]. Here's a 3-email launch sequence." |
| **Economic shift in their category** | "Consumer sentiment in [category] just shifted—here's how to adapt your messaging." |

---

## Next Steps (When You're Ready)

1. **Build `popup_audit_skill.md`** — Fastest win. You already have the Gamma template nearly done.
2. **Build `email_performance_ledger_skill.md`** — Essential for data-backed growth.
3. **Build `economic_research_skill.md`** — Your core differentiator. Feed it your master research doc.
4. **Build `email_copywriting_skill.md`** — The "enter brand name, get emails" workflow.
5. **Build Weekly Intel script in Claude Code** — Your first real automation.

---

## How to Find This Document

This file is saved at:
```
Contoured-Content/Agency-Ops/Plans/ai_workflow_plan.md
```
Your skills are located in:
```
Contoured-Content/Agency-Ops/Skills/
```

You can also ask me: *"Show me my AI workflow plan"* and I'll pull it up.
