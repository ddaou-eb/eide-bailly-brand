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
**APS Disclosure** → Any external-facing material that describes the firm or its services (proposals, presentations, reports, event materials, etc.) generally needs the Alternative Practice Structure disclosure paragraph, verbatim from the reference — typically as a small-type footer or closing-page disclaimer. When in doubt, include it.

## Formal Legal Entity Name

The Eide Bailly **brand, logo, colors, voice, and teams are unchanged.** The one thing to get right is the **formal legal entity name**, and it only matters where a document actually names the signing/contracting party. This is separate from the APS Disclosure paragraph below, which applies more broadly.

- **On documents with signatory lines** — SOWs, sign-offs / acceptance forms, engagement letters, order forms, invoices — the formal entity for advisory / Technology Consulting work is **Eide Bailly Advisory LLC**. Use it wherever the legal name and signature block appear.
- **Eide Bailly LLP** is the CPA / audit & attest entity — use it as the formal name **only** on audit & attest signatory documents.
- **Everywhere else** — slides, reports, proposals without a signature block, one-pagers, emails, general body copy — just use the brand name **"Eide Bailly."** No legal suffix needed.

## APS Disclosure (Alternative Practice Structure)

Broader than the signature-block rule above: **any external-facing material that describes the firm or its services** — proposals, presentations, reports, event materials, advertising, articles — generally requires this disclosure paragraph. When in doubt, include it (typically as a small-type footer or on a closing page).

The verbatim approved text is in [references/brand-guidelines-full.md](references/brand-guidelines-full.md) — use it exactly as written, never paraphrased.

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

## Word (.docx) and PowerPoint (.pptx): override the styles, not just the text

Document builders ship default styles and a default theme (often red or rust headings and a serif body font such as Cambria). Setting a font or color on individual runs does not change those defaults, so headings, subtitles, tables, and any text without explicit formatting come out off-brand. Do all of the following:

1. **Normal style** → Calibri, Black Blue `#0E172D`.
2. **Title, Subtitle, Heading 1–3** → Segoe UI Semibold, Black Blue `#0E172D` or EB Blue `#1E31B6`. Set an explicit hex color. Never leave the builder's default heading color, and never use red or orange.
3. **Set every font slot** (`ascii`, `hAnsi`, `eastAsia`, `cs`) and remove theme font references (`asciiTheme`, `hAnsiTheme`). Set the theme's heading font to Segoe UI and body font to Calibri. In PowerPoint, do this in the slide master and theme.
4. **Tables** → Calibri Black Blue text. Borders, header fills, and any shading come from the palette only. Hyperlinks are EB Blue.
5. **No off-palette color anywhere**, including status or warning text. Say it in words instead of coloring it.
6. **Verify the saved file.** Unzip it and read `word/styles.xml` and `word/theme/theme1.xml` (`ppt/theme/` for decks). Every font must be Segoe UI or Calibri, and every color must be a palette hex. If Cambria, Times New Roman, Arial, or any other color appears, fix the styles and rebuild before delivering.

## Guardrails

- **Never fabricate firm facts.** Use the firm boilerplate (in the reference) verbatim; don't invent statistics, rankings, office counts, awards, or claims. Missing fact → placeholder for the author to confirm.
- **Formal legal name.** On signatory documents (SOWs, sign-offs, engagement letters, invoices), name **Eide Bailly Advisory LLC** for advisory / Technology Consulting work (Eide Bailly LLP only for audit & attest). Everywhere else, just "Eide Bailly."
- **APS Disclosure.** On external-facing material describing the firm/services (proposals, presentations, reports, etc.), include the APS Disclosure paragraph verbatim from the reference — don't paraphrase it, and don't skip it when in doubt.
- **Fonts unavailable in the render environment?** Still specify Segoe UI / Calibri by name (Office applies them on open). Never swap in Times/Arial/Helvetica.
- **Logo missing or only EPS available?** Embed only the listed PNG files; never embed EPS in Office, and never recreate, recolor, or stretch the mark. If the exact colorway isn't present, choose by background contrast and note the choice.
- **Color uncertainty?** If a pairing isn't in the approved list, default to Black Blue + Stone White. Vivid Green stays an accent — one element per layout, max.
- **Don't over-apply.** Style Eide Bailly deliverables only — don't impose EB branding on client-owned or third-party documents.
- **Confirm before finalizing** using the checklist below.

## Checklist Before Finalizing Any Document

- [ ] Colors from the approved palette only
- [ ] Fonts: Segoe UI for headings, Calibri for body
- [ ] Built-in styles and theme overridden (Normal, Title, Subtitle, Headings, tables), and the saved file's `styles.xml` and theme checked: no serif fonts, no red or other off-palette colors
- [ ] Logo embedded from an approved **PNG**, correct color version for the background, ≥ 1" wide with proper clearspace
- [ ] Vivid Green used sparingly as accent only (not a dominant color)
- [ ] Voice is proactive, direct, and jargon-free — no buzzwords or hokey puns
- [ ] Boilerplate/statistics used verbatim — nothing fabricated
- [ ] Signatory documents (SOWs, sign-offs, invoices) use the formal entity **Eide Bailly Advisory LLC** (Eide Bailly LLP only for audit & attest); everywhere else just "Eide Bailly"
- [ ] External-facing materials (proposals, presentations, reports) include the APS Disclosure paragraph verbatim
