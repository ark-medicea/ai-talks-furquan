# Meta, xAI & Perplexity — Model Lineups (as of March 17, 2026)

*Research compiled 2026-03-17*

---

## Meta (Llama)

### Current Model Family: Llama 4 (released April 5, 2025)

Architecture shifted to **Mixture of Experts (MoE)** — only a fraction of expert sub-networks activate per token. Multimodal (text + image input → text output), multilingual (12 languages). Knowledge cutoff: August 2024.

| Model | Active Params | Total Params | Experts | Context Window | Training Data |
|---|---|---|---|---|---|
| **Llama 4 Scout** | 17B | 109B | 16 | **10M tokens** | 40T tokens |
| **Llama 4 Maverick** | 17B | 400B | 128 | **1M tokens** | 22T tokens |
| **Llama 4 Behemoth** *(announced, not released)* | 288B | ~2T | 16 | TBD | TBD |

- Maverick was **codistilled from Behemoth**; Scout was trained from scratch.
- Behemoth was still in training at the time of Scout/Maverick release.
- Open weights, released as both base and instruction-tuned versions.

### Model Mapping

| Role | Model | Notes |
|---|---|---|
| **Thinking/Reasoning** | No dedicated reasoning model released yet | Behemoth could serve this role when/if released. No "Llama-o1" equivalent exists. |
| **Standard (flagship)** | **Llama 4 Maverick** (400B total, 17B active) | 128 experts, 1M context. Meta's top released model. |
| **Fast/Lightweight** | **Llama 4 Scout** (109B total, 17B active) | 16 experts, 10M context (!). Designed for efficiency. |
| **Image Generation** | **Meta AI Imagine** | Powers image generation within Meta AI assistant (WhatsApp, Instagram, Facebook). Based on Llama 4 / internal models (previously used Emu). Not a standalone API product. |

### Llama 4 Status Summary
- ✅ **Scout** — Released April 5, 2025
- ✅ **Maverick** — Released April 5, 2025
- ⏳ **Behemoth** — Announced but NOT released (was still in training)
- ⚠️ Benchmark controversy: Meta submitted an "experimental chat version" of Maverick to LMArena that differed from the public release, drawing criticism.

### Legacy (Still Active)
- Llama 3.3 (70B, 128K context, Dec 2024)
- Llama 3.2 (1B/3B/11B/90B variants, Sep 2024)
- Llama 3.1 (8B/70B/405B, 128K context, Jul 2024)

**Sources:**
- [Wikipedia: Llama (language model)](https://en.wikipedia.org/wiki/Llama_(language_model))
- [Meta AI blog](https://ai.meta.com/blog/)

---

## xAI (Grok)

### Current Model Family: Grok 4.x series

xAI has iterated rapidly through 2025 into early 2026. Now owned by SpaceX (acquisition Feb 2026).

### Version Timeline

| Model | Release Date | Status | Key Features |
|---|---|---|---|
| **Grok 3** | Feb 17, 2025 | Active | 10x compute vs Grok 2, reasoning via "Think" mode |
| **Grok 3 mini** | Feb 2025 | Discontinued | Faster, lighter alternative to Grok 3 |
| **Grok 4** | Jul 9, 2025 | Active | Multimodal, native tool use, real-time search |
| **Grok 4 Heavy** | Jul 9, 2025 | Active | More powerful variant (SuperGrok Heavy tier) |
| **Grok Code Fast 1** | Aug 28, 2025 | Active | Agentic coding specialist, fast & economical |
| **Grok 4 Fast** | Sep 2025 | Active | ~same performance as Grok 4, 40% fewer thinking tokens, 2M context |
| **Grok 4.1** | Nov 17, 2025 | Active | Improved reasoning, emotional intelligence, reduced hallucinations |
| **Grok 4.1 Thinking** | Nov 2025 | Active | Reasoning-focused variant |
| **Grok 4.1 Fast** | Nov 2025 | Active | Tool-calling & agentic workflows, 2M context, Agent Tools API |
| **Grok 4.20 Beta** | Feb 2026 | Active | **Newest flagship**. Speed, agentic tool calling, low hallucination, strict prompt adherence |

### Model Mapping

| Role | Model | Notes |
|---|---|---|
| **Thinking/Reasoning** | **Grok 4.1 Thinking** | Dedicated reasoning variant of 4.1 |
| **Standard (flagship)** | **Grok 4.20 Beta** | Newest flagship (Feb 2026). Also Grok 4.1 as stable option. |
| **Fast/Lightweight** | **Grok 4.1 Fast** / **Grok 4 Fast** | Optimised for speed & tool-calling. 2M context window. Up to 64× cheaper than early frontier models. |
| **Coding** | **Grok Code Fast 1** | Specialised for agentic coding. Available on Cursor, GitHub Copilot, etc. |
| **Image Generation** | **Aurora** (released Dec 9, 2024) | xAI's in-house text-to-image model. Photorealistic, few restrictions. API available since Mar 2025. |
| **Video Generation** | **Grok Imagine** (released Jul 28, 2025) | Text-to-video AND text-to-image model. |

### X Premium Pricing (current)

| Tier | Monthly | Annual | Key Grok Access |
|---|---|---|---|
| **Free** | $0 | — | Limited Grok access (restricted prompts) |
| **Basic** | $3/mo | $32/yr | No Grok access mentioned specifically |
| **Premium** | $8/mo | $84/yr | Grok chatbot access, half ads |
| **Premium+** | $22/mo | $229/yr | Full Grok access, no ads, articles |
| **SuperGrok** | Separate product | — | Access to Grok 4 Heavy and advanced features |

*Note: Premium+ was briefly raised to $40/mo around Grok 3 launch (Feb 2025), but the current Wikipedia listing shows $22/mo.*

### Grok API Pricing (Grok 3, launched Apr 2025)
- **Input:** $3 per million tokens (~750K words)
- **Output:** $15 per million tokens

**Sources:**
- [Wikipedia: Grok (chatbot)](https://en.wikipedia.org/wiki/Grok_(chatbot))
- [Wikipedia: X Premium](https://en.wikipedia.org/wiki/X_Premium)
- [x.ai/blog/grok-4](https://x.ai/blog/grok-4)

---

## Perplexity AI

### Overview
AI-powered search engine that synthesises web results with LLM-generated answers. Valued at **$21.2B** (Series E-6, early 2026). ARR grew from $80M (late 2024) to ~$200M (Feb 2026).

In Feb 2026, Perplexity **dropped ad-supported model** in favour of subscription-first approach.

### Backend Models (as of Mar 2026)
Perplexity Pro users can choose between:
- **GPT-5.4** (OpenAI)
- **Claude 4.6** (Anthropic)
- **Gemini 3.1 Pro** (Google)
- **Sonar** (Perplexity's own, based on Llama 3.3)

Also introduced **"Model Council"** feature (Feb 5, 2026) — compare outputs from multiple LLMs simultaneously.

*Previously offered R1 1776 (based on DeepSeek R1), now removed.*

### Pricing Tiers

| Tier | Price | Features |
|---|---|---|
| **Free** | $0 | Basic search with LLM answers, limited queries |
| **Pro** | ~$20/mo (standard pricing) | Choose backend model (GPT-5.4, Claude 4.6, Gemini 3.1 Pro, Sonar), file uploads, API access, Deep Research |
| **Enterprise Pro** | Custom pricing | Up to 500 file index, enhanced security, internal knowledge search |

*Free Pro access offered to students, US military veterans, and government employees.*

### Notable Products
- **Perplexity Pages** — structured reports from queries
- **Deep Research** — extended multi-step research
- **Comet Browser** — AI-integrated Chromium browser (launched Jul 2025, free Oct 2025)
- **Perplexity Assistant** — cross-app AI agent (launched Jan 2025)
- **Shopping Hub** — AI product recommendations (launched Nov 2024)
- **Finance** — real-time stock quotes & analysis
- **Truth Social chatbot** — contracted to build chatbot for Trump's platform

**Sources:**
- [Wikipedia: Perplexity AI](https://en.wikipedia.org/wiki/Perplexity_AI)
- [perplexity.ai](https://perplexity.ai)

---

## Quick Comparison Table

| Capability | Meta (Llama) | xAI (Grok) | Perplexity |
|---|---|---|---|
| **Thinking/Reasoning** | None released (Behemoth pending) | Grok 4.1 Thinking | Uses third-party (GPT-5.4, Claude 4.6) |
| **Standard Flagship** | Llama 4 Maverick (400B MoE) | Grok 4.20 Beta / Grok 4.1 | Sonar (own) + third-party |
| **Fast/Light** | Llama 4 Scout (109B MoE) | Grok 4.1 Fast / 4 Fast | N/A (aggregator) |
| **Image Gen** | Meta AI Imagine (internal) | Aurora + Grok Imagine | None (search-focused) |
| **Open Source?** | ✅ Open weights | ❌ Proprietary (Grok 2.5 source-available) | ❌ Proprietary |
| **Pricing** | Free (open weights) | Free tier + $8-$22/mo X Premium | Free + ~$20/mo Pro |
