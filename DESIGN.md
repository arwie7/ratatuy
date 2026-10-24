---
name: Рататуй
description: Banquet halls and family dinners in Ulyanovsk, set like a quiet fine-dining table of white porcelain, ink and a gold band.
colors:
  paper: "#ffffff"
  linen: "#f6f4ef"
  whisper: "#ebe6dc"
  hairline: "#e6e1d7"
  ink: "#16130e"
  ink-soft: "#5e5a52"
  ink-mute: "#736d63"
  gold: "#b8975a"
  gold-deep: "#94733a"
  gold-ink: "#7d6130"
  gold-light: "#d2b47a"
  gold-pale: "#f3ecdf"
  night: "#17140f"
  night-soft: "#b9b1a2"
  error: "#a3362b"
typography:
  display:
    fontFamily: "'Noto Serif Display', 'Times New Roman', serif"
    fontSize: "clamp(2.5rem, 1.4rem + 2.4vw, 3.6rem)"
    fontWeight: 300
    lineHeight: 1.04
    letterSpacing: "-0.012em"
  headline:
    fontFamily: "'Noto Serif Display', 'Times New Roman', serif"
    fontSize: "clamp(2.5rem, 1.5rem + 3.6vw, 4.75rem)"
    fontWeight: 300
    lineHeight: 1.04
    letterSpacing: "-0.015em"
  title:
    fontFamily: "'Noto Serif Display', 'Times New Roman', serif"
    fontSize: "clamp(1.5rem, 1.2rem + 0.9vw, 2.05rem)"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.005em"
  lead:
    fontFamily: "'Jost', system-ui, sans-serif"
    fontSize: "clamp(1.125rem, 1.03rem + 0.3vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.6
  body:
    fontFamily: "'Jost', system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
    fontFeature: "'kern', 'liga', 'pnum'"
  label:
    fontFamily: "'Jost', system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.015em"
  caption:
    fontFamily: "'Jost', system-ui, sans-serif"
    fontSize: "0.93rem"
    fontWeight: 400
    lineHeight: 1.375
rounded:
  field: "0.75rem"
  tile: "1rem"
  frame: "1.5rem"
  panel: "2rem"
  pill: "999px"
spacing:
  mat: "0.5rem"
  keyline-inset: "0.75rem"
  gutter: "clamp(1rem, 0.4rem + 2.6vw, 2.5rem)"
  section-y: "clamp(4.5rem, 2.6rem + 6.5vw, 9.5rem)"
  shell-max: "92rem"
  measure: "62ch"
components:
  button-gold:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 1.75rem"
    height: "3.25rem"
  button-gold-hover:
    backgroundColor: "#a8884d"
  button-ink:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 1.75rem"
    height: "3.25rem"
  button-ink-hover:
    backgroundColor: "#2d2820"
  button-line:
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 1.75rem"
    height: "3.25rem"
  button-line-hover:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
  button-sm:
    rounded: "{rounded.pill}"
    padding: "0 1.3rem"
    height: "2.75rem"
  field:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "0.75rem 1rem"
    height: "3.25rem"
  panel:
    backgroundColor: "{colors.linen}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
  panel-night:
    backgroundColor: "{colors.night}"
    textColor: "{colors.paper}"
    rounded: "{rounded.panel}"
  frame:
    backgroundColor: "{colors.paper}"
    rounded: "{rounded.frame}"
    padding: "{spacing.mat}"
  hall-nameplate:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tile}"
  capacity-tile:
    backgroundColor: "{colors.gold-pale}"
    textColor: "{colors.gold-ink}"
    rounded: "0.65rem"
  occasion-card-selected:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tile}"
  day-card-today:
    backgroundColor: "{colors.gold-pale}"
    textColor: "{colors.ink}"
    rounded: "{rounded.tile}"
  choice-chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
---

# Design System: Рататуй

## Overview

**Creative North Star: "The Quiet Fine-Dining Table"**

The page is laid like a table before guests arrive: white porcelain ground, ink lettering, and a single gold band running through the actions, the hairlines and the words that carry each sentence. Nothing is loud. Colour is withheld so that photographs of food and halls, all on one warm grade, supply the warmth, and gold reads as the house's one precious material.

Density is generous. Sections breathe on a fluid vertical rhythm, headings are set large in a very light high-contrast serif, and text runs in a clean geometric sans at a comfortable measure. Containers are soft-cornered and concentric: linen panels with a gold hairline set in from the edge like a printed menu card, photographs held in white mats with a thin gold fillet at the picture edge, and one arched mat that holds the occasion's dish in the hero. Depth comes from warm, low, diffuse shadows under objects that sit on the table (frames, nameplates, the form card), never under the panels themselves.

The world refuses loud colour, the bright kids-party template, and the dark moody restaurant page. Darkness exists only as a single night material, used for the wine promotion, the address plate and the phone action bar.

**Key Characteristics:**
- Mostly white ground; black text and some black buttons; gold for primary buttons and accent words.
- Light serif headings (300) over a Jost text face (400/500); no bold display weights.
- Gold keyline inset inside every panel; white mat plus gold fillet around every photo on open ground.
- Pill buttons, soft 1rem tiles, 2rem panels; the arch is the hero dish's alone.
- Warm ink shadows, low and diffuse; panels stay flat.
- One warm gold soft-light grade shared by every photograph.

## Colors

A porcelain palette: white and linen grounds, warm near-black ink, and a four-step gold family, with one night tone held in reserve.

### Primary
- **Table Gold** (gold): the primary action colour (every main call to action is a gold pill with ink text), the panel keylines, the steps rule, link underlines and the scrollbar thumb. Also the brass house-number tile on the address plate.
- **Deep Gold** (gold-deep): accent words inside headings on light grounds, the focus outline and field focus border, inline line icons beside contact facts, and link hover.
- **Gold Ink** (gold-ink, #7d6130): gold at body and label size, where deep gold would fall under 4.5:1: menu prices, the menu accent phrase, the capacity figure on its pale-gold tile, and «сегодня» on today's card. It holds 5.8:1 on paper, 5.3:1 on linen and 4.9:1 on pale gold.
- **Pale Gold** (gold-pale): the capacity tile on hall nameplates, today's promotion card, text selection.
- **Light Gold** (gold-light): accent words and focus rings on the night material, and the pointer light on hall nameplates.

### Neutral
- **Porcelain White** (paper): the page ground, mats around photographs, the header, the form card, nameplates and the selected occasion card.
- **Linen** (linen): panel ground (hero, children, request form), the menu section band and the footer; also the placeholder behind images while they load.
- **Whisper** (whisper): the oversized background lettering of the name behind the hero dish. Decorative only.
- **Hairline** (hairline): borders, list rules, unselected chip and tile outlines, the frame's outer ring.
- **Ink** (ink): all primary text, black buttons, selected chips.
- **Soft Ink** (ink-soft): secondary text, leads, captions, unselected nav links.
- **Muted Ink** (ink-mute): placeholders only.
- **Night** (night): the one dark material: wine promotion panel, address plate, mobile action bar.
- **Night Soft** (night-soft): secondary text on night.
- **Error** (error): field error borders and messages only.

### Named Rules
**The Gold Band Rule.** Gold marks the primary action, the keyline and the one phrase per heading that carries the sentence. Secondary actions are ink (solid or outline), never a second gold.

**The White Ground Rule.** White carries the page; linen is for panels and one section band; night is reserved for the wine promotion, the address plate and the phone action bar. No other dark or tinted grounds.

**The Readable Gold Rule.** Deep gold is for accent words at heading size and for icons. Any gold text below heading size uses gold ink, never deep gold or the button gold.

## Typography

**Display Font:** Noto Serif Display (with 'Times New Roman', serif), weights 300 and 400 loaded
**Body Font:** Jost (with system-ui, sans-serif), weights 400 and 500 loaded

**Character:** A thin, high-contrast didone-like serif speaking softly at very large sizes, set against a clean geometric sans that handles every working word. The contrast is in scale and stroke, not in weight.

### Hierarchy
- **Display** (300, clamp(2.5rem → 3.6rem), 1.04): the hero H1 only.
- **Headline** (300, clamp(2.5rem → 4.75rem), 1.04, -0.015em): section headings. Balanced wrapping.
- **Title** (400, clamp(1.5rem → 2.05rem), 1.12): sub-headings, step titles, the confirmation message.
- **Serif accents** (400 in Noto Serif Display at 1.2 to 1.75rem): occasion names, hall names, capacity figures, weekday names on promotion cards, the wordmark (1.95rem, 300).
- **Lead** (400, clamp(1.125rem → 1.25rem), 1.6): the paragraph directly under a heading, max 62ch.
- **Body** (400, 1.0625rem, 1.65): running text, with kerning, ligatures and proportional figures on; pretty wrapping.
- **Label** (500, 1rem, 0.015em): buttons, form legends, definition terms, dish names in lists (1.1rem, 400).
- **Caption** (400, 0.93rem): photo captions, notes under fields, price disclaimers.

### Named Rules
**The Light Serif Rule.** Headings are Noto Serif Display at 300 (titles at 400). The serif is never bolded; emphasis inside a heading is colour (an accent word), not weight.

**The Working Sans Rule.** Everything that is read, tapped or compared is Jost. Prices and the rouble sign are set in Jost at 500 with tabular figures; phone numbers and counts use tabular figures.

**The Plain Text Rule.** Paragraphs start bare: no bullet dots, no long em dashes, and no decorative 01/02/03 numbering. Factual numbers (capacities, prices, hours, the house number) are content and may be set large.

## Layout

A single centred shell (max 92rem) with a fluid gutter (clamp 1rem to 2.5rem) and a fluid section rhythm (clamp 4.5rem to 9.5rem). Desktop layouts sit on a 12-column grid, typically split 7/5 or 5/7 between image and text; text columns hold a 62ch measure. Panels sit inside the shell rather than bleeding full width; only the menu band runs edge to edge in linen.

Phones collapse to a single column in reading order: heading, lead and actions first, image after. The hero becomes H1, actions, dish frame, then a 2x2 occasion grid with the chosen description below it. Two-column grids that could overflow are forced to one column with min-width 0 on children. A fixed night action bar (call, WhatsApp, booking) appears at the bottom on phones once the hero scrolls away, and the footer reserves space for it. Anchored sections scroll with a 5.5rem top offset under the sticky header.

Breakpoints are Tailwind's defaults (sm 640, md 768, lg 1024, xl 1280); lg is where the desktop grid takes over.

## Elevation & Depth

A hybrid: grounds are flat and tonal (white, linen, night), and objects that sit on them cast warm, low, diffuse shadows tinted with brown ink (rgb 40 30 15), never grey or black. Shadows always use a large negative spread so they pool under the object rather than outlining it. Hairline rings (1px box-shadow in hairline or gold) define edges instead of borders where a shadow is also present.

### Shadow Vocabulary
- **Soft lift** (`0 30px 60px -36px rgb(40 30 15 / 0.35), 0 12px 24px -18px rgb(40 30 15 / 0.18)`): matted photo frames and the request form card.
- **Dish lift** (`0 0 0 1px hairline, 0 50px 70px -40px rgb(40 30 15 / 0.5), 0 20px 30px -24px rgb(40 30 15 / 0.3)`): the hero's arched frame only.
- **Plate lift** (`0 22px 40px -26px rgb(40 30 15 / 0.5)`): hall nameplates.
- **Selected lift** (`inset 0 0 0 1px gold, 0 16px 30px -22px rgb(40 30 15 / 0.4)`): the chosen occasion card.
- **Gold glow** (`0 12px 24px -14px rgb(148 115 58 / 0.7)`, deepening to 0.85 on hover): gold buttons.
- **Bar lift** (`0 18px 40px -16px rgb(40 30 15 / 0.6)`): the mobile action bar.

### Named Rules
**The Objects-On-The-Table Rule.** Panels are flat; only things placed on them (frames, nameplates, the form card, the chosen occasion, gold buttons) are lifted.

## Shapes

Soft, concentric rounding throughout. Buttons and chips are full pills; tiles, cards and nameplates use 1rem; fields 0.75rem; frames 1.5rem; panels 2rem (hero 1.75rem, 2.25rem on desktop). Inner radii are always the outer radius minus the inset, so mats, fillets and keylines nest concentrically.

Two signature edges recur. The **keyline**: a 1px gold line (gold at 55% opacity) inset 0.75rem from a panel's edge, following its radius, like the printed border of a menu card. The **mat and fillet**: every photograph on open ground sits in a white mat (0.5rem) with a hairline outer ring, and the picture itself carries a 1px gold fillet (gold at 40%). The wine panel's photograph is the exception; it bleeds to the panel edge as the panel's own half.

The **arch** (fully rounded top, 1.6rem bottom corners, 4:5 portrait) belongs to the hero dish frame alone.

## Components

### Buttons
Refined and confident: soft pills, medium weight, slightly tracked.
- **Shape:** full pill (999px), 3.25rem tall, 1.75rem side padding; small variant 2.75rem and 1.3rem.
- **Gold (primary):** gold ground, ink text, gold glow shadow. One per action group: book a hall, order a children's party, pre-order, send to WhatsApp, the header's banquet button.
- **Ink:** ink ground, white text. Secondary commitments: check free dates, open the menu, build a route.
- **Line:** transparent with a 1px inset ink ring; fills ink with white text on hover. Call, toggles, icon-only social links.
- **Line light:** on night, a 1px white ring at 55% that firms to solid on hover.
- **Hover / Focus:** 0.3s expo-out colour and shadow transitions; press nudges down 1px. Focus is a 1.5px deep-gold outline offset 4px (light gold on night).

### Chips (choice chips in the request form)
- **Style:** pill, 2.75rem tall, soft-ink text, 1px inset hairline ring; hover darkens the ring and text.
- **State:** selected fills ink with white text. Hall choices use the same treatment as 0.85rem-rounded tiles with a capacity note under the name.

### Cards / Containers
- **Panel:** linen, 2rem radius, gold keyline inset 0.75rem, flat. Hosts the hero, children and request form.
- **Night panel:** the same construction on night with light-gold accents and night-soft secondary text.
- **Form card:** white, 1.5rem radius, soft lift, set inside the linen panel.
- **Day card:** white tile, 1rem radius, hairline ring; today's card turns pale gold with a gold ring and a small «сегодня» label.
- **Internal padding:** panels 3rem to 5rem vertical, 1.25rem to 4rem horizontal; tiles 1rem.

### Inputs / Fields
- **Style:** white, 1px hairline border, 0.75rem radius, 3.25rem tall, body type. Placeholders in muted ink.
- **Focus:** border turns deep gold with a 4px gold halo at 18%.
- **Error:** border in error red; message below in error at 500.
- **Steppers:** square 3.25rem ring buttons flank the guest count; ring turns deep gold on hover.

### Navigation
- **Header:** white, sticky, 4.5rem (5rem on desktop). Serif wordmark left, six Jost links in soft ink turning ink on hover, phone with a deep-gold line icon (xl only), and the small gold banquet pill. On scroll it turns 90% white with a backdrop blur and a hairline under it.
- **Mobile menu:** a full-height white panel with keyline, links set in the serif at 2.4rem, phone and round social buttons at the foot.
- **Mobile action bar:** a night pill bar of three: call, WhatsApp, and a gold booking button.

### Matted Frame (signature)
A photograph in a white mat with a gold fillet at the picture edge and a soft lift. Used for halls, the children's rooms, the menu photograph, the photo band and the map. All images share one grade: saturation 0.95, a gentle contrast lift, and a 10% gold (Table Gold) soft-light wash.

### Hero Dish Arch (signature)
The arched, white-matted frame in the hero. Choosing an occasion reveals the new dish rising into it (clip-path from the bottom, 1s expo-out, slight scale settle); the previous dish fades after.

### Hall Nameplate (signature)
A white 1rem plate with a plate lift: the hall name in serif, then a pale-gold capacity tile reading «до N» in deep gold serif with tabular figures. A soft gold light follows the pointer across it. Nameplates overlap the top edge of their photograph by 2.5rem on the smaller halls.

### Address Plate (signature)
A night panel with keyline holding the street name in serif, and a gold tile set into its right side carrying the house number in large serif ink.

## Do's and Don'ts

### Do:
- **Do** keep the ground white and use linen only for panels and the menu band.
- **Do** make every primary action a gold pill with ink text; make secondary actions ink or ink outline.
- **Do** set one accent phrase per heading in deep gold (light gold on night).
- **Do** set headings in Noto Serif Display 300 and everything functional in Jost 400/500.
- **Do** put every photograph on open ground in a white mat with a gold fillet, graded with the shared warm gold wash.
- **Do** give panels a 1px gold keyline inset from the edge, concentric with the corner.
- **Do** use warm ink-tinted shadows (rgb 40 30 15) with large negative spread, only under objects placed on a ground.
- **Do** set prices, the rouble sign, phone numbers and counts in Jost with tabular figures.
- **Do** use expo-out easing (cubic-bezier(0.16, 1, 0.3, 1)) and stop the photo band under reduced motion.

### Don't:
- **Don't** put bullet dots before paragraphs.
- **Don't** use long em dashes in copy.
- **Don't** number sections or steps decoratively (01, 02, 03); capacities, prices, hours and the house number are content and may be large.
- **Don't** introduce bright or saturated colour; gold and the night tone are the only departures from white and ink.
- **Don't** add a second dark panel beyond the wine promotion, the address plate and the phone action bar.
- **Don't** bold the serif or use a sans for headings.
- **Don't** set body-size text in deep gold on linen or pale gold.
- **Don't** reuse the arch outside the hero dish frame.
- **Don't** use grey or black drop shadows, or shadows under panels.
