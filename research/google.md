# Google DeepMind — Model Lineup (as of March 17, 2026)

## Current Model Family

Google's AI models are organised under the **Gemini** brand, currently in the **3.x generation**. The stable release lineup comprises: Gemini 3.1 Pro, 3 Deep Think, 3 Flash, 3.1 Flash Lite, and 3.1 Flash Image.

---

## Flagship / Standard Model: **Gemini 3.1 Pro**

- **Released:** February 19, 2026
- **API ID:** `gemini-3.1-pro-preview`, `gemini-3.1-pro-preview-customtools`
- **Description:** The latest and most capable Gemini model. Best-in-class for multimodal understanding, agentic capabilities, coding, and complex reasoning ("vibe-coding"). Replaces Gemini 3 Pro (deprecated March 9, 2026).
- **Context window:** Large (continuation of 1M+ token support from 2.5 series)
- **Key capabilities:** Multimodal (text, image, video, audio), agentic tool use, code generation, custom tools support
- **Source:** [Google Blog — "Gemini 3.1 Pro: A smarter model for your most complex tasks"](https://blog.google/technology/google-deepmind/gemini-3-1-pro/) (Feb 19, 2026)

### API Pricing (Paid Tier, per 1M tokens)
| | Standard |
|---|---|
| **Input** | $2.00 (≤200k) / $4.00 (>200k) |
| **Output** (incl. thinking) | $12.00 (≤200k) / $18.00 (>200k) |
| **Context caching** | $0.20 (≤200k) / $0.40 (>200k) + $4.50/M tokens/hr storage |
| **Free tier** | ❌ Not available |

---

## Thinking / Reasoning Model: **Gemini 3 Deep Think**

- **Released:** November 18, 2025 (announced); December 4, 2025 (rolled out to Ultra subscribers)
- **Description:** Google's dedicated reasoning model, based on the "Deep Think" mode that first appeared in Gemini 2.5 Pro. Excels at complex reasoning, math, science, and competitive programming (high ratings on IOI benchmarks). Uses chain-of-thought reasoning with extended thinking.
- **Access:** Available to Gemini Advanced (Ultra) subscribers in the Gemini app
- **API availability:** Not separately listed on the pricing page as of March 2026 — reasoning capabilities are integrated into the Pro models via "thinking tokens"
- **Source:** [Google — "Gemini 3 Deep Think is now available in the Gemini app"](https://blog.google/technology/google-deepmind/gemini-3-deep-think/) (Dec 4, 2025)

---

## Fast / Speed Model: **Gemini 3 Flash**

- **Released:** December 17, 2025
- **API ID:** `gemini-3-flash-preview`
- **Description:** "Our most intelligent model built for speed" — combines frontier intelligence with superior search and grounding. Successor to Gemini 2.5 Flash.
- **Key strengths:** Speed + intelligence balance, search grounding, multimodal

### API Pricing (Paid Tier, per 1M tokens)
| | Standard |
|---|---|
| **Input** | $0.50 (text/image/video) / $1.00 (audio) |
| **Output** (incl. thinking) | $3.00 |
| **Context caching** | $0.05 (text/image/video) / $0.10 (audio) + $1.00/M tokens/hr storage |
| **Free tier** | ✅ Free of charge (rate-limited) |

- **Source:** [Google — "Gemini 3 Flash: Frontier intelligence built for speed"](https://blog.google/technology/google-deepmind/gemini-3-flash/) (Dec 17, 2025)

---

## Lightweight / Cost-Efficient Model: **Gemini 3.1 Flash Lite**

- **Released:** March 3, 2026
- **API ID:** `gemini-3.1-flash-lite-preview`
- **Description:** "Our most cost-efficient model" — optimised for high-volume agentic tasks, translation, and simple data processing. First-ever Gemini Flash-Lite model designed for cost-efficiency and speed.
- **Key use cases:** Enterprise scale, high-volume tasks, translation, simple data processing

### API Pricing (Paid Tier, per 1M tokens)
| | Standard |
|---|---|
| **Input** | $0.25 (text/image/video) / $0.50 (audio) |
| **Output** (incl. thinking) | $1.50 |
| **Context caching** | $0.025 (text/image/video) / $0.05 (audio) + $1.00/M tokens/hr storage |
| **Free tier** | ✅ Free of charge (rate-limited) |

- **Source:** [Google — "Gemini 3.1 Flash-Lite: Built for intelligence at scale"](https://blog.google/technology/google-deepmind/gemini-3-1-flash-lite/) (Mar 3, 2026); [WinBuzzer](https://winbuzzer.com/2026/03/03/google-launches-gemini-3-1-flash-lite-for-enterprise-scale/) (Mar 3, 2026)

---

## Image Generation Models

### **Gemini 3 Pro Image** (aka "Nano Banana Pro" 🍌)
- **Released:** November 20, 2025
- **API ID:** `gemini-3-pro-image-preview`
- **Description:** Native image generation model, optimised for speed, flexibility, and contextual understanding. Improved text rendering and world knowledge over the original Nano Banana.
- **Pricing (Paid):** Text I/O priced same as Gemini 3.1 Pro; Image output at $120/M tokens (~$0.134 per 1K/2K image, ~$0.24 per 4K)
- **Free tier:** ❌ Not available

### **Gemini 3.1 Flash Image** (aka "Nano Banana 2" 🍌)
- **Released:** February 26, 2026
- **API ID:** `gemini-3.1-flash-image-preview`
- **Description:** Faster image generation built on Flash architecture. Better instruction following and text rendering. Designed for speed and efficiency — quick, interactive responses and high throughput.
- **Pricing (Paid):** Input $0.50 (text/image); Output $3 (text/thinking), $60/M tokens for images (~$0.045 per 0.5K, ~$0.067 per 1K, ~$0.101 per 2K, ~$0.151 per 4K)
- **Free tier:** ❌ Not available

### **Imagen 4**
- **API IDs:** `imagen-4.0-generate-001`, `imagen-4.0-ultra-generate-001`, `imagen-4.0-fast-generate-001`
- **Description:** Google's latest dedicated image generation model (non-Gemini). Significantly better text rendering and overall image quality.
- **Pricing:** Imagen 4 Fast: $0.02/image | Standard: $0.04/image | Ultra: $0.06/image
- **Free tier:** ❌ Not available

### Nano Banana History
- "Nano Banana" was the codename used during secret public testing on Arena (first appeared Aug 12, 2025). Named after nicknames for Naina Raisinghani, PM at Google DeepMind.
- **Nano Banana** = Gemini 2.5 Flash Image (Aug 26, 2025)
- **Nano Banana Pro** = Gemini 3 Pro Image (Nov 20, 2025)
- **Nano Banana 2** = Gemini 3.1 Flash Image (Feb 26, 2026)

---

## Video Generation: **Veo 3.1**

- **API IDs:** `veo-3.1-generate-preview`, `veo-3.1-fast-generate-preview`
- **Description:** Latest video generation model with audio
- **Pricing:** Standard: $0.40/sec (720p/1080p), $0.60/sec (4K) | Fast: $0.15/sec (720p/1080p), $0.35/sec (4K)
- Also available: **Veo 3** (stable, $0.40/sec standard, $0.15/sec fast) and **Veo 2** ($0.35/sec)

---

## Other Notable Models (Still Available)

| Model | API ID | Status | Notes |
|---|---|---|---|
| **Gemini 2.5 Pro** | `gemini-2.5-pro` | Stable (GA) | Excellent coding & reasoning. Input: $1.25-$2.50/M, Output: $10-$15/M |
| **Gemini 2.5 Flash** | `gemini-2.5-flash` | Stable (GA) | Hybrid reasoning, 1M context, thinking budgets. Input: $0.30/M, Output: $2.50/M |
| **Gemini 2.5 Flash-Lite** | `gemini-2.5-flash-lite` | Stable (GA) | Smallest, most cost-effective. Input: $0.10/M, Output: $0.40/M |
| **Gemini 2.0 Flash** | `gemini-2.0-flash` | Available | Previous generation |
| **Gemini 2.0 Flash-Lite** | `gemini-2.0-flash-lite` | ⚠️ Deprecated (shutdown June 1, 2026) | Migrate to newer models |
| **Lyria** | `lyria-realtime-exp` | Experimental | Music generation |
| **Gemini Robotics** | `gemini-robotics-er-1.5-preview` | Preview | Vision-language-action model (announced Mar 2025) |
| **Gemini 2.5 Computer Use** | `gemini-2.5-computer-use-preview-10-2025` | Preview | Computer use / agent |
| **Deep Research Pro** | `deep-research-pro-preview-12-2025` | Preview | Deep research capability |

---

## Gemini API Pricing Tiers

### Free Tier
- Available for developers and small projects
- Limited access to certain models (3 Flash, 3.1 Flash Lite, 2.5 Flash, 2.5 Pro — but NOT 3.1 Pro or image models)
- Free input & output tokens (rate-limited)
- Google AI Studio access
- ⚠️ Content used to improve Google's products

### Paid Tier (Pay-as-you-go)
- Higher rate limits for production deployments
- Context caching, Batch API
- Access to Google's most advanced models (including 3.1 Pro, image models)
- ✅ Content NOT used to improve Google's products
- Grounding with Google Search: 5,000 prompts/month free, then $14/1,000 queries (for 3.x models)
- Grounding with Google Maps: varies by model

### Enterprise Tier
- Custom needs, dedicated support
- Advanced security & compliance
- Provisioned throughput
- Volume-based discounts
- Contact Sales

### Gemini Consumer App (chatbot)
- **Free:** Access to Gemini (basic models)
- **Gemini Advanced (AI Premium):** $19.99/month via Google One — access to most capable models including 3 Deep Think, 3.1 Pro
- Includes 2TB Google One storage

---

## Quick Model Selection Guide

| Need | Best Model | Cost (per 1M output tokens) |
|---|---|---|
| Maximum intelligence / complex tasks | Gemini 3.1 Pro | $12.00-$18.00 |
| Deep reasoning / math / science | Gemini 3 Deep Think | (via Gemini Advanced app) |
| Speed + intelligence balance | Gemini 3 Flash | $3.00 |
| High volume / cost efficiency | Gemini 3.1 Flash Lite | $1.50 |
| Image generation (quality) | Gemini 3 Pro Image / Imagen 4 Ultra | ~$0.13-$0.24/img / $0.06/img |
| Image generation (speed) | Gemini 3.1 Flash Image / Imagen 4 Fast | ~$0.045-$0.15/img / $0.02/img |
| Video generation | Veo 3.1 | $0.15-$0.60/sec |

---

## Key Timeline

| Date | Event |
|---|---|
| Nov 18, 2025 | Gemini 3 Pro and 3 Deep Think announced |
| Nov 20, 2025 | Nano Banana Pro (Gemini 3 Pro Image) released |
| Dec 4, 2025 | 3 Deep Think rolled out to Ultra subscribers |
| Dec 17, 2025 | Gemini 3 Flash released |
| Feb 19, 2026 | **Gemini 3.1 Pro** released |
| Feb 26, 2026 | Nano Banana 2 (Gemini 3.1 Flash Image) released |
| Mar 3, 2026 | **Gemini 3.1 Flash Lite** released |
| Mar 9, 2026 | Gemini 3 Pro deprecated |

---

*Sources: [Wikipedia — Gemini (language model)](https://en.wikipedia.org/wiki/Gemini_(language_model)), [Google AI Developer Pricing](https://ai.google.dev/pricing), [Google Keyword Blog](https://blog.google/technology/google-deepmind/)*

*Researched: March 17, 2026*
