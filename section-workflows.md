# New Section: "Putting It All Together — Workflow Automation"

> **Placement:** AFTER the Skills/Tools/MCP section (What Can AI Actually Do?) and BEFORE the "AI Beyond Chat" non-technical tools comparison.
> This becomes a new slide in the sequence, pushing subsequent slides forward by one.

---

## MARKDOWN VERSION

---

## SLIDE — Putting It All Together: Workflow Automation

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
- **Cost:** Free tier available, Pro from ~$9/month
- **Best for:** Non-technical users. Lots of ready-made templates. Friendliest interface.
- **Limitation:** Cloud-only — your data goes through their servers

#### Zapier
- **What it is:** The original workflow automation tool. The biggest integration library on the planet.
- **Integrations:** 6,000+ apps — if it exists, Zapier probably connects to it
- **AI capability:** AI actions available — you can ask AI to process data within a "Zap"
- **Cost:** Free tier (limited), paid from ~$20/month
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
- **Cost:** Free if you self-host; cloud version from ~$20/month
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
| **Make.com** | Free / $9+/mo | 1,500+ | ✅ Built-in | 🟢 Easy | Beginners, visual thinkers |
| **Zapier** | Free / $20+/mo | 6,000+ | ✅ Available | 🟢 Easy | Widest app support |
| **Power Automate** | Often included in M365 | Microsoft-deep | ✅ AI Builder | 🟡 Medium | Microsoft shops |
| **n8n** | Free (self-host) / $20+/mo | 400+ | ✅ Full | 🔴 Technical | Full control, privacy |
| **OpenClaw** | Free (open-source) | Via MCP/skills | ✅ AI-native | 🔴 Technical | AI-first automation |

> 🎤 **Speaker note (transition):** "Right — so that's the automation landscape. You've got the full picture now: what AI can do, how it connects to your tools, and how you can automate entire workflows. Now let me show you the specific tools that bring this to life for everyday work — and then we'll get into the live demos."

---

## HTML VERSION

> **Instructions for merging:** Insert this HTML block as a new `<section>` between the Skills/Tools/MCP section and the "AI Beyond Chat" section. Adjust slide numbers accordingly.

```html
  <!-- SLIDE: Workflow Automation -->
  <section id="slide-workflows">
    <div class="slide-header">
      <span class="slide-num">6</span>
      <h2>Putting It All Together: Workflow Automation</h2>
    </div>
    <div class="speaker-note">
      Alright, so we've covered what AI can do, what it can't do, and how it connects to your tools through MCP. Now here's the really exciting bit — what happens when you chain all of this together into workflows that run <em>without you</em>? This is where AI goes from 'a clever tool I use sometimes' to 'a system that works for me while I sleep.'
    </div>

    <!-- Part 1: What Are Workflow Automation Tools? -->
    <h3>🔄 What Are Workflow Automation Tools?</h3>
    <p>You know how you might set a rule in your email: "If an email comes from this address, move it to this folder"? Workflow automation tools are that idea, but on steroids.</p>
    <p>Instead of one simple rule, you build a <em>chain</em> of actions:</p>

    <div class="key-concept" style="text-align:left;">
      <h4 style="margin-top:0; text-align:center; color:var(--amber);">Example Workflow</h4>
      <p style="margin-bottom:8px;">📧 When I get an email from a client</p>
      <p style="margin-bottom:8px;">→ 🔍 Extract the key information</p>
      <p style="margin-bottom:8px;">→ 📋 Update my CRM</p>
      <p style="margin-bottom:8px;">→ ✍️ Draft a reply</p>
      <p style="margin-bottom:0;">→ ✅ Send it to me for approval</p>
    </div>

    <p>That's five steps, across three different apps, happening automatically. These tools have been around for years. But here's what's new: <strong>you can now add AI as a step in the chain.</strong> That means your automation can <em>think</em>, not just follow rigid rules.</p>

    <div class="recommendation" style="border-color:var(--accent);">
      <h4 style="color:var(--accent);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">Workflow automation isn't new. But workflow automation that can <em>reason</em> — that understands context, drafts intelligent responses, and makes judgment calls — that's brand new. And it's available right now.</p>
    </div>

    <div class="speaker-note">
      Think of it this way. The old version: 'When I get an email, file it in this folder.' The new version: 'When I get an email, read it, figure out if it's urgent, draft an appropriate reply, update my project tracker, and let me know if I need to do anything.' Same trigger — wildly different outcome.
    </div>

    <!-- Part 2: The Main Players -->
    <h3>🛠️ The Main Players</h3>
    <p>Here's a quick tour of the tools you can use today — ordered from simplest to most powerful:</p>

    <div class="use-case">
      <h4 style="color:var(--green);">Make.com <span style="font-size:0.85rem; color:var(--text-muted); font-weight:400;">(formerly Integromat)</span></h4>
      <span class="tool-badge">1,500+ Apps</span>
      <span class="capability-badge">AI Modules Built In</span>
      <ul>
        <li><strong>What it is:</strong> A visual workflow builder — you literally drag and drop to create automations</li>
        <li><strong>AI capability:</strong> Add a "call Claude" or "call GPT" step to any workflow</li>
        <li><strong>Cost:</strong> Free tier available, Pro from ~$9/month</li>
        <li><strong>Best for:</strong> Non-technical users. Lots of ready-made templates. Friendliest interface.</li>
        <li><strong>Limitation:</strong> Cloud-only — your data goes through their servers</li>
      </ul>
    </div>

    <div class="use-case">
      <h4 style="color:var(--green);">Zapier</h4>
      <span class="tool-badge">6,000+ Apps</span>
      <span class="capability-badge">AI Actions Available</span>
      <ul>
        <li><strong>What it is:</strong> The original workflow automation tool. The biggest integration library on the planet.</li>
        <li><strong>AI capability:</strong> AI actions to process data within a "Zap"</li>
        <li><strong>Cost:</strong> Free tier (limited), paid from ~$20/month</li>
        <li><strong>Best for:</strong> Simple automations with the widest app support. "I need X to talk to Y" — Zapier probably has it.</li>
        <li><strong>Limitation:</strong> Can get expensive as you add more workflows; AI features are newer</li>
      </ul>
    </div>

    <div class="use-case">
      <h4 style="color:var(--green);">Microsoft Power Automate</h4>
      <span class="tool-badge">Microsoft 365 Native</span>
      <span class="capability-badge">AI Builder</span>
      <ul>
        <li><strong>What it is:</strong> Microsoft's workflow tool, built right into Microsoft 365</li>
        <li><strong>AI capability:</strong> AI Builder for document processing, text analysis</li>
        <li><strong>Cost:</strong> Included with many M365 business licences — you might already have it</li>
        <li><strong>Best for:</strong> Companies already in the Microsoft ecosystem (Outlook, Teams, SharePoint)</li>
        <li><strong>Limitation:</strong> Strongest within Microsoft; connecting to non-Microsoft apps is less seamless</li>
      </ul>
    </div>

    <div class="use-case">
      <h4 style="color:var(--green);">n8n <span style="font-size:0.85rem; color:var(--text-muted); font-weight:400;">(open-source)</span></h4>
      <span class="tool-badge">400+ Integrations</span>
      <span class="capability-badge">Full AI Integration</span>
      <ul>
        <li><strong>What it is:</strong> A visual workflow builder like Make.com, but open-source and self-hostable</li>
        <li><strong>AI capability:</strong> Call Claude, GPT, or any model as a workflow step</li>
        <li><strong>Cost:</strong> Free if you self-host; cloud version from ~$20/month</li>
        <li><strong>Best for:</strong> Technical users who want full control. Your data stays on your own servers.</li>
        <li><strong>Limitation:</strong> Requires more technical knowledge to set up and maintain</li>
      </ul>
    </div>

    <div class="use-case" style="border-color:var(--accent);">
      <h4 style="color:var(--accent);">OpenClaw <span style="font-size:0.85rem; color:var(--text-muted); font-weight:400;">(the AI-native approach)</span></h4>
      <span class="tool-badge">MCP + Skills</span>
      <span class="capability-badge">AI Is the Orchestrator</span>
      <ul>
        <li><strong>What it is:</strong> Not a traditional workflow tool — it's an AI agent that <em>uses</em> tools</li>
        <li><strong>The difference:</strong> In Make.com or Zapier, AI is a step in your workflow. In OpenClaw, AI is the <em>orchestrator</em> — it decides what to do, in what order, based on the situation</li>
        <li><strong>How it works:</strong> Install "skills" (capabilities) and the AI figures out when and how to use them</li>
        <li><strong>Best for:</strong> When you want the AI to run the show, not just follow a script</li>
      </ul>
    </div>

    <div class="speaker-note">
      Notice the progression here. Make.com and Zapier are brilliant for 'when X happens, do Y.' Power Automate is the same but for Microsoft shops. n8n is for techies who want control. But OpenClaw flips the model — instead of you building the workflow, the AI builds it on the fly based on what you need. That's the direction everything is heading.
    </div>

    <!-- Part 3: AI + Workflows = The Real Power -->
    <h3>⚡ AI + Workflows = The Real Power</h3>
    <p>Here's the key insight:</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Approach</th><th>What It Does Well</th><th>What It Can't Do</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>AI alone</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">ChatGPT, Claude</span></td>
            <td>Thinks, writes, analyses</td>
            <td style="color:var(--pink);">You have to manually copy-paste everything in and out. It can't <em>do</em> things in your apps.</td>
          </tr>
          <tr>
            <td><strong>Workflows alone</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">Zapier, Make</span></td>
            <td>Connects apps, moves data, follows rules automatically</td>
            <td style="color:var(--pink);">Follows rigid rules. Can't think, adapt, or handle edge cases.</td>
          </tr>
          <tr>
            <td><strong style="color:var(--green);">AI + Workflows</strong><br><span style="font-size:0.85rem;color:var(--text-muted)">The magic combination</span></td>
            <td style="color:var(--green);">Connects apps <strong>AND</strong> thinks. Handles edge cases. Makes intelligent decisions within automated processes.</td>
            <td>This is where everything is heading.</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="key-concept" style="text-align:left;">
      <h4 style="margin-top:0; text-align:center; color:var(--amber);">Real-World Example</h4>
      <p style="margin-bottom:6px;"><strong>Every Monday morning at 7am:</strong></p>
      <p style="margin-bottom:6px;">1️⃣ Pull my calendar for the week</p>
      <p style="margin-bottom:6px;">2️⃣ Check which meetings need prep documents</p>
      <p style="margin-bottom:6px;">3️⃣ Pull the latest project data from our tools</p>
      <p style="margin-bottom:6px;">4️⃣ Draft prep docs for each meeting</p>
      <p style="margin-bottom:6px;">5️⃣ Save them in my Google Drive</p>
      <p style="margin-bottom:0;">6️⃣ If anything looks urgent, Slack me immediately</p>
    </div>

    <p>That's <strong>six different apps</strong>, <strong>AI reasoning</strong>, and <strong>conditional logic</strong> — running automatically while you sleep on Sunday night.</p>
    <p>Without AI, a workflow tool could do steps 1 and maybe 2 (if you've tagged meetings manually). With AI in the loop, it can <em>read</em> the meeting descriptions, <em>understand</em> what kind of prep is needed, <em>find</em> the relevant data, and <em>write</em> something useful.</p>

    <div class="recommendation" style="border-color:var(--green);">
      <h4 style="color:var(--green);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">You don't have to choose between AI and workflow automation. The real power is using them together. Start with a simple workflow (even just "email me a summary of my day"), then add AI steps as you get comfortable.</p>
    </div>

    <div class="speaker-note">
      This example always gets people. Because this isn't science fiction — every single piece of this is available today. The tools exist. The AI exists. The connections exist. The only thing missing is someone sitting down for an afternoon and setting it up. And that's exactly what we help businesses do.
    </div>

    <!-- Part 4: Choosing the Right Tool -->
    <h3>🧭 Choosing the Right Tool</h3>
    <p>Don't overthink it. Here's the quick decision guide:</p>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Your Situation</th><th>Start With</th><th>Why</th></tr>
        </thead>
        <tbody>
          <tr>
            <td>🏢 Your company runs on Microsoft 365</td>
            <td><strong style="color:var(--accent);">Power Automate</strong></td>
            <td>Already included in your licence. Deep Outlook/Teams integration.</td>
          </tr>
          <tr>
            <td>🎯 You want the simplest possible start</td>
            <td><strong style="color:var(--accent);">Make.com</strong></td>
            <td>Friendliest interface, lots of templates, great free tier.</td>
          </tr>
          <tr>
            <td>🔗 You need to connect obscure/niche apps</td>
            <td><strong style="color:var(--accent);">Zapier</strong></td>
            <td>6,000+ integrations — the biggest library by far.</td>
          </tr>
          <tr>
            <td>🔧 You're technical and want full control</td>
            <td><strong style="color:var(--accent);">n8n</strong></td>
            <td>Open-source, self-hosted, your data stays with you.</td>
          </tr>
          <tr>
            <td>🤖 You want AI to run the show</td>
            <td><strong style="color:var(--accent);">OpenClaw</strong></td>
            <td>AI-native — the agent decides what to do, not a rigid workflow.</td>
          </tr>
          <tr>
            <td>🌱 Just starting and not sure?</td>
            <td><strong style="color:var(--green);">Make.com</strong></td>
            <td>Start here. Upgrade later if you outgrow it.</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="recommendation" style="border-color:var(--purple);">
      <h4 style="color:var(--purple);">💡 What This Means For You</h4>
      <p style="margin-bottom:0;">You can start with <em>any</em> of these today — most have free tiers. Pick the one closest to your world and try automating one thing. Just one. You'll be hooked.</p>
    </div>

    <div class="speaker-note">
      My advice? Don't try to automate everything on day one. Pick one thing that annoys you — something you do every week that's repetitive and boring. Automate that. Once you see it working, you'll start spotting opportunities everywhere. That's how it starts.
    </div>

    <!-- Quick Summary Table -->
    <h3>📊 Quick Comparison</h3>

    <div class="table-wrap">
      <table>
        <thead>
          <tr><th>Tool</th><th>Price</th><th>Integrations</th><th>AI?</th><th>Difficulty</th><th>Best For</th></tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Make.com</strong></td>
            <td>Free / $9+/mo</td>
            <td>1,500+</td>
            <td style="color:var(--green);">✅ Built-in</td>
            <td>🟢 Easy</td>
            <td>Beginners, visual thinkers</td>
          </tr>
          <tr>
            <td><strong>Zapier</strong></td>
            <td>Free / $20+/mo</td>
            <td>6,000+</td>
            <td style="color:var(--green);">✅ Available</td>
            <td>🟢 Easy</td>
            <td>Widest app support</td>
          </tr>
          <tr>
            <td><strong>Power Automate</strong></td>
            <td>Often included in M365</td>
            <td>Microsoft-deep</td>
            <td style="color:var(--green);">✅ AI Builder</td>
            <td>🟡 Medium</td>
            <td>Microsoft shops</td>
          </tr>
          <tr>
            <td><strong>n8n</strong></td>
            <td>Free (self-host) / $20+/mo</td>
            <td>400+</td>
            <td style="color:var(--green);">✅ Full</td>
            <td>🔴 Technical</td>
            <td>Full control, privacy</td>
          </tr>
          <tr>
            <td><strong>OpenClaw</strong></td>
            <td>Free (open-source)</td>
            <td>Via MCP/skills</td>
            <td style="color:var(--green);">✅ AI-native</td>
            <td>🔴 Technical</td>
            <td>AI-first automation</td>
          </tr>
        </tbody>
      </table>
    </div>

    <div class="speaker-note">
      Right — so that's the automation landscape. You've got the full picture now: what AI can do, how it connects to your tools, and how you can automate entire workflows. Now let me show you the specific tools that bring this to life for everyday work — and then we'll get into the live demos.
    </div>
  </section>
```

---

## MERGE INSTRUCTIONS

### For `talk-1-overview.md`:

1. **Insert the markdown content** (Parts 1–4 plus Quick Summary above) as a new slide between:
   - **AFTER:** The "What Can AI Actually Do?" section (Skills/Tools/MCP — from `section-skills-tools-mcp.md`)
   - **BEFORE:** The "AI Beyond Chat: Tools for Non-Technical Work" section

2. **Update the slide structure table** at the top of `talk-1-overview.md` to include the new slide. With the MCP section already inserted, the table should be:

```
| Slide | Title | Duration |
|-------|-------|----------|
| 1 | Title slide | 15s |
| 2 | "Who's Who in AI" — landscape + model table | 2.5 min |
| 3 | Key concept: Models vs Tools | 30s |
| 4 | "What Does It Cost?" — pricing & plans | 2 min |
| 5 | "What Can AI Actually Do?" — capabilities, MCP, skills | 3 min |
| 6 | "Putting It All Together" — workflow automation | 2 min |
| 7 | "AI Beyond Chat" — non-technical tools comparison | 2 min |
| 8 | "5 Things You'll See Me Do Live" — use cases | 2 min |
| 9 | Transition to Talk 2 / Q&A buffer | 1 min |
```

3. **Renumber** subsequent slides accordingly (existing slide numbers shift +1 from the insertion point).

### For `index.html`:

1. **Insert the HTML `<section>` block** between:
   - **AFTER:** The closing `</section>` of the Skills/Tools/MCP section (`<!-- SLIDE 5: What Can AI Actually Do? -->` or `id="slide-5-capabilities"`)
   - **BEFORE:** The `<!-- SLIDE 5: AI Beyond Chat -->` section (which should already be renumbered to 6 after the MCP insert)

2. **Adjust slide numbers:** The `<span class="slide-num">` values in subsequent sections need to increment by 1 from the insertion point.

3. **Update `id` attributes** and any internal anchor links that reference later slides.

4. **Note:** The HTML block above uses `id="slide-workflows"` which is stable regardless of numbering. The `<span class="slide-num">6</span>` assumes MCP section is slide 5 — adjust if your numbering differs.

### Design Notes:
- Uses the same CSS classes as existing sections: `.use-case`, `.key-concept`, `.recommendation`, `.speaker-note`, `.table-wrap`, `.tool-badge`, `.capability-badge`
- No new CSS required — all styles are already defined in `index.html`
- Colour variables used: `--accent`, `--green`, `--amber`, `--pink`, `--purple` (all existing)
- Responsive-safe: all components use existing responsive breakpoints
