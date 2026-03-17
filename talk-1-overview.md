# Talk 1: AI in 2026 — The Landscape, The Tools, The Possibilities

**Duration:** 5–10 minutes
**Presenter:** Ali
**Audience:** Non-technical professionals — assume zero AI knowledge
**Goal:** Orient the room, build excitement, set up the live workshop (Talk 2)

---

## Suggested Slide Structure

| Slide | Title | Duration |
|-------|-------|----------|
| 1 | Title slide | 15s |
| 2 | "Who's Who in AI" — landscape + model table | 2.5 min |
| 3 | Key concept: Models vs Tools | 30s |
| 4 | "What Does It Cost?" — pricing & plans | 2 min |
| 5 | "AI Beyond Chat" — non-technical tools comparison | 2 min |
| 6 | "5 Things You'll See Me Do Live" — use cases | 2 min |
| 7 | Transition to Talk 2 / Q&A buffer | 1 min |

---

## SLIDE 1 — Title

### AI in 2026: What You Need to Know in 10 Minutes

*Enriched Solutions*

> 🎤 **Speaker note:** "Before we get into the hands-on stuff, I want to give everyone the same starting point. Whether you've been using ChatGPT daily or you've never touched it — by the end of this, you'll know who the players are, what the tools do, and what's actually possible for your business right now."

---

## SLIDE 2 — The AI Landscape: Who's Who

> 🎤 **Speaker note:** "Think of it like smartphones. There are a few big companies, each makes their own 'brain' — we call those models — and then there are apps where you actually use them. Here's the map."

### Company Overview

| Company | What They Do | Where You Use It | Known For |
|---------|-------------|-------------------|-----------|
| **OpenAI** | The company that started the current AI wave | **ChatGPT** (web, mobile, desktop) | The household name. Best all-rounder |
| **Google DeepMind** | Google's AI division | **Gemini app**, baked into Gmail/Docs/Sheets | Deeply integrated into Google products you already use |
| **Anthropic** | AI safety-focused company | **claude.ai** (web, mobile) | Excellent at long documents, analysis, careful reasoning |
| **Meta** | Facebook/Instagram parent | Available through many apps and platforms | Free and open-source — anyone can build with it |
| **xAI** | Elon Musk's AI company | Built into **X** (Twitter), standalone app | Real-time information, integrated into social media |
| **Perplexity** | AI-powered search engine | **perplexity.ai** (web, mobile) | Search with sources — answers, not links |

### Model Lineup by Category

Each company makes different models for different jobs — like how a car maker has a sports car, a family car, and a small city car.

| Company | 🧠 Thinking Model (Deep Reasoning) | ⚡ Standard Model (Everyday Use) | 🏎️ Fast/Lightweight Model | 🎨 Image Generation |
|---------|--------------------------------------|-----------------------------------|---------------------------|---------------------|
| **OpenAI** | GPT-5.4 Thinking | GPT-5.4 | GPT-4.1 mini | GPT Image (built-in) |
| **Google** | Gemini 3 Deep Think | Gemini 3.1 Pro | Gemini 3.1 Flash Lite | Imagen 4 |
| **Anthropic** | Claude Opus 4.6 | Claude Sonnet 4.6 | Claude Haiku 4.5 | None (vision only) |
| **Meta** | — | Llama 4 Maverick (400B MoE) | Llama 4 Scout (109B MoE) | Meta Imagine |
| **xAI** | Grok 4.1 Thinking | Grok 4.20 Beta | Grok 4.1 Fast | Aurora |
| **Perplexity** | — (aggregator) | Sonar / user picks model | — | — |

**What do these categories mean?**
- **Thinking models** take longer but work through complex problems step-by-step — great for analysis, strategy, hard questions
- **Standard models** are the everyday workhorses — fast and capable for most tasks
- **Fast/lightweight models** are optimised for speed and cost — good for simple questions, quick tasks
- **Image generation** creates pictures from text descriptions — logos, illustrations, mockups

> 🎤 **Speaker note:** "Don't worry about memorising this. The key takeaway: there are about 5–6 serious players right now. They all do similar things, they all have free tiers you can try tonight, and the differences are honestly shrinking. If you only try one — start with Claude. It's what I use for everything you're about to see."

**Optional mention:** Mistral (French company, strong in Europe, good for multilingual work)

---

## SLIDE 3 — The Key Concept

### Models are the engine. Tools are the car.

- The **model** (GPT-5.4, Claude, Gemini) is the intelligence — it understands language, reasons, generates
- The **tool** (ChatGPT, claude.ai, Gemini app) is how you interact with that intelligence for a specific job
- Many tools let you swap models — like choosing which engine goes in your car
- You don't need to understand engines to drive. Same here.

> 🎤 **Speaker note:** "This is the only technical concept I want you to take away. When someone says 'I used ChatGPT' — ChatGPT is the tool, GPT is the model inside it. When someone says 'I used Claude' — Claude is both the model and the tool name. That's it. You now understand the entire architecture."

---

## SLIDE 4 — What Does It Cost?

> 🎤 **Speaker note:** "The number one question I get: 'Do I have to pay for this?' Short answer — you can do a surprising amount for free, but the paid tiers are where it gets really powerful. Here's the honest breakdown."

### What Are Tokens?

Tokens are how AI measures text — roughly **1 token ≈ ¾ of a word**. So 1,000 tokens ≈ 750 words. When you send a message, the AI counts the tokens going in (your question) and coming out (the answer). Free tiers give you a limited number per day; paid tiers give you much more.

### Consumer Plans: Free vs Paid

| Service | Free Tier | What You Get Free | Pro/Paid Tier | Cost/Month | What Pro Adds |
|---------|-----------|-------------------|---------------|------------|---------------|
| **Claude** (Anthropic) | ✅ Yes | Sonnet/Haiku with usage limits; basic features | Claude Pro / Max | **$20/mo (~£16)** / Max from **$100/mo** | 5× more usage, Opus 4.6 access, priority, web search, file uploads |
| **ChatGPT** (OpenAI) | ✅ Yes | GPT-5.x (limited) + GPT-4.1 mini; image gen | ChatGPT Plus / Pro | **$20/mo (~£16)** / **$200/mo** | Full GPT-5.4, GPT-5.4 Thinking, unlimited usage, Deep Research |
| **Gemini** (Google) | ✅ Yes | Gemini Flash models; integrated into Google apps | Gemini Advanced | **$19.99/mo (~£16)** | Gemini 3.1 Pro, 3 Deep Think, 1M token context, deeper Google integration |
| **Grok** (xAI) | ✅ Yes (via X) | Basic Grok access on X | X Premium+ | **$22/mo (~£18)** | Full Grok 4.x access, Aurora image gen, no ads |
| **Perplexity** | ✅ Yes | Limited searches, basic LLM answers | Perplexity Pro | **~$20/mo (~£16)** | Choose backend model (GPT-5.4, Claude 4.6, Gemini 3.1 Pro), Deep Research |

*Prices approximate as of March 2026. All offer annual discounts.*

### For Developers / API Users (Brief Mention)

If you're building apps with AI, you pay per token rather than a monthly subscription. For context:

| Model | Input (per 1M tokens) | Output (per 1M tokens) |
|-------|----------------------|------------------------|
| Claude Sonnet 4.6 | ~$3 | ~$15 |
| Claude Opus 4.6 | ~$5 | ~$25 |
| Gemini 3.1 Flash Lite | ~$0.25 | ~$1.50 |
| Claude Haiku 4.5 | ~$1 | ~$5 |

*Most people in this room will use the consumer products, not the API — so don't worry about this table. It's here if you're curious.*

### 💡 Recommendation

**For most business users: Claude Pro at $20/month is the best value.** Here's why:
- Best-in-class for long documents, contracts, analysis, and writing
- Web search included
- Co-work feature for collaborative projects (more on this next)
- File upload for spreadsheets, PDFs, documents
- Consistently ranks highest for business/professional tasks
- *Note: Claude does not generate images — for that, use ChatGPT (free tier includes GPT Image)*

ChatGPT Plus is an equally strong choice — especially if you prefer OpenAI's ecosystem or need image generation. You genuinely can't go wrong with either.

> 🎤 **Speaker note:** "Here's my honest take: if you do nothing else after today, spend £16 on Claude Pro for one month and actually use it. Use it for everything — emails, analysis, contracts, research. If after a month you don't think it's worth it, cancel. But I've never met anyone who's cancelled."

---

## SLIDE 5 — AI Beyond Chat: Tools for Non-Technical Work

> 🎤 **Speaker note:** "Now, AI isn't just a chatbot you ask questions to. There are tools that embed AI into the work you're already doing. Here are three worth knowing about."

### Comparison: AI Productivity Tools

| Feature | **Claude Co-work** (Anthropic) | **OpenClaw** (Open Source) | **Notion AI** (Notion) |
|---------|-------------------------------|---------------------------|------------------------|
| **What It Is** | Collaborative workspace where Claude works alongside you — creates docs, spreadsheets, code, and artifacts in real-time | Personal AI assistant framework that connects AI to your email, calendar, messaging, files | AI built directly into Notion's project management, notes, and docs |
| **Underlying Model(s)** | Claude Sonnet 4.6 / Opus 4.6 | Any model (Claude, GPT, Gemini — you choose) | Multiple (Claude, GPT, Gemini) |
| **Key Functionality** | Draft documents, analyse data, create presentations, iterate collaboratively in a persistent workspace | "Check my email, summarise what's urgent, and draft replies." AI operates your tools directly | Summarise pages, generate content, answer questions about your Notion workspace |
| **Pricing** | Included with Claude Pro ($20/month) | Free (open-source, self-hosted) | $10/month per member (add-on to Notion plan) |
| **Best For** | Business professionals who want a versatile AI co-worker for documents, analysis, and creative work | Power users who want AI integrated into their actual workflow tools (email, calendar, etc.) | Teams already using Notion who want AI enhancements in their existing workspace |
| **Limitations** | Tied to Anthropic's ecosystem; requires Claude subscription for full features | Requires some technical setup; self-hosted means you manage it | Only works within Notion; limited outside that ecosystem |

> 🎤 **Speaker note:** "The takeaway: AI isn't just a chatbot. These tools embed AI into the work you're already doing. The gap between 'talking to an AI' and 'AI doing the work' is closing fast. For today's demos, we'll focus on Claude — because it's the most accessible and versatile for business users."

---

## SLIDE 6 — Five Things You're About to See Me Do Live

> 🎤 **Speaker note:** "Alright, enough theory. Here are five real business tasks I'm going to do live in the next session — no pre-prepared demos, no tricks. Just me, Claude, and a business problem. Each one demonstrates a different AI capability."

### 1. 📊 Turn Messy Financials into an Executive Summary
**Capability demonstrated: File upload + data analysis**
- **The task:** I'll take a raw, unformatted Excel spreadsheet of company financials — the kind your accountant emails you — and ask AI to clean it up, calculate key financial ratios (profit margin, burn rate, runway), and produce a board-ready executive summary
- **Tool:** Claude (claude.ai — upload the file, ask questions about it)
- **Why it's impressive:** This normally takes a financial analyst 2–3 hours. We'll do it in under 5 minutes.
- **What you'll see:** Messy spreadsheet in → clean summary with charts out

### 2. 📝 Draft a Professional Services Contract from a Brief
**Capability demonstrated: Long-form writing + iteration**
- **The task:** Given a one-paragraph description of a consulting engagement, I'll generate a full professional services agreement — proper legal structure, payment terms, IP clauses, limitation of liability — then refine specific clauses in real-time
- **Tool:** Claude (claude.ai)
- **Why it's impressive:** This is a £500–£2,000 job from a solicitor for a first draft. AI gets you 80% there in 2 minutes. (Still get it reviewed — but your starting point is dramatically better.)
- **What you'll see:** One-paragraph brief in → multi-page contract out → live clause refinement

### 3. 🎨 Create a Brand Identity from Scratch
**Capability demonstrated: Image generation from text**
- **The task:** We'll invent a fictional business on the spot (audience picks the concept), then generate a logo, colour palette, and brand guidelines. We'll use ChatGPT for logo generation (its built-in GPT Image model), then hop back to Claude for the full brand guidelines and tone of voice document
- **Tool:** ChatGPT (chatgpt.com — GPT Image for logo/visuals) + Claude (claude.ai — for brand guidelines document)
- **Why it's impressive:** A branding agency charges £5,000–£15,000 for this. We'll have a working first draft in minutes.
- **What you'll see:** Business idea → logo options (ChatGPT) → full brand guidelines document (Claude)

> 🎤 **Speaker note:** "This is the one demo where we switch tools. Claude is fantastic for text, analysis, and documents — but it doesn't generate images. ChatGPT's free tier includes excellent image generation via GPT Image, so we'll use the best tool for each job. This is actually a great lesson: you don't have to pick just one."

### 4. 🔍 Deep-Dive Market Research with Sources
**Capability demonstrated: Web search + research**
- **The task:** I'll pick a market (or the audience picks one), and ask AI to produce a structured competitive analysis — market size, key players, trends, threats, opportunities — with actual sources you can verify
- **Tool:** Claude (claude.ai — with built-in web search enabled)
- **Why it's impressive:** This is a week-long consulting engagement compressed into minutes. The sources are real, clickable, and verifiable.
- **What you'll see:** Market question → structured research report with citations

### 5. 🚀 Build an Investor Pitch Deck from a Napkin Idea
**Capability demonstrated: Presentation/artifact creation**
- **The task:** Starting from a one-line business idea, I'll produce a complete investor pitch deck — problem, solution, market size, business model, team slide, financial projections, the ask — directly in Claude as an artifact
- **Tool:** Claude (claude.ai — using artifacts to create the presentation directly)
- **Why it's impressive:** Founders spend weeks on pitch decks. We'll have a solid first draft in minutes. Claude can create structured presentations as artifacts that you can export.
- **What you'll see:** One-line idea → complete pitch deck with 10–12 slides

---

> 🎤 **Speaker note (transition to Talk 2):** "Five real tasks. No magic, no pre-prepared answers. Almost all done with Claude — plus ChatGPT for image generation. Both are available free to every single person in this room. Ready to see it happen? Let's go."

---

## Presenter Cheat Sheet

**If someone asks "which one should I use?":**
- For everything in today's demos: **Claude** (claude.ai — what I use daily)
- For image generation: **ChatGPT** (chatgpt.com — GPT Image, available on free tier)
- For research with sources: **Claude with web search** (or Perplexity as a free alternative)
- For anything in Google Workspace: **Gemini** (already built in)
- ChatGPT is also excellent — similar capabilities, different interface

**If someone asks "is it free?":**
- Claude: Free tier available, Pro $20/month (~£16), Max from $100/month
- ChatGPT: Free tier available, Plus $20/month (~£16), Pro $200/month
- Gemini: Free in Google products, Advanced $19.99/month (~£16)
- Grok: Free via X, full access with X Premium+ $22/month (~£18)
- Perplexity: Free with limits, Pro ~$20/month (~£16)

**If someone asks "is it safe / will it steal my data?":**
- All major providers have enterprise tiers where data isn't used for training
- For sensitive business data: use paid tiers, check the data policy
- Rule of thumb: don't put anything into a free AI tool that you wouldn't email to a stranger
- Paid tiers generally have stronger privacy guarantees

**If someone asks "will it replace my job?":**
- "AI won't replace you. But someone using AI might. That's why we're here tonight."
