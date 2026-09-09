---
name: eide-bailly-brand
description: |
  Apply Eide Bailly's official brand standards — approved colors, typography, logo files, layout, and voice — to any document, deck, or written deliverable created for Eide Bailly by anyone on the team. Use whenever creating or formatting a Word document (.docx), PowerPoint (.pptx), PDF, proposal, SOW, report, one-pager, or any client-facing or internal Eide Bailly deliverable. Trigger phrases include "brand this", "make it on-brand", "apply our brand", "add the Eide Bailly logo", "use our colors and fonts", and "follow the brand guidelines". Provides exact hex colors, the approved font pairing (Segoe UI / Calibri), embed-ready logo PNGs, layout rules, and voice guidance. Do NOT use for third-party or client-owned branding, for plain-text chat replies or unformatted emails, or for redesigning, recreating, or recoloring the logo.
cowork:
  category: writing
  icon: PaintBrush
  pluginTitleId: T_f880cc4d-38a5-55cb-86fb-7229585c4b82
  publishedAt: "2026-08-03T15:54:39Z"
---

# Eide Bailly Brand Guidelines

Firm-wide brand skill — apply the same standards for whoever is creating the deliverable. The **core rules below cover almost every document and deck.** For deeper detail (full color palette and pairings, per-element font weights, detailed logo placement and don'ts, per-format layout, full voice guidance, firm boilerplate), read [references/brand-guidelines-full.md](references/brand-guidelines-full.md) — only when you need it.

## When to Use This Skill

Apply automatically, without being asked, whenever building or formatting an Eide Bailly deliverable:

- Creating or restyling a **Word doc (.docx)**, **PowerPoint (.pptx)**, or **PDF** in an Eide Bailly context
- A **proposal, SOW, report, one-pager, client deliverable, or internal firm document**
- Any request to **"brand this," "make it on-brand," "apply our brand/colors/fonts," "add the Eide Bailly logo,"** or **"follow brand guidelines"**

When in doubt for an Eide Bailly document, apply it — brand consistency matters on every deliverable, quick ones included.

## When NOT to Use

- **Third-party, client-owned, or co-branded materials** — follow the other party's guidelines, not Eide Bailly's, unless told to co-brand.
- **Plain-text chat answers or unformatted emails** with no document/slide output — there's nothing to style.
- **Logo redesign, recreation, recoloring, or "make a new logo"** — never do this. Use only the provided files, exactly as supplied.
- **Non-Eide-Bailly personal documents.**

## Quick Reference (the core rules)

Apply these automatically on every Eide Bailly deliverable:

**Colors** → Black Blue **#0E172D** for body text and headings; EB Blue **#1E31B6** for accents/headers; Stone White **#F6F6F6** for backgrounds; Vivid Green **#6EDC82** as a sparing accent only (one element per layout, max). Full palette + approved pairings are in the reference.
**Fonts** → **Segoe UI Semibold** for headings; **Calibri Regular** for body. Name them explicitly in the file (Office applies them on open); never substitute Times New Roman, Arial, or Helvetica.
**Logo** → Embed the approved **PNG** files (table below); pick the colorway by background; never modify, rotate, recolor, stretch, or use the mark alone. Minimum 1" wide.
**Voice** → Proactive, business-savvy, genuine, collaborative, trustworthy — direct, jargon-free, no buzzwords ("unlock," "boost") or hokey puns.
**Formal legal name** → Only on documents with signatory lines (SOWs, sign-offs, engagement letters, invoices), the formal entity for advisory / Technology Consulting work is **Eide Bailly Advisory LLC** (**Eide Bailly LLP** only for audit & attest). Everywhere else, just use "Eide Bailly."

## Formal Legal Entity Name

The Eide Bailly **brand, logo, colors, voice, and teams are unchanged.** The one thing to get right is the **formal legal entity name**, and it only matters where a document actually names the signing/contracting party.

- **On documents with signatory lines** — SOWs, sign-offs / acceptance forms, engagement letters, order forms, invoices — the formal entity for advisory / Technology Consulting work is **Eide Bailly Advisory LLC**. Use it wherever the legal name and signature block appear.
- **Eide Bailly LLP** is the CPA / audit & attest entity — use it as the formal name **only** on audit & attest signatory documents.
- **Everywhere else** — slides, reports, proposals without a signature block, one-pagers, emails, general body copy — just use the brand name **"Eide Bailly."** No legal suffix needed.
- Confirm exact signature-block wording with Legal/Marketing rather than inventing it; use a placeholder like `[confirm EB Advisory LLC signature block]` if it isn't supplied.

## How to Apply (mechanics for the document builder)

Pairs with the document-building tool for each format — `docx`, `pptx`, or `pdf` — which produces the file while this skill supplies the brand rules.

1. **Colors** — Set text/heading/background/accent colors explicitly with the hex values above; don't rely on template defaults.
2. **Fonts** — Name **Segoe UI** (headings) and **Calibri** (body) explicitly. Never silently substitute another font.
3. **Logos — embed the PNGs.** Word/PowerPoint/PDF embed **PNG** (not EPS). Use the `*.png` files in `assets/`, choosing the colorway by background:
   - Light/white background → the **Black Blue** version
   - Dark/blue background → the **Stone White** version
   - Limited vertical space (headers, footers, inline) → the **Secondary** (horizontal) version
4. **Hand-off** — Once colors, fonts, and logo are set, let the `docx`/`pptx`/`pdf` skill generate the file, then run the checklist before delivering.

### Approved logo files (in `assets/`)

Embed-ready — use these in .docx / .pptx / .pdf:

| File | Lockup | Colorway | Use on | Notes |
|---|---|---|---|---|
| `EB-Logo-Primary-BlackBlue.png` | Primary (stacked) | Black Blue | Light backgrounds | 1501×682, transparent — highest-res; default logo |
| `EB-Logo-Primary-StoneWhite.png` | Primary (stacked) | Stone White | Dark/blue backgrounds | 300×134, transparent — best under ~3" wide |
| `EB-Logo-Secondary-BlackBlue.png` | Secondary (horizontal) | Black Blue | Light backgrounds | 300×52, transparent — headers/footers/inline |
| `EB-Logo-Secondary-StoneWhite.png` | Secondary (horizontal) | Stone White | Dark/blue backgrounds | 300×52, transparent — headers/footers/inline |

Vector masters (EPS) are **not** bundled — Copilot skill folders only accept PNG (not EPS/WEBP). For a larger/print size, get the vector master from Marketing and export a PNG; never stretch a small PNG up past its native size.

## Guardrails

- **Never fabricate firm facts.** Use the firm boilerplate (in the reference) verbatim; don't invent statistics, rankings, office counts, awards, or claims. Missing fact → placeholder for the author to confirm.
- **Formal legal name.** On signatory documents (SOWs, sign-offs, engagement letters, invoices), name **Eide Bailly Advisory LLC** for advisory / Technology Consulting work (Eide Bailly LLP only for audit & attest). Everywhere else, just "Eide Bailly." Confirm exact wording with Legal/Marketing rather than inventing it.
- **Fonts unavailable in the render environment?** Still specify Segoe UI / Calibri by name (Office applies them on open). Never swap in Times/Arial/Helvetica.
- **Logo missing or only EPS available?** Embed only the listed PNG files; never embed EPS in Office, and never recreate, recolor, or stretch the mark. If the exact colorway isn't present, choose by background contrast and note the choice.
- **Color uncertainty?** If a pairing isn't in the approved list, default to Black Blue + Stone White. Vivid Green stays an accent — one element per layout, max.
- **Don't over-apply.** Style Eide Bailly deliverables only — don't impose EB branding on client-owned or third-party documents.
- **Confirm before finalizing** using the checklist below.

## Checklist Before Finalizing Any Document

- [ ] Colors from the approved palette only
- [ ] Fonts: Segoe UI for headings, Calibri for body
- [ ] Logo embedded from an approved **PNG**, correct color version for the background, ≥ 1" wide with proper clearspace
- [ ] Vivid Green used sparingly as accent only (not a dominant color)
- [ ] Voice is proactive, direct, and jargon-free — no buzzwords or hokey puns
- [ ] Boilerplate/statistics used verbatim — nothing fabricated
- [ ] Signatory documents (SOWs, sign-offs, invoices) use the formal entity **Eide Bailly Advisory LLC** (Eide Bailly LLP only for audit & attest); everywhere else just "Eide Bailly"
