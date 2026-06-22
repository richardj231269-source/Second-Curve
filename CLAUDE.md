# Second Curve — Claude Handoff

## Project
Static HTML website for Richard Jones's strategic advisory practice, Second Curve.
**Do not publish yet** — UWV benefit situation. Deadline: World of Coffee Brussels, 26–28 June 2026.

## Folder & repo
- Local: `C:\Users\richa\Second Curve`
- GitHub: `github.com/richardj231269-source/Second-Curve` (branch: `main`)
- Preview: double-click `index.html` in File Explorer (do not rely on Claude Code preview panel — it locks to the session's starting directory)

## Files
| File | Purpose |
|---|---|
| `index.html` | Primary design — warm cream, EB Garamond + DM Sans |
| `index-v2.html` | Alternative design — dark/architectural, Fraunces + Space Grotesk |
| `wordmark-full.svg` | Wordmark with horizontal rule + "STRATEGIC ADVISORY" (nav + footer) |
| `wordmark-transparent.svg` | Wordmark only, no rule/subtext (available if needed) |
| `images/richard-jones.jpeg` | Portrait — hero right column + about section |
| `images/shadow-light.jpg` | Geometric amber blinds — thesis section background |
| `images/window-light.jpg` | Light through window — Hesitation Gap section background |

## Brand — LOCKED (never change without flagging)
- **Colours:** Warm white `#F7F4EF`, Cream `#F0EDE7`, Charcoal `#2A2A27`, Amber `#B8851E`, Ink mid `#5A5955`, Ink light `#8C8A86`
- **Fonts:** EB Garamond (headlines/display), DM Sans Light (body/UI)
- **Wordmark:** Always use the Figma SVG export — never hand-code the S-curve mark
- **Wordmark source:** `C:\Users\richa\OneDrive\Desktop\RJ WORK FOLDER\SECOND CURVE\Wordmark design files\v1\Second Curve - Wordmark v1.svg`

## Current CSS values (index.html)
- Nav logo: `height: 137px` (desktop), `112px` (1024px), `87px` (768px)
- Nav padding: `16px 64px` (desktop), `14px 40px` (1024px), `12px 24px` (768px)
- Nav links: `font-size: 0.82rem`, `letter-spacing: 0.18em`
- Background image opacities: thesis `0.40`, HG section `0.40`
- Footer wordmark: `height: 52px`, `filter: brightness(0) invert(1)`, `opacity: 0.35`

## Wordmark rendering
- **Nav (light background):** No filter — natural charcoal/amber colours show through
- **Footer (dark background):** `filter: brightness(0) invert(1)` converts to white
- `wordmark-full.svg` viewBox: `250 18 740 248` — crops to content, transparent background

## Copy rules — ABSOLUTE
- Always "I" / "my" — never "we" / "our"
- Never reference London — Amsterdam only
- Never add: testimonials, pricing, packages, newsletter, contact form
- Contact: email only — `richard@secondcurve.nl`
- Hero line locked: "Complexity is rarely the problem. Hesitation is."
- CTA locked: "Start a conversation"

## Site structure (index.html)
1. **Hero** — Two-column grid. Left: headline + body + CTAs. Right: full-bleed portrait. `justify-content: center`, `padding: 140px 64px 64px`
2. **What I Do** — Two-column: heading left, three paragraphs right
3. **Thesis** — Dark charcoal bg + shadow-light.jpg at 0.40 opacity. Full-width quote
4. **Where I Work** — Six situation cards in 3-col grid with numbered labels + "so what" closing lines in amber italic
5. **Hesitation Gap** — Dark bg + window-light.jpg at 0.40 opacity. Two-column layout
6. **About** — Two-column: photo frame left, bio + ventures right
7. **Contact** — Email only. No form
8. **Footer** — Wordmark + copyright

## Pending before launch
- [ ] Wordmark PNG (2x) — `Second Curve - Wordmark v1 2x.png` in OneDrive — may be needed as fallback
- [ ] More/better photography (Richard said more options coming)
- [ ] Captive Leader website panel (framework still in development)
- [ ] LLMs.txt file
- [ ] Confirm secondcurve.nl domain is live
- [ ] Resolve UWV situation before publishing

## Richard's background (for copy decisions)
- Coffee Planet (UAE): co-founder, ~€15m revenue, ~20% EBITDA, 200+ staff, specialty coffee
- Ludlow Street Healthcare (UK): Deputy Chairman / Commercial Director, ~£50m revenue, ~1,500 staff
- Jones Brothers Coffee Co. (Netherlands): founded, scaled, closed — the authentic origin of Second Curve

## What NOT to do
- Never reopen locked decisions (hero line, CTA, wordmark direction, colour palette) without flagging
- Never use coaching/therapy language for the frameworks
- Never use stock photography of handshakes, graphs, boardrooms
- Never add features not explicitly requested
