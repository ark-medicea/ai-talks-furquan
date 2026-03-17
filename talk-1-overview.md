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
| 3 | "What Does It Cost?" — pricing & plans | 2 min |
| 4 | "What Can AI Actually Do?" — capabilities, MCP, skills | 3 min |
| 5 | "Putting It All Together" — workflow automation | 2 min |
| 6 | "AI Beyond Chat" — non-technical tools comparison | 2 min |

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

## SLIDE 3 — What Does It Cost?

> 🎤 **Speaker note:** "The number one question I get: 'Do I have to pay for this?' Short answer — you can do a surprising amount for free, but the paid tiers are where it gets really powerful. Here's the honest breakdown."

### What Are Tokens?

Tokens are how AI measures text — roughly **1 token ≈ ¾ of a word**. So 1,000 tokens ≈ 750 words. When you send a message, the AI counts the tokens going in (your question) and coming out (the answer). Free tiers give you a limited number per day; paid tiers give you much more.

### Consumer Plans: Free vs Paid

| Service | Free Tier | What You Get Free | Paid Tier | Cost/Month | What Paid Adds |
|---------|-----------|-------------------|-----------|------------|----------------|
| **Claude** (Anthropic) | ✅ Yes | Sonnet/Haiku with usage limits; basic features | Pro | **£16/mo** | 5× more usage, Opus 4.6 access, priority, web search, file uploads, Co-work |
| | | | Max | **from £80/mo** | Everything in Pro + massive usage limits, extended thinking |
| **ChatGPT** (OpenAI) | ✅ Yes | GPT-5.x (limited) + GPT-4.1 mini; image gen | Plus | **£16/mo** | Full GPT-5.4, GPT-5.4 Thinking, more usage, Deep Research |
| | | | Pro | **£160/mo** | Unlimited usage, highest-tier models, voice mode |
| **Gemini** (Google) | ✅ Yes | Gemini Flash models; integrated into Google apps | Advanced | **£16/mo** | Gemini 3.1 Pro, 3 Deep Think, 1M token context, deeper Google integration |
| **Grok** (xAI) | ✅ Yes (via X) | Basic Grok access on X | X Premium+ | **£18/mo** | Full Grok 4.x access, Aurora image gen, no ads |
| **Perplexity** | ✅ Yes | Limited searches, basic LLM answers | Pro | **£16/mo** | Choose backend model (GPT-5.4, Claude 4.6, Gemini 3.1 Pro), Deep Research |

*Prices approximate as of March 2026. All offer annual discounts.*

### For Developers / API Users (Brief Mention)

If you're building apps with AI, you pay per token rather than a monthly subscription. For context:

| Model | Input (per 1M tokens) | Output (per 1M tokens) |
|-------|----------------------|------------------------|
| Claude Sonnet 4.6 | ~£2.40 | ~£12 |
| Claude Opus 4.6 | ~£4 | ~£20 |
| Gemini 3.1 Flash Lite | ~£0.20 | ~£1.20 |
| Claude Haiku 4.5 | ~£0.80 | ~£4 |

*Most people in this room will use the consumer products, not the API — so don't worry about this table. It's here if you're curious.*

### 💡 Recommendation

**For most business users: Claude Pro at £16/month is the best value.** Here's why:
- Best-in-class for long documents, contracts, analysis, and writing
- Web search included
- Co-work feature for collaborative projects (more on this next)
- File upload for spreadsheets, PDFs, documents
- Can generate and export Excel (.xlsx) and PowerPoint (.pptx) files via artifacts
- Consistently ranks highest for business/professional tasks
- *Note: Claude does not generate images — for that, use ChatGPT (free tier includes GPT Image)*

ChatGPT Plus is an equally strong choice — especially if you prefer OpenAI's ecosystem or need image generation. You genuinely can't go wrong with either.

> 🎤 **Speaker note:** "Here's my honest take: if you do nothing else after today, spend £16 on Claude Pro for one month and actually use it. Use it for everything — emails, analysis, contracts, research. If after a month you don't think it's worth it, cancel. But I've never met anyone who's cancelled."

---

## SLIDE 4 — What Can AI Actually Do?

> 🎤 **Speaker note:** "So we've covered who the players are, what the models do, and what it costs. Now the big question — what can AI actually *do* for your business? I'm going to be really honest here. There are things it's brilliant at, things it's okay at, and things it genuinely can't do yet. Knowing the difference is the most valuable thing I can teach you tonight."

---

### Part 1: What AI Is Genuinely Good At ✅

These are areas where AI is already better — or at least faster — than doing it yourself:

| Capability | What It Means For You | How Good? |
|-----------|----------------------|-----------|
| **Text** — writing, editing, summarising, translating | Emails in seconds. Reports drafted in minutes. Translate a document while you make tea. | ⭐⭐⭐⭐⭐ Excellent |
| **Code** — writing, debugging, explaining | Even if you're not technical, AI can build simple tools, automate spreadsheets, create websites | ⭐⭐⭐⭐⭐ Excellent |
| **Data analysis** — reading CSVs/Excel, spotting trends, calculating ratios | Upload a spreadsheet, ask "what's the trend?" and get a real answer | ⭐⭐⭐⭐ Very Good |
| **Research** — web search, synthesising sources, citing | Ask a question, get a structured answer with links you can verify | ⭐⭐⭐⭐ Very Good |
| **Reasoning** — logic, planning, breaking down complex problems | "Here's my situation — what are my options?" AI thinks it through step by step | ⭐⭐⭐⭐ Very Good |
| **Conversation** — context-aware dialogue, remembering earlier in the chat | It remembers what you said 20 messages ago. Better than most colleagues. | ⭐⭐⭐⭐⭐ Excellent |
| **File generation** — Excel (.xlsx), PowerPoint (.pptx), PDFs, CSVs | Claude can generate downloadable spreadsheets and presentations via artifacts | ⭐⭐⭐⭐ Very Good |

> 💡 **What this means for you:** If your daily work involves writing, analysing data, or researching — AI is already a game-changer. Start here.

> 🎤 **Speaker note:** "This is where AI earns its keep. If you write emails, read reports, or analyse any kind of data — even occasionally — AI will save you hours every week. Not theoretically. Actually. And one thing that's changed recently — Claude can now generate actual Excel and PowerPoint files you can download. Not just text — real files you can open in Office."

---

### Part 2: What AI Is Mediocre At ⚠️

These work, but manage your expectations:

- **Complex spreadsheet formatting** — AI can generate working .xlsx files with data and formulas, but don't expect pixel-perfect branded templates with conditional formatting and pivot tables. It generates *functional* spreadsheets, not design-award ones. Great for data exports; you may want to polish the formatting.

- **Presentation design** — AI can generate .pptx files and structured slide content, but the visual design tends to be basic. Tools like Gamma and Beautiful.ai help with the design side. For content and structure, AI is excellent; for making it look stunning, you'll want a human touch.

- **Diagrams & Charts** — Can describe them, write code to generate them (Mermaid, SVG). Interactive charts in artifacts work well. Publication-quality visuals for print still need a rendering tool.

- **Complex formatting** — Multi-column layouts, branded templates, precise positioning — not there yet. It writes content brilliantly; it doesn't do graphic design.

- **Maths** — Basic arithmetic and business formulas are fine. Complex maths can have errors. Always double-check the numbers.

> 💡 **What this means for you:** AI can now generate the files directly — Excel, PowerPoint, PDFs. The content will be good. The formatting will be functional but basic. Budget a few minutes to polish the look. The 80/20 rule still applies: AI does 80% of the work in 20% of the time.

> 🎤 **Speaker note:** "This used to be worse — AI couldn't generate actual files at all. Now Claude can hand you a real Excel spreadsheet or PowerPoint file. The content is solid. The formatting is... fine. Think of it as getting a perfectly written first draft that needs 10 minutes of design love. Still saves you hours."

---

### Part 3: What AI Cannot Do (Today) 🚫

Be clear-eyed about the limits:

- **Guarantee accuracy** — Hallucinations are real. AI can state completely made-up facts with total confidence. *Always verify facts, numbers, and especially legal text.*
- **Replace domain expertise** — It's a powerful assistant, not an expert. A bad prompt gets a confident but wrong answer. The human in the loop is still essential.
- **Remember between conversations** — Each new chat starts fresh, unless the tool has memory features (Claude Projects, ChatGPT memory).
- **Take actions in other software by default** — It can't click buttons in your CRM, send emails, or book meetings by itself... *unless* it's connected via something called MCP (and I'm about to explain that).

**What about accessing your files?** This has improved dramatically:
- **Claude Co-work** can now read files from your local machine — it has file system access within the Co-work environment
- **OpenClaw** has full local file access — it can read, search, and work with anything on your computer
- **Standard claude.ai chat** still requires you to upload files manually — but that takes seconds
- **ChatGPT** can read uploaded files and has persistent memory across conversations

> 💡 **What this means for you:** AI is a brilliant assistant, not an autonomous employee. Trust but verify. Use it to draft, analyse, and brainstorm — then apply your own expertise and judgment before acting. The biggest risk isn't that AI can't do something — it's that it does it *confidently wrong* and you don't check.

> 🎤 **Speaker note:** "The single most important thing on this slide: AI makes things up. Confidently. Convincingly. It will cite a study that doesn't exist, quote a statistic it invented, or draft a contract clause that sounds perfect but is legally nonsense. Always check. That said — the tools are getting much better at accessing your actual data. Claude Co-work can read your local files now. And tools like OpenClaw can access everything on your machine. The 'AI lives in a box' story is becoming less true every month."

---

### Part 4: MCP — The Game-Changer 🔌

> 🎤 **Speaker note:** "Now, I mentioned AI can't take actions in your other software — by default. But there's something that's changing this, and it's called MCP. Let me explain it without any jargon."

**The problem:** By default, AI can only see what you give it. It can't check your email, look at your calendar, query your database, or update your CRM.

**MCP is like giving AI hands.**

MCP stands for *Model Context Protocol*. But forget the name — here's what it actually means:

Think of it like **USB ports for AI**. Just like your laptop has USB ports that let you plug in a printer, a camera, or an external drive — MCP lets you plug external services into your AI tool.

**What this looks like in practice:**

| You connect AI to... | And now it can... |
|----------------------|-------------------|
| Your **Google Drive** | Read and search your documents |
| Your **calendar** | Check availability and schedule meetings |
| Your **database** | Query and analyse your data directly |
| Your **Slack or email** | Read messages and draft replies |
| Your **CRM** | Look up client information |
| Your **accounting software** | Pull financial reports |

**Who supports MCP today:**
- **Claude** — native support in Claude Desktop app
- **OpenClaw** — built entirely on MCP (it's how it connects to everything)
- **Cursor, Windsurf** — AI-powered code editors
- Growing ecosystem — new MCP integrations are being published daily

**The key insight:** MCP is why AI is about to get *dramatically* more useful. It's the difference between:
- ❌ "Let me copy this data into ChatGPT and ask about it"
- ✅ "AI, check my email and tell me what's urgent"

> 💡 **What this means for you:** You don't need to understand MCP technically. Just know that it exists and it's coming to every major AI tool. Within the next year, AI won't just answer questions — it'll actually *do things* in your business tools. The organisations that prepare for this will have a massive advantage.

> 🎤 **Speaker note:** "MCP is the thing I'm most excited about in AI right now. The early adopters — people connecting AI to their actual business systems — are seeing productivity gains that frankly feel unfair. This is still early days, and it does require some setup. But the direction is clear: AI is about to break out of the chat box."

---

### Part 5: Skills & Plugins — Apps for Your AI 📱

One last concept: just like your phone has an app store, AI tools are getting their own version of apps.

| AI Tool | How It Extends | Think of it as... |
|---------|---------------|-------------------|
| **Claude** | MCP servers, Projects (persistent context), Artifacts | Plugging in new capabilities + a filing cabinet that remembers |
| **ChatGPT** | GPTs (custom bots), Actions | Pre-built mini-experts for specific tasks |
| **OpenClaw** | Skills (installable capabilities), MCP integration | Apps on your AI's phone — install what you need |
| **Notion AI** | Built into your workspace, no extra setup | AI that already knows where everything is |

> 💡 **What this means for you:** The AI you use today is the *least capable* version it will ever be. Every month, new integrations and skills make it more useful. The best strategy: pick one tool, learn it well, and it'll keep getting better around you.

> 🎤 **Speaker note:** "I don't want anyone to feel overwhelmed. You don't need to set up MCP tonight. You don't need to install skills or plugins. The message is simple: AI is getting more connected and more capable every month. Start with the basics — which is what we're about to do live — and know that it only gets better from here. Right, let's move on to the tools that exist today."

---

## SLIDE 5 — Putting It All Together: Workflow Automation

> 🎤 **Speaker note:** "Alright, so we've covered what AI can do, what it can't do, and how it connects to your tools through MCP. Now here's the really exciting bit — what happens when you chain all of this together into workflows that run *without you*? This is where AI goes from 'a clever tool I use sometimes' to 'a system that works for me while I sleep.'"

---

### Part 1: What Are Workflow Automation Tools?

You know how you might set a rule in your email: "If an email comes from this address, move it to this folder"? Workflow automation tools are that idea, but on steroids.

Instead of one simple rule, you build a *chain* of actions:

> **Example:** "When I get an email from a client → extract the key information → update my CRM → draft a reply → send it to me for approval"

That's five steps, across three different apps, happening automatically.

These tools have been around for years. But here's what's new: **you can now add AI as a step in the chain.** That means your automation can *think*, not just follow rigid rules.

> 💡 **What this means for you:** Workflow automation isn't new. But workflow automation that can *reason* — that understands context, drafts intelligent responses, and makes judgment calls — that's brand new. And it's available right now.

> 🎤 **Speaker note:** "Think of it this way. The old version: 'When I get an email, file it in this folder.' The new version: 'When I get an email, read it, figure out if it's urgent, draft an appropriate reply, update my project tracker, and let me know if I need to do anything.' Same trigger — wildly different outcome."

---

### Part 2: The Main Players

Here's a quick tour of the tools you can actually use today. I've ordered them from simplest to most powerful:

#### Make.com (formerly Integromat)
- **What it is:** A visual workflow builder — you literally drag and drop to create automations
- **Integrations:** 1,500+ apps (Gmail, Slack, Notion, HubSpot, Xero, you name it)
- **AI capability:** AI modules built in — add a "call Claude" or "call GPT" step to any workflow
- **Cost:** Free tier available, Pro from ~£7/month
- **Best for:** Non-technical users. Lots of ready-made templates. Friendliest interface.
- **Limitation:** Cloud-only — your data goes through their servers

#### Zapier
- **What it is:** The original workflow automation tool. The biggest integration library on the planet.
- **Integrations:** 6,000+ apps — if it exists, Zapier probably connects to it
- **AI capability:** AI actions available — you can ask AI to process data within a "Zap"
- **Cost:** Free tier (limited), paid from ~£16/month
- **Best for:** Simple automations with the widest app support. "I need X to talk to Y" — Zapier probably has it.
- **Limitation:** Can get expensive as you add more workflows; AI features are newer

#### Microsoft Power Automate
- **What it is:** Microsoft's workflow tool, built right into Microsoft 365
- **Integrations:** Deep integration with Office, Teams, SharePoint, Outlook, Dynamics
- **AI capability:** AI Builder for adding AI steps (document processing, text analysis)
- **Cost:** Included with many Microsoft 365 business licences — you might already have it
- **Best for:** Companies already in the Microsoft ecosystem. If your business runs on Outlook, Teams, and SharePoint — this is the natural choice.
- **Limitation:** Strongest within the Microsoft world; connecting to non-Microsoft apps is possible but less seamless

#### n8n (open-source)
- **What it is:** A visual workflow builder like Make.com, but open-source and self-hostable
- **Integrations:** 400+ built-in, plus you can connect to anything with an API
- **AI capability:** Full AI integration — call Claude, GPT, or any model as a workflow step
- **Cost:** Free if you self-host; cloud version from ~£16/month
- **Best for:** Technical users who want full control. Your data stays on your own servers.
- **Limitation:** Requires more technical knowledge to set up and maintain

#### OpenClaw (the AI-native approach)
- **What it is:** Not a traditional workflow tool — it's an AI agent that *uses* tools
- **The difference:** In Make.com or Zapier, AI is a step in your workflow. In OpenClaw, AI is the *orchestrator* — it decides what to do, in what order, based on the situation
- **How it works:** Install "skills" (capabilities) and the AI figures out when and how to use them
- **Best for:** When you want the AI to run the show, not just follow a script

> 🎤 **Speaker note:** "Notice the progression here. Make.com and Zapier are brilliant for 'when X happens, do Y.' Power Automate is the same but for Microsoft shops. n8n is for techies who want control. But OpenClaw flips the model — instead of you building the workflow, the AI builds it on the fly based on what you need. That's the direction everything is heading."

---

### Part 3: AI + Workflows = The Real Power

Here's the key insight I want you to take away:

| On Its Own | What It Does Well | What It Can't Do |
|-----------|-------------------|-----------------|
| **AI alone** (ChatGPT, Claude) | Thinks, writes, analyses | You have to manually copy-paste everything in and out. It can't *do* things in your apps. |
| **Workflows alone** (Zapier, Make) | Connects apps, moves data, follows rules automatically | Follows rigid rules. Can't think, adapt, or handle edge cases. |
| **AI + Workflows** | Connects apps AND thinks. Handles edge cases. Makes intelligent decisions within automated processes. | This is the magic combination. |

**A real-world example:**

> "Every Monday morning at 7am:
> 1. Pull my calendar for the week
> 2. Check which meetings need preparation documents
> 3. Pull the latest project data from our tools
> 4. Draft prep docs for each meeting
> 5. Save them in my Google Drive
> 6. If anything looks urgent, Slack me immediately"

That's **six different apps**, **AI reasoning**, and **conditional logic** — running automatically while you sleep on Sunday night.

Without AI, a workflow tool could do steps 1 and maybe 2 (if you've tagged meetings manually). With AI in the loop, it can *read* the meeting descriptions, *understand* what kind of prep is needed, *find* the relevant data, and *write* something useful.

> 💡 **What this means for you:** You don't have to choose between AI and workflow automation. The real power is using them together. Start with a simple workflow (even just "email me a summary of my day"), then add AI steps as you get comfortable.

> 🎤 **Speaker note:** "This example always gets people. Because this isn't science fiction — every single piece of this is available today. The tools exist. The AI exists. The connections exist. The only thing missing is someone sitting down for an afternoon and setting it up. And that's exactly what we help businesses do."

---

### Part 4: Choosing the Right Tool

Don't overthink it. Here's the quick decision guide:

| Your Situation | Start With | Why |
|---------------|------------|-----|
| 🏢 Your company runs on Microsoft 365 | **Power Automate** | It's already included in your licence. Deep Outlook/Teams integration. |
| 🎯 You want the simplest possible start | **Make.com** | Friendliest interface, lots of templates, great free tier. |
| 🔗 You need to connect obscure/niche apps | **Zapier** | 6,000+ integrations — the biggest library by far. |
| 🔧 You're technical and want full control | **n8n** | Open-source, self-hosted, your data stays with you. |
| 🤖 You want AI to run the show | **OpenClaw** | AI-native — the agent decides what to do, not a rigid workflow. |
| 🌱 You're just starting and don't know | **Make.com** | Start here. Upgrade later if you outgrow it. |

> 💡 **What this means for you:** You can start with *any* of these today — most have free tiers. Pick the one closest to your world and try automating one thing. Just one. You'll be hooked.

> 🎤 **Speaker note:** "My advice? Don't try to automate everything on day one. Pick one thing that annoys you — something you do every week that's repetitive and boring. Automate that. Once you see it working, you'll start spotting opportunities everywhere. That's how it starts."

---

### Quick Summary

| Tool | Price | Integrations | AI? | Technical Level | Best For |
|------|-------|-------------|-----|----------------|----------|
| **Make.com** | Free / £7+/mo | 1,500+ | ✅ Built-in | 🟢 Easy | Beginners, visual thinkers |
| **Zapier** | Free / £16+/mo | 6,000+ | ✅ Available | 🟢 Easy | Widest app support |
| **Power Automate** | Often included in M365 | Microsoft-deep | ✅ AI Builder | 🟡 Medium | Microsoft shops |
| **n8n** | Free (self-host) / £16+/mo | 400+ | ✅ Full | 🔴 Technical | Full control, privacy |
| **OpenClaw** | Free (open-source) | Via MCP/skills | ✅ AI-native | 🔴 Technical | AI-first automation |

> 🎤 **Speaker note (transition):** "Right — so that's the automation landscape. You've got the full picture now: what AI can do, how it connects to your tools, and how you can automate entire workflows. Now let me show you the specific tools that bring this to life for everyday work."

---

## SLIDE 6 — AI Beyond Chat: Tools for Non-Technical Work

> 🎤 **Speaker note:** "Now, AI isn't just a chatbot you ask questions to. There are tools that embed AI into the work you're already doing. Here are three worth knowing about."

### Comparison: AI Productivity Tools

| Feature | **Claude Co-work** (Anthropic) | **OpenClaw** (Open Source) | **Notion AI** (Notion) |
|---------|-------------------------------|---------------------------|------------------------|
| **What It Is** | Collaborative workspace where Claude works alongside you — creates docs, spreadsheets, code, and artifacts in real-time | Personal AI assistant framework that connects AI to your email, calendar, messaging, files | AI built directly into Notion's project management, notes, and docs |
| **Underlying Model(s)** | Claude Sonnet 4.6 / Opus 4.6 | Any model (Claude, GPT, Gemini — you choose) | Multiple (Claude, GPT, Gemini) |
| **Key Functionality** | Draft documents, analyse data, create presentations, generate Excel/PowerPoint files, read your local files, iterate collaboratively in a persistent workspace | "Check my email, summarise what's urgent, and draft replies." AI operates your tools directly with full local file access | Summarise pages, generate content, answer questions about your Notion workspace |
| **Pricing** | Included with Claude Pro (£16/month) | Free (open-source, self-hosted) | ~£8/month per member (add-on to Notion plan) |
| **Best For** | Business professionals who want a versatile AI co-worker for documents, analysis, and creative work | Power users who want AI integrated into their actual workflow tools (email, calendar, etc.) | Teams already using Notion who want AI enhancements in their existing workspace |
| **Limitations** | Tied to Anthropic's ecosystem; requires Claude subscription for full features | Requires some technical setup; self-hosted means you manage it | Only works within Notion; limited outside that ecosystem |

> 🎤 **Speaker note:** "The takeaway: AI isn't just a chatbot. These tools embed AI into the work you're already doing. Claude Co-work can now read your local files and generate actual Excel and PowerPoint documents. OpenClaw can access everything on your machine. The gap between 'talking to an AI' and 'AI doing the work' is closing fast."

---

## Presenter Cheat Sheet

**If someone asks "which one should I use?":**
- For everything in today's demos: **Claude** (claude.ai — what I use daily)
- For image generation: **ChatGPT** (chatgpt.com — GPT Image, available on free tier)
- For research with sources: **Claude with web search** (or Perplexity as a free alternative)
- For anything in Google Workspace: **Gemini** (already built in)
- ChatGPT is also excellent — similar capabilities, different interface

**If someone asks "is it free?":**
- Claude: Free tier available, Pro £16/month, Max from £80/month
- ChatGPT: Free tier available, Plus £16/month, Pro £160/month
- Gemini: Free in Google products, Advanced £16/month
- Grok: Free via X, full access with X Premium+ £18/month
- Perplexity: Free with limits, Pro £16/month

**If someone asks "is it safe / will it steal my data?":**
- All major providers have enterprise tiers where data isn't used for training
- For sensitive business data: use paid tiers, check the data policy
- Rule of thumb: don't put anything into a free AI tool that you wouldn't email to a stranger
- Paid tiers generally have stronger privacy guarantees

**If someone asks "will it replace my job?":**
- "AI won't replace you. But someone using AI might. That's why we're here tonight."

**If someone asks "can AI generate Excel/PowerPoint files?":**
- Yes! Claude can generate downloadable .xlsx and .pptx files via artifacts
- The content and structure will be solid; formatting will be functional but basic
- For polished presentations, use AI for the content then refine in PowerPoint/Keynote
- ChatGPT can also generate files, and tools like Gamma specialise in AI presentations
