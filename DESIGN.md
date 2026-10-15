---
name: Shamrock Transportation
description: Sea glass laid over a still sky that warms from a New Jersey morning to a Florida afternoon.
colors:
  bottle-ink: "#13342a"
  bottle-ink-soft: "#35554a"
  deep-sea-glass: "#0f4434"
  call-green-light: "#1b664d"
  call-green-dark: "#0d3e30"
  shore-ivory: "#f6f1e6"
  brass-numeral: "#7a5c2e"
  brass-outline: "#9a7440"
  sky: "#d9e6ea"
  mist: "#e5eeeb"
  shore: "#eef0e5"
  sand: "#f4e9d8"
  sun: "#f5dcc4"
  pane-aqua: "#e6f6f6"
  pane-green: "#e8f6ee"
  pane-peach: "#fff3e8"
  sea-glass-mid: "#9fd0ba"
  sea-glass-edge: "#3f8a6c"
typography:
  display:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(2.875rem, 1.9rem + 4.4vw, 5.25rem)"
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: "-0.01em"
  price:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(3rem, 2.3rem + 3vw, 4.25rem)"
    fontWeight: 400
    lineHeight: 1.05
  headline:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "clamp(2rem, 1.55rem + 2vw, 2.875rem)"
    fontWeight: 400
    lineHeight: 1.12
  title:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "1.5rem"
    fontWeight: 400
    lineHeight: 1.3
  numeral:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "1.75rem"
    fontWeight: 400
    lineHeight: 1.25
  wordmark:
    fontFamily: "Gilda Display, Didot, Bodoni 72, Georgia, serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.12em"
  lead:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.3125rem"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.6
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.14em"
  phone:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: "0.03em"
    fontFeature: "tnum"
rounded:
  button: "20px"
  bar: "22px"
  pane: "28px"
  pane-wide: "36px"
spacing:
  gutter-phone: "16px"
  gutter-tablet: "32px"
  gutter-desktop: "48px"
  pane-phone: "36px 24px 40px"
  pane-tablet: "52px 48px 56px"
  pane-desktop: "60px 64px 64px"
  section-phone: "28px"
  section-desktop: "40px"
  button-gap: "32px"
components:
  button-call:
    backgroundColor: "{colors.call-green-dark}"
    textColor: "{colors.shore-ivory}"
    rounded: "{rounded.button}"
    padding: "14px 18px"
    height: "80px"
    width: "24rem"
  button-call-light:
    backgroundColor: "{colors.shore-ivory}"
    textColor: "{colors.deep-sea-glass}"
    rounded: "{rounded.button}"
    padding: "14px 18px"
    height: "80px"
    width: "24rem"
  pane-glass:
    backgroundColor: "{colors.pane-aqua}"
    textColor: "{colors.bottle-ink}"
    rounded: "{rounded.pane}"
    padding: "{spacing.pane-phone}"
  pane-deep:
    backgroundColor: "{colors.deep-sea-glass}"
    textColor: "{colors.shore-ivory}"
    rounded: "{rounded.pane}"
    padding: "{spacing.pane-phone}"
  header-bar:
    backgroundColor: "{colors.pane-aqua}"
    textColor: "{colors.bottle-ink}"
    rounded: "{rounded.bar}"
    padding: "6px 18px"
    height: "68px"
---

# Design System: Shamrock Transportation

## Overview

**Creative North Star: "Sea Glass on the Drive South"**

Frosted, soft-edged green glass from the Jersey and Florida shores, laid over a still sky. The page ground is one long vertical gradient that starts as a cool New Jersey morning at the top and ends as a warm Florida afternoon at the bottom, so scrolling is the drive south. Content sits on frosted panes that blur the scene behind them and nothing else sits on the ground: no scattered blobs or pebbles of color, so the page stays quiet and expensive. Nothing moves. The glass is felt through translucency, inner shading and green-tinted shadow, never through animation or light effects.

The audience is 40 to 70 and reading on a phone, often inside the Facebook browser. Every rule bends to that: large serif headings, 20px body, 80px call buttons, contrast measured against the actual glass rather than the flat tint, nothing hidden behind a tap or hover. Elegance comes from restraint and material, not from small type or faint text. Density is low: one idea per pane, generous pane padding, a single column on phones.

Confirmed rejections: the dark-hero-plus-white-bands default, every moving glass effect (shimmer, parallax, tilt, animated refraction), glints, specular highlight streaks and rim lines on the glass (removed at Ellie's direction), and eyebrow labels over headings.

**Key Characteristics:**
- Still sky-to-sand ground (sky → mist → shore → sand → sun) behind everything.
- Frosted panes: backdrop blur 22px with saturate 150%, tinted aqua → green → peach down the page.
- Deep sea-glass green for every call button and for the closing pane.
- Gilda Display for headings, numerals and the wordmark; the system sans at 20px for reading.
- Brass appears only on numerals and on hover/focus outlines.
- One emblem: an engraved deep-green line shamrock drawn in SVG.
- Zero motion, zero hidden content.

## Colors

A cool-to-warm pastel scene carrying deep bottle-green ink and glass, with brass held back for a few accents.

### Primary
- **Deep Sea-Glass Green** (deep-sea-glass): headline and heading color on light glass and the text color on the light call button.
- **Call Green** (call-green-light → call-green-dark): the 155deg gradient on every call button. Hover deepens both stops slightly.

### Secondary
- **Brass Numeral** (brass-numeral): the Roman numerals I–III in How it works. This is the deeper brass and the lowest-contrast text on the page (measured 4.77:1 on the real glass).
- **Brass Outline** (brass-outline): hover and focus outlines (2px, 4px offset) and the hover underline color on footer links. Non-text only; it measures 3.2–4.3:1 and must never carry text.

### Tertiary
- **Sea-Glass Mid / Sea-Glass Edge** (sea-glass-mid, sea-glass-edge): the shamrock emblem's radial fill, pale at the center and deepening to the edge. The list markers in One driver use a smaller sea-glass gradient in the same family.

### Neutral
- **Bottle Ink** (bottle-ink): primary text. Ink is deep green, never gray.
- **Bottle Ink Soft** (bottle-ink-soft): secondary body copy inside panes, notes, footer text (6.2:1 or better on the scene).
- **Shore Ivory** (shore-ivory): text on the deep-green call buttons.
- **The Scene** (sky, mist, shore, sand, sun): the body gradient at 0 / 22 / 52 / 82 / 100%. The html background is sun so overscroll lands on the Florida end.
- **Pane Tints** (pane-aqua, pane-green, pane-peach): RGB tints mixed into the glass gradient at 62% → 30% white → 42%, in page order aqua, green, peach.
- **Divider**: 1px rgba(19,52,42,.14), used only between the One driver body and its truck aside.

### Named Rules
**The Brass Is Rare Rule.** Brass appears on numerals and on hover/focus outlines, nowhere else. No brass fills, borders, icons or headings.

**The Measured on Glass Rule.** Every text color is checked at 4.5:1 or better against the real rendered glass, not the flat tint. If a pane's tint gets darker, the tint changes; the text never gets lighter.

**The Green Ink Rule.** Text is bottle green or ivory. No gray text, no pure black.

## Typography

**Display Font:** Gilda Display (with Didot, Bodoni 72, Georgia, serif), self-hosted woff2, weight 400 only.
**Body Font:** the system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial).

**Character:** a quiet high-contrast serif at a single regular weight does the elegance; a familiar system sans at large size does the reading. The serif is never bold and never small.

### Hierarchy
- **Display** (400, clamp 46–84px, 1.04, -0.01em): the hero headline only, deep sea-glass green, each sentence on its own balanced line.
- **Price** (400, clamp 48–68px, 1.05): the rate figure, nowrap.
- **Headline** (400, clamp 32–46px, 1.12): pane headings (h2), balanced, 22px below.
- **Title** (400, 24px, 1.3): step titles; the truck aside heading runs 26px on phones and 32px on desktop.
- **Numeral** (400, 28px, 1.25): Roman step numerals in brass numeral, in a 3rem column.
- **Wordmark** (400, 17px, 0.12em, uppercase): the name in the header and footer only. Tracking is 0.2em in the header, 0.16em on phones.
- **Lead** (400, 21px, 1.55, max 28em): the hero line under the headline.
- **Body** (400, 20px, 1.6, max 34em): all running copy; text-wrap pretty.
- **Small** (400, 18px): notes and the footer. 18px is the floor for any reading text.
- **Label** (600, 17px, 0.14em, uppercase): the action word on a call button ("Call Ed"), sitting directly above the number. It exists only inside buttons.
- **Phone** (400, 22px, 0.03em, tabular numerals): the number inside call buttons.

### Named Rules
**The Eighteen Floor Rule.** No reading text below 18px (1.125rem). Body is 20px.

**The One Weight Serif Rule.** Gilda Display is used at 400 only. Hierarchy comes from size and color, never from faux bold.

**The No Eyebrow Rule.** Headings stand alone. No small caps kicker, tag or eyebrow label above any heading. Uppercase tracking is reserved for the wordmark and the action word inside a call button.

## Layout

A centered column, max 72rem, with a gutter of 16px on phones, 32px from 640px and 48px from 1024px. Panes stack in one column on phones with 28px between them (40px on desktop).

Breakpoints are 640px (gutter and pane padding grow) and 1024px (two-column compositions and the larger pane radius). At every width the hero is one centered column (shamrock crest, headline, Ed's line, call button); at 1024px How it works and The rate share a 1.1fr / 0.9fr row with equal-height panes and the rate's call button pinned to the pane bottom; One driver splits into two columns divided by a 1px line with 64px either side. A landscape phone (max-height 500px) shrinks the hero so the call button stays on the first screen.

Pane padding steps 36/24/40px → 52/48/56px → 60/64/64px. A call button sits 32px below the copy it follows. Text measures cap at 28em (lead) and 34em (body).

The header is a slim glass bar in normal flow, not sticky, holding only the wordmark, centered. There is no header phone number: the number lives on the Call buttons, so it never shows twice on the first screen.

## Elevation & Depth

Depth is material: frosted translucency plus soft, green-tinted ambient shadow. Panes blur and saturate whatever lies under them (blur 22px, saturate 150%), over the graded ground; the tint, inner shade and shadow are what make them read as glass. Each light pane carries a diffuse inner shade (a soft white wash fading in from the top, a faint green dusk at the bottom) to suggest thickness, and a long, soft green shadow below. Where backdrop-filter is unsupported the pane falls back to a more opaque tinted gradient (86% → 66%) so text contrast holds.

### Shadow Vocabulary
- **Pane** (`box-shadow: inset 0 24px 40px -28px rgba(255,255,255,.9), inset 0 -26px 40px -30px rgba(19,70,54,.16), 0 28px 60px -28px rgba(19,70,54,.38), 0 4px 14px -6px rgba(19,70,54,.12)`): every light glass surface, including the header bar.
- **Call button** (`box-shadow: 0 18px 36px -16px rgba(11,51,40,.6), 0 3px 8px -3px rgba(11,51,40,.3)`): pressed state tightens to `0 8px 18px -10px rgba(11,51,40,.6)`.

### Named Rules
**The Green Shadow Rule.** Shadows are tinted bottle green (rgba 19,70,54 or 11,51,40), soft and long. No black shadows on light glass, no hard offsets.

**The Still Glass Rule.** Nothing moves: no transitions, animations, parallax, shimmer or scroll effects. State changes are instant.

**The No Glint Rule.** Glass has no specular streaks, glints, highlight strokes or rim lines. Light inside the glass is only ever a diffuse wash.

## Shapes

Soft, generous corners throughout: panes 28px (36px from 1024px), the header bar 22px, call buttons 20px. Panes have no border; their edge is the change in blur and the shadow. The only line is the 1px translucent divider in One driver. The one organic form is the shamrock (three heart leaves, a curved stem and a center disc merged into one silhouette, clipped by a mask so it reads as one piece of glass). List markers are small irregular sea-glass blobs (border-radius 40% 55% 45% 60%), not circles or glyphs.

## Components

### Buttons
Heavy, calm and impossible to miss. The call button is the only interactive control besides the phone links.
- **Shape:** gently rounded (20px), full width up to 24rem, at least 80px tall.
- **Primary (Call):** a 155deg call-green gradient, ivory text; two lines centered, the uppercase action label (600, 17px, 0.14em) above the number (22px, tabular). Every button dials the same number.
- **Hover / Focus:** hover darkens the gradient and adds the 2px brass outline at 4px offset; focus-visible shows the same outline.

### Cards / Containers (Glass Pane)
- **Corner Style:** 28px, 36px at desktop.
- **Background:** a 150deg tinted translucent gradient over backdrop blur; tint follows page order aqua → green → peach.
- **Shadow Strategy:** Pane shadow (see Elevation & Depth).
- **Border:** none.
- **Internal Padding:** 36/24/40px, 52/48/56px, 60/64/64px by breakpoint.

### Navigation
- **Header bar:** a slim glass bar (22px radius, min 60px tall) holding only the uppercase serif wordmark, centered, linking to the top (48px target). No phone number (it is on the call buttons) and no menu: the page is one scroll.

### Steps List
Roman numerals in brass numeral (Gilda, 28px) in a 3rem column spanning a serif title and a sans line of body copy; 26px between steps.

### Engraved Shamrock (signature)
The one emblem: the three-heart-leaf-and-stem silhouette drawn as a single fine outline (an SVG feMorphology dilate of the silhouette minus the silhouette itself) in currentColor, with one vein per leaf at 75% opacity. The stem carries its own outline (masked clear of the center hub) so a line divides it from the leaf it crosses, as in the solid version. No fill, gradient, grain or shadow. Deep sea-glass green in the hero crest (88px phone, 112px desktop, centered above the headline); ivory with a heavier line on the deep-green favicon and home-screen icon. Ellie chose it as option A of four on 2026-10-15 (options page: https://claude.ai/artifact/6R56VxMiaXTtfF81aAc4o1); B solid emerald, C seal and D quiet glass remain candidates.

## Do's and Don'ts

### Do:
- **Do** keep the ground as the single sky → mist → shore → sand → sun gradient; the scroll is the drive south.
- **Do** keep the ground clear: no color blooms, blobs or pebbles behind the panes (Ellie cut them as less elegant).
- **Do** tint panes in page order aqua → green → peach and end on the footer; there is no closing call band (Ellie cut it).
- **Do** make every call button at least 80px tall (56px absolute minimum) with the full number on it.
- **Do** keep body text at 20px and nothing below 18px.
- **Do** measure every text color against the rendered glass at 4.5:1 or better; the brass numeral at 4.77:1 is the floor.
- **Do** keep tap targets at least 48px tall, including header and footer links.

### Don't:
- **Don't** add motion of any kind: no transitions, animated glass, parallax, reveal-on-scroll or hover lifts.
- **Don't** hide content behind accordions, tabs, menus, popups or sticky widgets.
- **Don't** add glints, specular highlight streaks, highlight strokes or rim lines to panes or the shamrock.
- **Don't** put an eyebrow, kicker or tag label above any heading.
- **Don't** use brass for text other than numerals, or the lighter outline brass for any text at all.
- **Don't** add a second contact action (form, email, text, social); call is the only action.
- **Don't** use gray or black text or black shadows; ink and shadow are bottle green.
- **Don't** bold Gilda Display or set it below 16px (the phone wordmark size).
