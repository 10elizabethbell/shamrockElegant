# Shamrock Transportation (elegant / sea glass) — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shamrockElegant/ · **Repo:** https://github.com/10elizabethbell/shamrockElegant · **Built:** 2026-10-15 from the Muse brief in `../shamrockSimpleClear/brief.md`, with the context handed over by the shamrockSimpleClear session

## What's built
- **The world: sea glass.** Ellie asked for "very elegant and high-class, glassy, liquid glass, light soft gradients". Impeccable's roll picked sea glass from my list of seven glass renditions: frosted, soft-edged green glass from the Jersey and Florida shores.
  - **The ground:** a still sky that warms down the page, from a cool New Jersey morning (#d9e6ea) at the top to a Florida afternoon (#f5dcc4) at the bottom, so scrolling is the drive south. Nothing moves.
- **Glass that does something.** Frosted panes (`backdrop-filter: blur(22px) saturate(150%)`) sit straight on the graded sky with nothing else behind them (the color blooms and pebbles were cut as less elegant). The panes tint aqua, then green, then peach down the page, with soft inner shading for thickness. There are no glint or highlight lines, since you cut those before. Browsers without backdrop-filter get a more opaque pane that still reads.
- **The shamrock** is drawn as one piece of frosted sea glass: three heart leaves and a stem in a single silhouette, translucent in the middle and deeper at the edges, with faint frost grain. It appears large in the hero, small in the header from 640px wide (phones get a centered name-over-number header instead), and on the favicon, home-screen icon and share image. Redrawn after you said the first one looked like four pieces with the stem behind.
- **Sections:**
  - glass header with the name and full number
  - hero: "You fly. / I'll drive your car.", Ed's line, CALL ED button carrying the number, "My own cell" note, the shamrock
  - How it works (I–III)
  - The rate ($1 per mile + Call for your total)
  - One driver + When a truck is the better choice
  - deep-green close ("Heading south this winter?"; March–May it reads "Heading home to New Jersey?")
  - footer
- **Desktop** puts How it works and The rate side by side. One driver splits into two columns, and the close pane puts its heading beside the button.
- **Type:** Gilda Display (self-hosted, OFL, 13 KB) for headings and the price. The system sans at 20px for body. Button labels are letterspaced capitals.
- **Contact:** every call link is `tel:+17323003835`. There is no text button because texting is unknown. At most the header number plus one button show on the first screen.
- **Checked:**
  - Chrome and WebKit at 360/375/390/414/430, landscape 844x390, 1024 and 1440: no sideways scroll, Call on the first screen everywhere, header name never touches the number
  - on-screen contrast measured against the real glass: lowest 4.77:1 (brass numerals, large text), body text 5.4:1+
  - Impeccable detector clean (three recorded exceptions in `.impeccable/config.json`, each with a reason)
  - Impeccable finish review plus every other mode except live

## Assumptions I made
- **Same copy as shamrockSimpleClear, word for word**, because you liked it. Every assumption there carries over:
  - $1 a mile is on the page (the `RATE` comment in the HTML)
  - "I drive your car myself"
  - "packed with your things"
  - the truck answer is general driveaway knowledge, not Ed's words
  - the card tagline is left off
- **The shamrock is a drawing**, not the card's emblem (the brief says ask before using a card scan). Its greens are sea-glass greens, not sampled from the card.
- **Gilda Display** is my pick: elegant, high-contrast, and sturdy enough at heading sizes. It's one `@font-face` and `--serif` to swap.

## Placeholders and gaps
- No photo of Ed (`<!-- PHOTO -->` comments mark the hero emblem spot and the One driver pane).
- No email and no Facebook, so the footer email and the "see more of my work" link are absent by design.
- Not on the page: insurance, what $1 a mile includes, hours, years in business, reviews, exact towns.
- youflyilldrive.com may be unregistered. Verify it at a registrar before offering it.

## Questions for the owner
1. Does $1 a mile include gas, tolls and your trip back? Is there a minimum?
2. Do you take texts? (If so, a "Text Ed" link can go under the Call button.)
3. What insurance covers the car and its contents while you drive?
4. Do you drive every car yourself? Any packing limits?
5. What does "Airport services anywhere in Florida" mean in practice?
6. Can we use the shamrock from your card, and a photo of you beside a car?
7. Which months do you head south and north? How much notice do you need?

## Ideas not built (yours to pick)
- **Cut How it works.** The mode sweep pointed out that the hero already says steps I and II, and you cut this section from other Shamrock builds once the price was on the page. If you cut it, move "back to New Jersey in the spring" into One driver.
- **Runner-up rendition: windshield glass.** A dawn highway seen through a frosted windscreen, with the panes as glass. It's more literal and less shore.
- **A small handset icon before the header number**, to show older visitors it's tappable. I left it out because it crowds the header at 390px.
- **Lighter phone rendering:** drop the backdrop blur on the panes (keep it on the header) if older Android phones scroll slowly. The panes keep almost the same look with a slightly more opaque tint.
- A "What's included" line under $1 a mile once Ed answers question 1.

## Not verified
- Real-device tap-to-call on iPhone and Android, and inside Facebook's in-app browser.
- Scroll smoothness of four frosted panes on an older Android phone.
- How the page reads to an actual 60-year-old (the research suggests a 5–6 person test).
