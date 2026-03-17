# New Section: "What Can AI Actually Do?" — Skills, Tools & MCP

> **Placement:** AFTER Slide 4 (What Does It Cost?) and BEFORE Slide 5 (AI Beyond Chat)
> This becomes the new Slide 5, pushing existing slides 5→6 and 6→7.

---

## MARKDOWN VERSION

---

## SLIDE 5 — What Can AI Actually Do?

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

> 💡 **What this means for you:** If your daily work involves writing, analysing data, or researching — AI is already a game-changer. Start here.

> 🎤 **Speaker note:** "This is where AI earns its keep. If you write emails, read reports, or analyse any kind of data — even occasionally — AI will save you hours every week. Not theoretically. Actually."

---

### Part 2: What AI Is Mediocre At ⚠️

These work, but manage your expectations. Think "helpful intern" not "expert":

- **Excel/Spreadsheets** — Can read and analyse data you upload. Can suggest formulas. But it can't directly edit your .xlsx file and give it back perfectly formatted. Output is often a markdown table or code snippet, not a polished spreadsheet. *Use it for analysis, not formatting.*

- **PowerPoint/Slides** — Can generate content, structure, and talking points. Tools like Gamma and Beautiful.ai help with design. But AI-generated slides often look generic — you'll want to polish them. Claude's artifacts can create basic slide-like views, which is what we used to build this talk.

- **Diagrams & Charts** — Can describe them, write code to generate them (Mermaid, SVG). Can't produce publication-quality visuals directly without a rendering tool.

- **Complex Formatting** — Multi-column layouts, branded templates, precise positioning — not there yet. It writes content brilliantly; it doesn't do graphic design.

- **Maths** — Basic arithmetic and business formulas are fine. Complex maths can have errors. Always double-check the numbers.

> 💡 **What this means for you:** Use AI to generate the *content*, then use your normal tools to make it look right. The 80/20 rule applies perfectly: AI does 80% of the work in 20% of the time. You do the last 20% (formatting, polish, checking).

> 🎤 **Speaker note:** "This is where people get disappointed — they expect AI to hand them a perfect PowerPoint or a formatted Excel file. It doesn't work that way yet. Think of AI as the brain, not the graphic designer. It creates the content; you make it pretty. Still saves you 80% of the time."

---

### Part 3: What AI Cannot Do (Today) 🚫

Be clear-eyed about the limits:

- **Access your local files** — unless you upload them or use integration tools (more on this in a moment)
- **Remember between conversations** — each new chat starts fresh, unless the tool has memory features (Claude Projects, ChatGPT memory)
- **Take actions in other software** — it can't click buttons in your CRM, send emails, or book meetings by itself... *unless* it's connected via something called MCP (and I'm about to explain that)
- **Guarantee accuracy** — hallucinations are real. AI can state completely made-up facts with total confidence. *Always verify facts, numbers, and especially legal text.*
- **Replace domain expertise** — it's a powerful assistant, not an expert. A bad prompt gets a confident but wrong answer. The human in the loop is still essential.

> 💡 **What this means for you:** AI is a brilliant assistant, not an autonomous employee. Trust but verify. Use it to draft, analyse, and brainstorm — then apply your own expertise and judgment before acting.

> 🎤 **Speaker note:** "This is the slide I wish every AI company would put on their homepage. AI is incredible, but it's not magic. It makes things up. It can't access your systems. It doesn't remember you. Knowing these limits is what separates people who use AI effectively from people who give up after one bad experience."

---

### Part 4: MCP — The Game-Changer 🔌

> 🎤 **Speaker note:** "Now, I just said AI can't access your files, your email, or your calendar. That's true... by default. But there's something new that's changing this — and it's called MCP. Let me explain it without any jargon."

**The problem:** AI lives in a box. It can only see what you copy-paste into it. It can't check your email, look at your calendar, query your database, or update your CRM.

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

## HTML VERSION

> **Instructions for merging:** Insert this HTML block as a new `<section>` between `<!-- SLIDE 4: Cost & Pricing -->` and `<!-- SLIDE 5: AI Beyond Chat -->`. Renumber subsequent slides (5→6, 6→7). Update the slide structure table and nav anchors accordingly.

```html
  <!-- SLIDE 5: What Can AI Actually Do? -->
  <section id="slide-5-capabilities">
    <div class="slide-header">
      <span class="slide-num">5</span>
      <h2>What Can AI Actually Do?</h2>
    </div>
    <div class="speaker-note">
      So we've covered who the players are, what the models do, and what it costs. Now the big question — what can AI actually <em>do</em> for your business? I'm going to be really honest here. There are things it's brilliant at, things it's okay at, and things it genuinely can't do yet. Knowing the difference is the most valuable thing I can teach you tonight.
    </div>

    <!-- Part 1: What AI is Good At -->
    <h3>✅ What AI Is Genuinely Good At</h3>
    <p>These are areas where AI is already better — or at least faster — than doing it yourself:</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Capability</th><th>What It Means For You</th><th>Rating</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Text</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Writing, editing, summarising, translating</span></td>
            <td>Emails in seconds. Reports drafted in minutes. Translate a document while you make tea.</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐⭐</td>
          </tr>
          <tr>
            <td><strong>Code</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Writing, debugging, explaining</span></td>
            <td>Even if you're not technical, AI can build simple tools, automate spreadsheets, create websites</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐⭐</td>
          </tr>
          <tr>
            <td><strong>Data Analysis</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Reading CSVs/Excel, spotting trends</span></td>
            <td>Upload a spreadsheet, ask "what's the trend?" and get a real answer</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐</td>
          </tr>
          <tr>
            <td><strong>Research</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Web search, synthesising sources</span></td>
            <td>Ask a question, get a structured answer with links you can verify</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐</td>
          </tr>
          <tr>
            <td><strong>Reasoning</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Logic, planning, problem breakdown</span></td>
            <td>"Here's my situation — what are my options?" AI thinks it through step by step</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐</td>
          </tr>
          <tr>
            <td><strong>Conversation</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Context-aware, remembers earlier chat</span></td>
            <td>It remembers what you said 20 messages ago. Better than most colleagues.</td>
            <td style="color:var(--green);white-space:nowrap;">⭐⭐⭐⭐⭐</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="recommendation" style="border-color:var(--accent);">
      <h4 style="color:var(--accent);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">If your daily work involves writing, analysing data, or researching — AI is already a game-changer. Start here.</p>
    </div>

    <div class="speaker-note">
      This is where AI earns its keep. If you write emails, read reports, or analyse any kind of data — even occasionally — AI will save you hours every week. Not theoretically. Actually.
    </div>

    <!-- Part 2: What AI is Mediocre At -->
    <h3>⚠️ What AI Is Mediocre At (Use With Caution)</h3>
    <p>These work, but manage your expectations. Think "helpful intern" not "expert":</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Task</th><th>What AI Can Do</th><th>The Catch</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Excel / Spreadsheets</strong></td>
            <td>Read and analyse uploaded data, suggest formulas, spot patterns</td>
            <td>Can't give you back a perfectly formatted .xlsx. Output is tables or code, not a polished spreadsheet.</td>
          </tr>
          <tr>
            <td><strong>PowerPoint / Slides</strong></td>
            <td>Generate content, structure, and talking points. Tools like Gamma help with design.</td>
            <td>AI slides often look generic. You'll want to polish them. Claude artifacts create basic slide views.</td>
          </tr>
          <tr>
            <td><strong>Diagrams & Charts</strong></td>
            <td>Describe them, write diagram code (Mermaid, SVG)</td>
            <td>Can't produce publication-quality visuals without a rendering tool.</td>
          </tr>
          <tr>
            <td><strong>Complex Formatting</strong></td>
            <td>Writes content brilliantly</td>
            <td>Multi-column layouts, branded templates, precise positioning — not there yet.</td>
          </tr>
          <tr>
            <td><strong>Maths</strong></td>
            <td>Basic arithmetic and business formulas work fine</td>
            <td>Complex maths can have errors. Always double-check the numbers.</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="recommendation" style="border-color:var(--amber);">
      <h4 style="color:var(--amber);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">Use AI to generate the <em>content</em>, then use your normal tools to make it look right. The 80/20 rule: AI does 80% of the work in 20% of the time. You handle the last 20% — formatting, polish, checking.</p>
    </div>

    <div class="speaker-note">
      This is where people get disappointed — they expect AI to hand them a perfect PowerPoint or a formatted Excel file. It doesn't work that way yet. Think of AI as the brain, not the graphic designer. It creates the content; you make it pretty. Still saves you 80% of the time.
    </div>

    <!-- Part 3: What AI Cannot Do -->
    <h3>🚫 What AI Cannot Do (Today)</h3>
    <p>Be clear-eyed about the limits:</p>

    <ul style="font-size:1.05rem;">
      <li><strong style="color:var(--pink);">Access your local files</strong> — unless you upload them or use integration tools (more on this in a moment)</li>
      <li><strong style="color:var(--pink);">Remember between conversations</strong> — each new chat starts fresh, unless the tool has memory features (Claude Projects, ChatGPT memory)</li>
      <li><strong style="color:var(--pink);">Take actions in other software</strong> — can't click buttons in your CRM, send emails, or book meetings by itself... <em>unless</em> it's connected via something called MCP (and I'm about to explain that)</li>
      <li><strong style="color:var(--pink);">Guarantee accuracy</strong> — hallucinations are real. AI can state completely made-up facts with total confidence. <em>Always verify facts, numbers, and especially legal text.</em></li>
      <li><strong style="color:var(--pink);">Replace domain expertise</strong> — it's a powerful assistant, not an expert. A bad prompt gets a confident but wrong answer. The human in the loop is still essential.</li>
    </ul>

    <div class="recommendation" style="border-color:var(--pink);">
      <h4 style="color:var(--pink);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">AI is a brilliant assistant, not an autonomous employee. Trust but verify. Use it to draft, analyse, and brainstorm — then apply your own expertise and judgment before acting.</p>
    </div>

    <div class="speaker-note">
      This is the slide I wish every AI company would put on their homepage. AI is incredible, but it's not magic. It makes things up. It can't access your systems. It doesn't remember you. Knowing these limits is what separates people who use AI effectively from people who give up after one bad experience.
    </div>

    <!-- Part 4: MCP -->
    <h3>🔌 MCP — The Game-Changer</h3>

    <div class="speaker-note">
      Now, I just said AI can't access your files, your email, or your calendar. That's true... by default. But there's something new that's changing this — and it's called MCP. Let me explain it without any jargon.
    </div>

    <div class="key-concept">
      <h3>AI lives in a box. MCP gives it hands.</h3>
      <p style="color:var(--text-muted); font-size:1.05rem; max-width:640px; margin:16px auto 0;">
        Think of MCP like <strong>USB ports for AI</strong>. Just like your laptop has ports that let you plug in a printer, camera, or external drive — MCP lets you plug external services into your AI tool.
      </p>
    </div>

    <p><strong>MCP</strong> stands for <em>Model Context Protocol</em>. Forget the name — here's what it actually means in practice:</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>You Connect AI to...</th><th>And Now It Can...</th></tr>
        </thead>
        <tbody>
          <tr><td>Your <strong>Google Drive</strong></td><td>Read and search your documents</td></tr>
          <tr><td>Your <strong>Calendar</strong></td><td>Check availability and schedule meetings</td></tr>
          <tr><td>Your <strong>Database</strong></td><td>Query and analyse your data directly</td></tr>
          <tr><td>Your <strong>Slack or Email</strong></td><td>Read messages and draft replies</td></tr>
          <tr><td>Your <strong>CRM</strong></td><td>Look up client information</td></tr>
          <tr><td>Your <strong>Accounting Software</strong></td><td>Pull financial reports</td></tr>
        </tbody>
      </table>
    </div>

    <h4>Who supports MCP today?</h4>
    <ul>
      <li><strong style="color:var(--accent);">Claude</strong> — native support in the Claude Desktop app</li>
      <li><strong style="color:var(--accent);">OpenClaw</strong> — built entirely on MCP (it's how it connects to everything)</li>
      <li><strong style="color:var(--accent);">Cursor, Windsurf</strong> — AI-powered code editors</li>
      <li>Growing ecosystem — new MCP integrations published daily</li>
    </ul>

    <div class="key-concept" style="text-align:left;">
      <h4 style="margin-top:0; text-align:center; color:var(--amber);">The Key Difference</h4>
      <p style="margin-bottom:8px;"><span style="color:var(--pink);">❌ Before MCP:</span> "Let me copy this data into ChatGPT and ask about it"</p>
      <p style="margin-bottom:0;"><span style="color:var(--green);">✅ With MCP:</span> "AI, check my email and tell me what's urgent"</p>
    </div>

    <div class="recommendation" style="border-color:var(--purple);">
      <h4 style="color:var(--purple);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">You don't need to understand MCP technically. Just know it exists and it's coming to every major AI tool. Within the next year, AI won't just answer questions — it'll actually <em>do things</em> in your business tools. The organisations that prepare for this will have a massive advantage.</p>
    </div>

    <div class="speaker-note">
      MCP is the thing I'm most excited about in AI right now. The early adopters — people connecting AI to their actual business systems — are seeing productivity gains that frankly feel unfair. This is still early days, and it does require some setup. But the direction is clear: AI is about to break out of the chat box.
    </div>

    <!-- Part 5: Skills & Plugins -->
    <h3>📱 Skills & Plugins — Apps for Your AI</h3>
    <p>One last concept: just like your phone has an app store, AI tools are getting their own version of apps.</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>AI Tool</th><th>How It Extends</th><th>Think of It As...</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Claude</strong></td>
            <td>MCP servers, Projects (persistent context), Artifacts</td>
            <td>Plugging in new capabilities + a filing cabinet that remembers</td>
          </tr>
          <tr>
            <td><strong>ChatGPT</strong></td>
            <td>GPTs (custom bots), Actions</td>
            <td>Pre-built mini-experts for specific tasks</td>
          </tr>
          <tr>
            <td><strong>OpenClaw</strong></td>
            <td>Skills (installable capabilities), MCP integration</td>
            <td>Apps on your AI's phone — install what you need</td>
          </tr>
          <tr>
            <td><strong>Notion AI</strong></td>
            <td>Built into your workspace, no extra setup</td>
            <td>AI that already knows where everything is</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="recommendation" style="border-color:var(--accent);">
      <h4 style="color:var(--accent);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">The AI you use today is the <em>least capable</em> version it will ever be. Every month, new integrations and skills make it more useful. The best strategy: pick one tool, learn it well, and it'll keep getting better around you.</p>
    </div>

    <div class="speaker-note">
      I don't want anyone to feel overwhelmed. You don't need to set up MCP tonight. You don't need to install skills or plugins. The message is simple: AI is getting more connected and more capable every month. Start with the basics — which is what we're about to do live — and know that it only gets better from here. Right, let's move on to the tools that exist today.
    </div>
  </section>
```

---

## MERGE INSTRUCTIONS

### For `talk-1-overview.md`:

1. Insert the markdown content (Parts 1–5 above) as a new **SLIDE 5** between the current SLIDE 4 (What Does It Cost?) and the current SLIDE 5 (AI Beyond Chat)
2. Renumber: current SLIDE 5 → SLIDE 6, current SLIDE 6 → SLIDE 7
3. Update the slide structure table at the top:

```
| Slide | Title | Duration |
|-------|-------|----------|
| 1 | Title slide | 15s |
| 2 | "Who's Who in AI" — landscape + model table | 2.5 min |
| 3 | Key concept: Models vs Tools | 30s |
| 4 | "What Does It Cost?" — pricing & plans | 2 min |
| 5 | "What Can AI Actually Do?" — capabilities, MCP, skills | 3 min |
| 6 | "AI Beyond Chat" — non-technical tools comparison | 2 min |
| 7 | "5 Things You'll See Me Do Live" — use cases | 2 min |
| 8 | Transition to Talk 2 / Q&A buffer | 1 min |
```

### For `index.html`:

1. Insert the HTML `<section>` block above between `<!-- SLIDE 4: Cost & Pricing -->` section closing `</section>` and `<!-- SLIDE 5: AI Beyond Chat -->`
2. Renumber slide badges: existing slide 5 → `<span class="slide-num">6</span>`, existing slide 6 → `<span class="slide-num">7</span>`
3. Update `id` attributes: existing `slide-5` → `slide-6`, existing `slide-6` → `slide-7`
4. Update any internal anchor links (e.g., `#slide-5` references)
