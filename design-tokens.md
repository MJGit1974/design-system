# Brand Design System

## Colour Palette

### Primary colours
| Token | Hex | Usage |
|-------|-----|-------|
| color-green | #30EA03 | Primary accent, highlights, CTA buttons, key UI moments |
| color-black | #000000 | Primary text, divider slide backgrounds |
| color-white | #FFFFFF | Content slide/page backgrounds |
| color-slate-dark | #333F48 | Supporting dark tone, secondary headings |
| color-grey-mid | #8D979D | Captions, metadata, supporting copy |
| color-grey-light | #D0D3D3 | Borders, dividers, rule lines |

### Highlight palette (use sparingly)
| color-teal | #5CE0CA | Category tags |
| color-pink | #FF28FF | Category tags |
| color-purple | #AD7BFF | Category tags |
| color-yellow | #DCFF00 | Category tags |

## Typography
Font: Verdana, Geneva, sans-serif throughout.
Heading Large: Verdana Bold 24pt
Heading Regular: Verdana Bold 18pt
Subheading Large: Verdana Regular 16pt
Subheading Regular: Verdana Regular 12pt
Body Large: Verdana Regular 14pt
Body Regular: Verdana Regular 11pt
Caption: Verdana Italic 11pt
Rules: Sentence case only. Left-align body. Primary bullets hyphen, secondary bullets arrow.
Highlight key phrases in #30EA03 bold inline only - never green for full body text.

## Logo
Black wordmark with #30EA03 green bar replacing middle crossbar of E.
Colour positive on white/light. Colour negative (white) on black/dark.
Logo on every slide and page.

## Spacing (8px base grid)
space-xs: 8px | space-sm: 16px | space-md: 24px | space-lg: 32px
space-xl: 48px (page margins minimum) | space-2xl: 64px | space-3xl: 96px

## Components

Buttons:
Primary: #30EA03 bg, #000 Verdana bold uppercase
Secondary: #000 bg, #FFF text
Outlined: transparent, #000 border 2px
Ghost: transparent, #D0D3D3 border 2px
Border radius 2px, letter-spacing 0.08em

Cards: #FFF bg, 1px #D0D3D3 border, 4px radius, #30EA03 accent bar 3px wide

Stat callouts: large bold number, #8D979D label above, #30EA03 3px rule below

Divider slides: #000 bg, white Verdana bold heading, #30EA03 4px bar above heading

Tags: Verdana Bold 9-10pt uppercase, highlight palette colours

## Icons
Clean outlined style, thin strokes, transparent backgrounds.
Categories: Oral Health, Pain Relief, Respiratory Health, VMS, Digestive Health, Therapeutic Skin Health
Stakeholders: Consumers, Health Professionals, Employees, Investors, Suppliers, Customers, Government/Regulators
Resources: R&D, Manufacturing, Sales, Regulatory Expertise, Resources, AP
Drivers: Health & Wellness, Aging Population, Global Population, Pressure on Healthcare, Unmet Consumer Needs

## Layout Rules
Content slides: white (#FFFFFF) background
Divider slides: black (#000000) or #333F48 only
No full-width decorative bars or underlines beneath titles
Logo every slide. Page numbers every slide.

## Accessibility
Black on White: 21:1 - PASS AA + AAA
White on Black: 21:1 - PASS AA + AAA
Black on Green #30EA03: 9.8:1 - PASS AA + AAA
Green #30EA03 on White: 1.4:1 - FAIL - DO NOT USE FOR BODY TEXT
Dark Slate #333F48 on White: 8.1:1 - PASS AA + AAA

## Claude Design Prompt
Use this design system:
- Primary green: #30EA03 | Black: #000000 | White: #FFFFFF
- Dark slate: #333F48 | Mid grey: #8D979D | Light grey: #D0D3D3
- Highlight (sparingly): teal #5CE0CA, pink #FF28FF, purple #AD7BFF, yellow #DCFF00
- Font: Verdana throughout. Bold headings. Regular body.
- Content backgrounds: white. Divider slides: black.
- Green for accents and highlights only - not body text on white (fails WCAG).
- 8px grid. 48px page margins. Generous negative space.
- Logo on every slide/page.
