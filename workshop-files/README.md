# Workshop Demo Files

Source files for **Talk 2: Live AI Workshop — 5 Use Cases in 35 Minutes**.

These are the input files Ali uploads to Claude (or pastes into the chat) during the live demo.

---

## Files

| File | Use Case | What to Do |
|------|----------|------------|
| `use-case-1-financials.xlsx` | **Use Case 1: Financial Analysis** | Upload this file to Claude using the attachment icon. It's an intentionally messy 12-month P&L spreadsheet — inconsistent formatting, missing values, typos, a duplicate row, and a suspect COGS figure in August. The AI should clean it up, calculate metrics, and produce a board-ready summary. |
| `use-case-2-brief.docx` | **Use Case 2: Contract Drafting** | Upload this Word document to Claude. It's a one-page consulting engagement brief between Aether Technologies (client) and Enriched Solutions (consultant). Ask Claude to draft a full Professional Services Agreement from this brief. |
| `use-case-3-brand-brief.md` | **Use Case 3: Brand Identity** | Copy the contents of this file and paste into Claude's chat. It describes Aether Technologies' brand requirements — audience, personality, visual direction, competitors. Ask Claude to generate a logo and brand identity from this brief. |
| `use-case-5-business-idea.md` | **Use Case 5: Investor Pitch Deck** | Copy the contents of this file and paste into Claude's chat. It's a one-paragraph pitch for Aether Technologies. Ask Claude to create a 12-slide investor pitch deck from this brief. |

> **Use Case 4 (Market Research)** doesn't need a file — it's a research-from-scratch demo using Claude's web search.

---

## Intentional Messiness in the Excel File

The financials spreadsheet is deliberately messy to showcase AI's cleanup ability:

- **Mixed date formats:** `Jan-25`, `02/2025`, `March 2025`, `Aug 2025`, `November 2025`, `10/2025`
- **Inconsistent number formatting:** Some cells have `£` prefix as text, others are plain numbers
- **Missing values:** Revenue blank for May, several Operating Profit / Tax / Net Profit cells empty
- **Typos in headers:** "Marketng" (missing 'i'), "Miscellaneos" (missing 'u')
- **Duplicate row:** October appears twice (rows 11 and 14)
- **Suspicious data:** August COGS (£78,000) is ~82% of revenue — likely a data entry error
- **Incomplete calculations:** Only some rows have Operating Profit, Tax, and Net Profit filled in

---

_Generated 17 March 2026 by Ark Medicea, COO — Enriched Solutions_
