# SCANBUILD VISUAL IDENTITY STANDARD

**Document ID:** SB-KB-02b — canonical file name per Foundation §37: `02_SCANBUILD_VISUAL_IDENTITY_STANDARD.md`
**Status:** APPROVED v1.0 — promoted from DRAFT v0.2 by James (ScanBuild1), 16 October 2026. This is the master visual identity standard for the ScanBuild ecosystem and supersedes all prior drafts and ad-hoc styling.
**v0.2 change:** added document-interior system (§11.1) from the completed Towers Business Plan PDFs (Memorandum 27 pp + Investors Edition 29 pp, Oct 2026); added data-semantics colour rule; new open decisions (print page size, editable masters, cover date check).
**Date:** 16 October 2026
**Primary entity:** ScanBuild1
**Related entities:** Scan4D / ScanBuild IP (future UI tokens); PHD / House Doctor (out of scope — separate brand)
**Authority chain:** `00_SCANBUILD_MASTER_CONTEXT.md` → `02_SCANBUILD_BRAND_FOUNDATION (1).md` (V0.2, canonical strategy) → this draft
**Provenance of tokens:**
- CONFIRMED — live production CSS from `towers-passport.scanbuild1.com.au` (css/tp.css), retrieved 16 Oct 2026
- CONFIRMED — Towers Passport Developer Partner Presentation PDF (24 pp, 16:9) and Investor Memorandum Oct 2026 PDF (14 pp, A4): embedded-font and sampled-colour analysis
- CONFIRMED — Towers Business Plan PDFs supplied 16 Oct 2026 (Memorandum ed., 27 pp; Investors ed., 29 pp; US Letter): full-page colour sampling across all 56 pages — palette identical to system; layout analysis of cover, section dividers, tables, charts, KPI cards
- CONFIRMED — 8 logo candidate PNGs supplied to hub: exact colour extraction
- RECOMMENDATION / PROVISIONAL — all usage rules, scales and recipes below

---

## 1. PURPOSE & SCOPE

This system is the single reference for all Genspark content creation: decks, business plans, reports, marketing, landing pages, social, email and video direction. It translates the approved brand strategy (construction credibility + spatial intelligence + future-facing technology + practical commercial usefulness) into enforceable visual tokens and rules.

- **Governs:** ScanBuild / ScanBuild1 external identity and collateral.
- **Prepared for:** Scan4D UI inherits the digital-product tokens (colour signals, mono labels, status colours) but must not present platform capability as current ScanBuild1 operations.
- **Does not govern:** PHD / House Doctor (separate QBCC-licensed entity — distinct brand, no shared mark).
- Per the canonical foundation: visual identity is **provisional until approved** (Foundation §5, §38, §40). This draft is the vehicle for that approval.

## 2. DESIGN PRINCIPLES

1. **Evidence first** — every visual should imply a real building was measured (Foundation: "Built on Evidence").
2. **Construction credibility + spatial intelligence** — raw architectural realism (concrete, sites, towers) fused with point-cloud/mesh/scan overlays; never pure sci-fi.
3. **Dark-canvas authority, yellow signal** — deep navy carries the brand voice; yellow is reserved as a precise accent (scan lines, stats, CTAs, footers), never as background fill.
4. **Futuristic, not science fiction** — no HUD clutter, no crypto/neon clichés (Foundation §4, §31).
5. **Reproducible, not flattened** — all identity elements must exist as independent reusable assets transferable to Canva and GoHighLevel (Foundation §21, §28).
6. **Legible everywhere** — report page to vehicle to favicon; contrast AA minimum (verified pairs in §3).

## 3. COLOUR SYSTEM

### 3.1 Core tokens (CONFIRMED — live landing CSS)

| Token | Hex | RGB | Role |
|---|---|---|---|
| `--ground` | `#011A40` | 1, 26, 64 | Primary dark canvas (web hero, deck backgrounds, dark panels) |
| `--ground-2` | `#02224F` | 2, 34, 79 | Elevated dark surface / section alternation |
| `--cobalt` | `#004AAD` | 0, 74, 173 | Brand blue — primary accent on light backgrounds |
| `--deep` | `#003070` | 0, 48, 112 | Deep blue — gradients, pressed states |
| `--surge` | `#1A7CFF` | 26, 124, 255 | Vivid blue — links, interactive emphasis (AA-Large on ground only) |
| `--sky` | `#6CA7F9` | 108, 167, 249 | Sky blue — secondary data series, mesh lines, icons |
| `--ice` | `#A8CBFD` | 168, 203, 253 | Ice blue — tags, subtle highlights on dark |
| `--yellow` | `#F2CB07` | 242, 203, 7 | Signal yellow — scan lines, stats, CTA, footer bars (AAA on ground) |
| `--azure` | `#253238` | 37, 50, 56 | Charcoal — headings on light backgrounds |
| `--slate` | `#5B7B8A` | 91, 123, 138 | Slate — secondary text/icons on light (AA-Large; darken 10% for small body text) |
| `--text-2` | `#B7C6CE` | 183, 198, 206 | Secondary text on dark (AAA on ground) |
| `--mist` | `#F4F7F8` | 244, 247, 248 | Light canvas — report pages, light sections |

**Extended in-use tones (CONFIRMED in production):** `#011638` `#0B1A2E` `#01143A` `#0A1530` `#022150` (navy depth ramp) · `#0A5FD6` (mid blue) · `#FFF3A6` (pale yellow highlight) · `#8FA6B2` `#6E8793` (cool greys).

**Document-family note (PROVISIONAL):** the deck/memo PDFs sample as `#081838` navy + `#F8C808` yellow — the same family rendered through PDF compression. RECOMMENDATION: consolidate on the CSS tokens above as canonical and treat `#081838`/`#F8C808` as print/render variants.

### 3.2 Verified contrast (CALCULATED, WCAG 2.1)

| Pair | Ratio | Grade |
|---|---|---|
| Yellow `#F2CB07` on Ground `#011A40` | 10.89 | AAA |
| White on Ground | 17.17 | AAA |
| Text-2 `#B7C6CE` on Ground | 9.80 | AAA |
| Ice `#A8CBFD` on Ground | 10.32 | AAA |
| Sky `#6CA7F9` on Ground | 6.98 | AA |
| Cobalt `#004AAD` on Mist `#F4F7F8` | 7.55 | AAA |
| Azure `#253238` on Mist | 12.25 | AAA |
| Ground on Yellow (inverted) | 10.89 | AAA |
| Surge `#1A7CFF` on Ground | 4.39 | AA-Large only |
| Slate `#5B7B8A` on Mist | 4.20 | AA-Large only |

Rules: body text on dark = White or Text-2; **never** Surge or Slate for small body text; yellow only for large/short text or non-text accents on dark.

### 3.3 Environment behaviour

- **Dark-first digital** (web, decks, screens): Ground canvas, navy ramps, blue mesh, yellow signal.
- **Light print** (reports, proposals): Mist canvas, Azure headings, Cobalt accents, yellow used as thin rules/highlights only — never large yellow fields on paper.
- **Vehicles/PPE:** Ground + Cobalt body, Yellow safety-graphic band. CMYK/Pantone conversions NOT yet verified — required before print approval.

## 4. TYPOGRAPHY

**CONFIRMED live stack** (Google Fonts, loaded by the production landing page):

| Role | Face | Weights | Use |
|---|---|---|---|
| Display / headline | **Chakra Petch** | 500, 600, 700 (+ italics) | Headlines, stage labels, deck titles. Squared, technical, engineered. Fallback: Oxanium, then sans-serif |
| Body / long-form | **IBM Plex Sans** | 300, 400, 500 | Reports, web body, captions. Fallback: system-ui |
| Technical / data | **IBM Plex Mono** | 400, 500 | Tracked uppercase labels, stage trackers, dimensions, stats, form text |

**Type treatments (CONFIRMED from references):** uppercase + wide letter-spacing for category labels and stage trackers; sentence case for headlines ("Hand over a building that knows itself."); bold lead-in phrases followed by regular-weight body; yellow reserved for label-level type and key stats, white for headlines.

**Document-family note (DECISION REQUIRED):** the Investor Memorandum also embeds Aileron and Academy (plus Chakra Petch Light Italic). RECOMMENDATION: consolidate all documents on the live stack above; retire Aileron/Academy unless there is a print-licensing reason.

**Licensing check (Foundation §22):** all three faces are Google Fonts (open licence) — web and Canva use is expected to be safe, but confirm Canva availability and embed in exported PDFs before final approval.

**Provisional scale:** Deck headline 36–40 pt / deck body 14–16 pt / label 10–12 pt tracked +8–12%. Web: display clamp 40–72 px, H2 28–36 px, body 16–18 px, mono label 12–13 px.

## 5. LOGO SYSTEM

### 5.1 Candidate inventory (CONFIRMED — supplied PNGs, exact sampled colours)

| File | Observation (from hub record + extraction) |
|---|---|
| `1.png` | Isometric blue cube grid, one frosted/translucent cube; SCANBUILD wordmark (SCAN royal blue / BUILD charcoal, gold hook accent); "Built on Evidence" tagline in yellow script. Palette `#1C4C9C` `#144CA4`. Analysis notes: strong BIM/proptech look; script tagline tension noted vs technical type |
| `2.png` | Glossy blue cube variant of the same system; tagline "Built on Evidence" |
| `4.png` | Angular SCANBUILD lettering, blue + dark grey, yellow accent (`#0C54B4` family) — flat, technical |
| `5.png` | Glossy blue 3D cube cluster, one translucent ice-blue cube (mark only) |
| `6.png` | Grey monogram + blue geometric mark — restrained, corporate |
| `7.png` | Futuristic abstract grey emblem, blue accents, yellow details (dark styling) |
| `8.png` | Bold grey monogram + blue/black wordmark, yellow accents |
| `9.png` | Stylised emblem, yellow accents on deep navy `#043474` `#F4CC04` |

### 5.2 System requirements (Foundation §29 — CONFIRMED standard)

Approved system must include: primary lockup; horizontal variant; compact/stacked; symbol; wordmark; one-colour; reversed/white; favicon; social avatar. Legible at small size; field-ready.

### 5.3 Provisional direction (RECOMMENDATION — DECISION REQUIRED)

The cube-grid mark (family of `1/2/5.png`) is the most distinctive and strategy-aligned: it reads as a building being voxelised into structured data, it owns the "one element different" idea (frosted cube = the captured/transformed building), and it scales. Suggested refinements before approval: replace the script tagline with Chakra Petch tracked uppercase; produce flat one-colour and reversed versions; test at 24 px favicon scale.

**Misuse rules (PROVISIONAL):** no recolouring outside tokens; no stretching; minimum clear space = height of one cube unit; dark backgrounds use reversed version with yellow accents intact.

## 6. LAYOUT & GRID

- **Deck (16:9, 1440×810):** asymmetric split — text column left, full-bleed imagery right; ~50/50 is the house style. Thin yellow bar anchors the bottom edge of every slide (CONFIRMED across deck + memo covers). Page number bottom-right.
- **A4 documents:** dark cover (same split logic), light interior pages (Mist canvas), yellow rule elements carried through.
- **Web (CONFIRMED from tp.css):** content max-width `--max: 1240px`; section rhythm 72/120/150 px; padding 20/40 px; button height scale 44–56 px.
- Faint wireframe/mesh texture on dark canvases (CONFIRMED motif).

## 7. GRAPHIC DEVICES (the ownable grammar)

1. **Stage tracker** — tracked uppercase mono in yellow: `STAGE 3 · CAPTURED`; process sequence `FORM → BUILT → CAPTURED` with arrows (CONFIRMED).
2. **Scan line** — horizontal yellow beam crossing a building/render (CONFIRMED on cover, memo, deck).
3. **Wireframe mesh / point cloud** — subtle blue triangular mesh and glowing nodes on navy (CONFIRMED).
4. **Square bullets** — small solid yellow squares as list markers (CONFIRMED).
5. **Yellow footer bar / rule** — 4–8 px anchor line (CONFIRMED).
6. **Physical → digital split** — one image divided by a glowing yellow vertical: raw/concrete vs finished/staged, or building vs holographic twin (CONFIRMED).
7. **Gradient grammar** (CONFIRMED): cobalt/sky diagonals at 110–135°; navy fades `#011638 → rgba(1,22,56,.55)`; pale-yellow edge glow `rgba(242,203,7,.65)`.
8. **Dimensional annotation** — measurement ticks, coordinates, arrows in mono type (Foundation §30 direction; use sparingly).

Rule: devices are information-bearing first. One hero device per composition; never stack all eight.

## 8. IMAGERY

- **Hero register:** real towers/sites at night, coastal city context, warm interior lighting against navy tech overlays (CONFIRMED cover style).
- **The money shot:** physical building dematerialising into cubes/particles with a yellow scan line — the physical-to-digital transformation (CONFIRMED cover + skill guidance).
- **Contrast pairing:** raw concrete/unfurnished vs warm staged interiors (golden-hour) — proof of the transformation value (CONFIRMED deck p09).
- **People:** field operators in PPE on real sites; faces real, not stocky; privacy/client permissions and case-study approvals respected before publication.
- **Grade:** navy shadows, cyan-blue data overlays, warm practical lights; never full-neon.

## 9. ICONOGRAPHY & DATA VISUALISATION

- Icons: 1.5–2 px stroke, squared terminals, geometric construction; outline default, filled only for active states. IBM Plex ecosystem or custom set aligned to Chakra Petch geometry.
- Charts on dark: Ground canvas, series in Sky/Ice/Surge, single yellow series reserved for THE number. Labels in Plex Mono. Grid lines `--line` opacity.
- Charts on light: Mist canvas, Cobalt/Slate series, yellow highlight only.
- Diagrams: building-first (plans, sections, towers), data second — never abstract particles.

## 10. MOTION & INTERACTION

Principles (from CONFIRMED easings + skill guidance): **scan** (yellow line sweep), **reveal** (content rises with `--ease-out` cubic-bezier(.16,1,.3,1)), **register** (elements snap to grid), **layer** (mesh fades under content). Micro-interactions use `--ease-io` cubic-bezier(.65,0,.35,1). No gratuitous parallax/neon pulsing. Hover states: Surge blue or yellow underline; 150–250 ms.

## 11. APPLICATION RECIPES

- **Genspark decks:** "16:9 dark presentation. Deep navy `#011A40` background with faint blue wireframe mesh. Left text column: yellow tracked mono stage label, large white Chakra Petch headline, bold-lead-in bullets with yellow square markers. Right: full-bleed architectural render with blue digital-twin overlay and one yellow scan line. Thin yellow bar along bottom edge. Fonts: Chakra Petch / IBM Plex Sans / IBM Plex Mono."
- **Documents/business plans (PDF):** A4. Dark navy cover in the split style + yellow bottom bar; interior pages on `#F4F7F8`, Azure headings in Chakra Petch, Plex Sans body, yellow thin rules, mono data labels.
- **Web/GHL:** use `scanbuild_design_tokens.css` as-is; Ground hero sections, Mist content sections; Cobalt CTAs on light, Yellow CTA on dark (Ground text on yellow).
- **Social:** dark tile, one device, yellow stat in mono, minimal.
- **Video:** open with scan-line over building; navy grade; yellow transitions; end-card on Ground with reversed logo.

### 11.1 Document interiors — business plans (CONFIRMED from Towers Business Plan PDFs, Oct 2026)

The completed business plans establish the house style for long-form stakeholder documents. Light pages on white/Mist; dark navy pages reserved for cover and section dividers.

**Page furniture:**
- **Running header:** left — `scanbuild · TOWERS PASSPORT · BUSINESS PLAN & INVESTOR REFERENCE` in muted grey; right — section marker `05 · BUSINESS MODEL`.
- **Section tag:** small solid-yellow box holding the section number, beside an uppercase tracked section title.
- **Footer:** logo bottom-left; centred compliance line (`CONFIDENTIAL · STAKEHOLDER REFERENCE · NOT AN INVESTMENT OFFER`); page number bottom-right; solid yellow stripe across the bottom edge (same anchor bar as decks).

**Headline pattern:** bold Azure/Ground-navy headline with the key claim emphasised — italic secondary phrase or yellow highlight bar under the number/claim (e.g. "Profitable from Year 1, scaling to **$12.1m in Year 5**."). Subhead in regular weight names the assumption base.

**Table system:** solid yellow header bar with bold uppercase dark column labels; alternating white / `#F4F5F7` rows; key rows (totals, margins) as solid navy bands with white text; outlined `ESTIMATED` badge where values are modelled; grey assumption footnotes below.

**Data-semantics colour rule (NEW — CONFIRMED in charts and KPI cards):**
- **Yellow = revenue / gross / upside** (gross turnover bars, revenue KPI card, opportunity callouts).
- **Navy/Cobalt = profit / net / bottom-line** (NPAT bars, profit KPI cards, total rows).
This two-tone data story (volume vs bottom line) is now standard for all ScanBuild financial visuals.

**Chart system:** grouped bars with exact value labels above each bar; thin grey gridlines `#E5E7EB`; year + driver (e.g. "new sites") beneath; legend markers in the two semantic colours.

**KPI card row:** 4-up horizontal cards mixing navy, cobalt, yellow and charcoal fills — white numerals, small labels; yellow card reserved for the single most important upside figure.

**Callout banner:** wide yellow band for offers/programs (e.g. FOUNDING PILOT PROGRAM) with rounded pill badge for target dates.

**Dark section dividers:** full-navy pages with mesh texture between major parts (CONFIRMED pp. 11, 25, 27 region).

**Document differences note:** Memorandum (27 pp) vs Investors Edition (29 pp) share one design system with audience-specific content; treat them as one template family with content variants.

## 12. EXCLUSIONS (Foundation §31 — CONFIRMED standard)

No: generic house-roof or camera icons; standard 3D cube used generically; circuit-board brains; generic AI sparks; blockchain networks; globe clichés; untransformed stock blueprints; excessive neon; crypto/metaverse aesthetics; sci-fi HUDs; surveillance/military imagery; blue-purple AI gradients.

## 13. GOVERNANCE

- This file is **APPROVED v1.0** (promoted 16 Oct 2026) — the master visual identity standard. Per Foundation §38, approved material may now enter the Canva Brand Kit, GoHighLevel environment and official templates. New creative work must conform to this standard or be flagged as a proposed amendment.
- On approval, promote to canonical `02_SCANBUILD_VISUAL_IDENTITY_STANDARD.md` (Foundation §37) and update the Decision Register.
- Handoff sequence (Foundation §28): Genspark concept → approved decision → master assets → Canva Brand Kit → GHL/templates.
- Open decisions (Foundation §40 + this draft): logo selection; tagline treatment (script vs technical typeface); palette formal approval; consolidation of memo fonts (Aileron/Academy); CMYK/Pantone print values; trademark/licensing checks; Scan4D sub-mark relationship.
- **Print page size (NEW):** hub memo is A4; the 2026 business plans exported at US Letter. RECOMMENDATION: standardise Australian stakeholder documents on A4 and set the export template accordingly.
- **Editable masters (NEW):** the business-plan PDFs contain no embedded fonts or extractable text — type is outlined, so the PDFs are final-art only. RECOMMENDATION: retain the editable source files (design tool project) as the master template so the document system stays reproducible per Foundation §21.
- **Cover date check (NEW):** the business-plan cover is read as "REVISION 2.0 · OCTOBER 2024" — the hub file names say Oct 2026. Verify which is correct and correct the master if it is a typo (flagged, not asserted).

**Approval record:** Token set, typography stack, layout system, graphic devices, imagery direction, document-interior system and exclusions APPROVED by James (ScanBuild1) — 16 October 2026. Remaining tracked open items (do not block day-to-day use): final logo selection (cube-grid family recommended provisionally), script-vs-technical tagline treatment, CMYK/Pantone print values, trademark/licensing checks, Scan4D sub-mark relationship, business-plan cover date verification ("OCTOBER 2024" vs Oct 2026).
