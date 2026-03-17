# Anthropic — Claude Model Lineup (as of March 17, 2026)

## Current Models (Latest Generation)

### Claude Opus 4.6 — Thinking / Flagship Model
- **API ID:** `claude-opus-4-6`
- **Description:** "The most intelligent model for building agents and coding"
- **Context window:** 1M tokens (~750k words)
- **Max output:** 128k tokens
- **Extended thinking:** ✅ Yes
- **Adaptive thinking:** ✅ Yes
- **API Pricing:** $5/input MTok · $25/output MTok
- **Latency:** Moderate
- **Knowledge cutoff:** Reliable through May 2025; training data through Aug 2025
- **Note:** This is the newest model — the docs page has a dedicated "Migrating to Claude 4.6" section

### Claude Sonnet 4.6 — Standard / Balanced Model
- **API ID:** `claude-sonnet-4-6`
- **Description:** "The best combination of speed and intelligence"
- **Context window:** 1M tokens
- **Max output:** 64k tokens
- **Extended thinking:** ✅ Yes
- **Adaptive thinking:** ✅ Yes
- **API Pricing:** $3/input MTok · $15/output MTok
- **Latency:** Fast
- **Knowledge cutoff:** Reliable through Aug 2025; training data through Jan 2026

### Claude Haiku 4.5 — Fast / Lightweight Model
- **API ID:** `claude-haiku-4-5` (alias) / `claude-haiku-4-5-20251001` (snapshot)
- **Description:** "The fastest model with near-frontier intelligence"
- **Context window:** 200k tokens
- **Max output:** 64k tokens
- **Extended thinking:** ✅ Yes
- **Adaptive thinking:** ❌ No
- **API Pricing:** $1/input MTok · $5/output MTok
- **Latency:** Fastest
- **Knowledge cutoff:** Reliable through Feb 2025; training data through Jul 2025
- **Released:** October 2025

## Image Generation
- **Claude does NOT generate images.** As of March 2026, Claude remains a text-and-vision model — it can *analyze* images (vision input) but cannot *generate* them.
- No Anthropic image generation model exists. For image gen, users rely on third-party models (DALL-E, Midjourney, Stable Diffusion, Google Imagen, etc.)

## Model Evolution Timeline
| Date | Release |
|------|---------|
| May 22, 2025 | **Claude 4** launched (Opus 4 + Sonnet 4) — major generation leap |
| Aug 5, 2025 | **Claude Opus 4.1** released |
| Sep 29, 2025 | **Claude Sonnet 4.5** released |
| Oct 15, 2025 | **Claude Haiku 4.5** released |
| Nov 1, 2025 (approx) | **Claude Opus 4.5** released |
| ~March 2026 | **Claude Opus 4.6** and **Claude Sonnet 4.6** released (current) |

## Legacy Models (still available)
| Model | API ID | Pricing (input/output per MTok) |
|-------|--------|--------------------------------|
| Claude Sonnet 4.5 | `claude-sonnet-4-5-20250929` | $3 / $15 |
| Claude Opus 4.5 | `claude-opus-4-5-20251101` | $5 / $25 |
| Claude Opus 4.1 | `claude-opus-4-1-20250805` | $15 / $75 |
| Claude Sonnet 4 | `claude-sonnet-4-20250514` | $3 / $15 |
| Claude Opus 4 | `claude-opus-4-20250514` | $15 / $75 |
| Claude Haiku 3 | `claude-3-haiku-20240307` | $0.25 / $1.25 (**deprecated**, retiring April 19, 2026) |

**Note on pricing evolution:** Opus 4.6 ($5/$25) is dramatically cheaper than the original Opus 4 ($15/$75), making the flagship model much more accessible.

## Claude.ai Subscription Tiers

### Free Tier
- **Price:** $0
- Access to Claude (likely Sonnet/Haiku models)
- Limited message volume
- No extended thinking / advanced features
- Basic access to claude.ai web interface

### Claude Pro
- **Price:** $20/month
- Higher message limits
- Access to Claude Opus (the most capable model)
- Priority access during high-traffic periods
- Extended thinking capabilities
- Access to new features first

### Claude Max
- **Price:** From $100/month (multiple tiers up to ~$200/month)
- Significantly higher or unlimited usage limits
- 5x–20x more usage than Pro (depending on tier)
- All Pro features plus higher capacity

### Claude Team
- **Price:** $25–30/seat/month (+ usage-based billing)
- Team collaboration features
- Admin controls and workspace management
- Higher limits per seat

### Claude Enterprise
- **Price:** Custom pricing (contact sales)
- Enterprise security features (SSO, SCIM)
- Self-serve and sales-assisted options available
- Custom data retention policies

## Notable Products & Features (March 2026)
- **Claude Code** — Command-line agentic coding tool (major product, think Cursor/Copilot competitor)
- **Claude Agent SDK** — SDK for building agents on top of Claude
- **Claude Cowork** — Desktop tool for non-developers to automate file and task management
- **Claude for Chrome** — Browser agent (beta)
- **Claude for Excel** — Spreadsheet agent (beta)
- **Claude for PowerPoint** — Presentation tool
- **Claude for Slack** — Slack integration
- **Skills & Plugins** — Installable bundles of MCPs, skills, and tools for Claude Code / Cowork
- **MCP (Model Context Protocol)** — Open protocol for tool/service integration
- **Extended Thinking** — Chain-of-thought reasoning (available on Opus 4.6, Sonnet 4.6, Haiku 4.5)
- **Adaptive Thinking** — Dynamic reasoning depth (Opus 4.6, Sonnet 4.6 only)
- **1M Token Context** — Opus 4.6 and Sonnet 4.6 natively support 1M tokens

## Key Competitive Differentiators
1. **Agentic capabilities** — Claude is heavily positioned for AI agents and autonomous coding (Claude Code, Agent SDK, Cowork)
2. **Extended/Adaptive Thinking** — Built-in chain-of-thought reasoning, not just a wrapper
3. **Massive context** — 1M tokens on flagship models
4. **Safety focus** — Anthropic's constitutional AI approach, emphasis on alignment
5. **MCP ecosystem** — Open protocol for third-party tool integration

## Sources
- Anthropic Models Docs: https://docs.anthropic.com/en/docs/about-claude/models
- Anthropic Pricing: https://www.anthropic.com/pricing
- Anthropic News/Blog: https://www.anthropic.com/news
- Claude Platform: https://platform.claude.com/docs/en/about-claude/models/overview
