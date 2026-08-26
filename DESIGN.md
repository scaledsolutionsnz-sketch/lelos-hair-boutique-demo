---
name: Lelo's Hair Boutique
description: A one-chair garden salon published as a fashion magazine assembled from the stylist's own plates.
colors:
  ink: "#0C0B0B"
  ink-2: "#141212"
  chalk: "#F4F3F1"
  chalk-dim: "rgba(244,243,241,.64)"
  rule: "rgba(244,243,241,.20)"
  rule-soft: "rgba(244,243,241,.11)"
  paper: "#EDEDEA"
  paper-2: "#E3E3DF"
  paper-dim: "rgba(12,11,11,.62)"
  paper-rule: "rgba(12,11,11,.18)"
  gold: "#C89A4E"
typography:
  display:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(2.4rem, 5.6vw, 4.6rem)"
    lineHeight: 0.92
    letterSpacing: "-.035em"
    fontVariation: "'wdth' 118, 'wght' 800"
    textTransform: "uppercase"
  headline:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(2.2rem, 4.8vw, 3.8rem)"
    lineHeight: 0.94
    letterSpacing: "-.035em"
    fontVariation: "'wdth' 116, 'wght' 800"
    textTransform: "uppercase"
  pull:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1.4rem, 3.3vw, 2.35rem)"
    lineHeight: 1.12
    letterSpacing: "-.025em"
    fontVariation: "'wdth' 108, 'wght' 600"
  title:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1.02rem, 1.5vw, 1.35rem)"
    lineHeight: 1.1
    letterSpacing: "-.01em"
    fontVariation: "'wdth' 112, 'wght' 700"
    textTransform: "uppercase"
  body:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1.02rem, .42vw + .92rem, 1.16rem)"
    lineHeight: 1.62
    fontVariation: "'wdth' 100, 'wght' 400"
  base:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(15px, .55vw + 13.4px, 17px)"
    lineHeight: 1.6
    fontVariation: "'wdth' 100, 'wght' 400"
  label:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".68rem"
    letterSpacing: ".2em"
    fontVariation: "'wdth' 100, 'wght' 600"
    textTransform: "uppercase"
  action:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".83rem"
    letterSpacing: ".16em"
    fontVariation: "'wdth' 100, 'wght' 700"
    textTransform: "uppercase"
  navLabel:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".72rem"
    letterSpacing: ".18em"
    fontVariation: "'wdth' 100, 'wght' 600"
    textTransform: "uppercase"
  micro:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".8rem"
    lineHeight: 1.55
    fontVariation: "'wdth' 100, 'wght' 400"
  caption:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".88rem"
    lineHeight: 1.5
    fontVariation: "'wdth' 100, 'wght' 400"
  smallBody:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: ".95rem"
    lineHeight: 1.55
    fontVariation: "'wdth' 100, 'wght' 400"
  coverHeadline:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(2.6rem, 6.2vw, 5.4rem)"
    lineHeight: 0.9
    letterSpacing: "-.035em"
    fontVariation: "'wdth' 116, 'wght' 800"
    textTransform: "uppercase"
  colophonHead:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(2.6rem, 6vw, 5.4rem)"
    lineHeight: 0.9
    letterSpacing: "-.035em"
    fontVariation: "'wdth' 118, 'wght' 800"
    textTransform: "uppercase"
  drawerLink:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1.7rem, 7vw, 2.6rem)"
    lineHeight: 1.1
    letterSpacing: "-.02em"
    fontVariation: "'wdth' 112, 'wght' 700"
    textTransform: "uppercase"
  marginNote:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1.3rem, 2.6vw, 2rem)"
    lineHeight: 1.02
    letterSpacing: "-.02em"
    fontVariation: "'wdth' 112, 'wght' 700"
    textTransform: "uppercase"
  wordmark:
    fontFamily: "Archivo, system-ui, -apple-system, 'Helvetica Neue', Arial, sans-serif"
    fontSize: "clamp(1rem, 1.5vw, 1.24rem)"
    lineHeight: 1
    letterSpacing: "-.01em"
    fontVariation: "'wdth' 118, 'wght' 800"
    textTransform: "uppercase"
spacing:
  gut: "clamp(20px, 4.4vw, 64px)"
  sec: "clamp(4.5rem, 9vw, 8rem)"
  sec-tight: "clamp(3rem, 6vw, 5rem)"
  well: "clamp(2.6rem, 6vw, 5.5rem)"
  spread: "clamp(14px, 2.2vw, 30px)"
  entry: "clamp(1.1rem, 2.4vw, 1.7rem)"
components:
  action-primary:
    backgroundColor: "{colors.chalk}"
    textColor: "{colors.ink}"
    typography: "{typography.action}"
    padding: ".95rem 1.6rem"
    height: "54px"
  action-primary-hover:
    backgroundColor: "transparent"
    textColor: "{colors.chalk}"
  action-line:
    backgroundColor: "transparent"
    textColor: "{colors.chalk}"
    typography: "{typography.action}"
    padding: ".95rem 1.6rem"
    height: "54px"
  action-line-hover:
    backgroundColor: "{colors.chalk}"
    textColor: "{colors.ink}"
  action-primary-on-paper:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.action}"
    padding: ".95rem 1.6rem"
    height: "54px"
  nav-call:
    backgroundColor: "{colors.chalk}"
    textColor: "{colors.ink}"
    padding: ".6rem 1rem"
    height: "42px"
  contents-entry:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    padding: "clamp(1.1rem, 2.4vw, 1.7rem) 0"
  booking-box:
    backgroundColor: "transparent"
    textColor: "{colors.chalk}"
    padding: "clamp(1.4rem, 3vw, 2.1rem)"
  icon-button:
    backgroundColor: "transparent"
    textColor: "{colors.chalk}"
    height: "46px"
    width: "46px"
---

# Design System: Lelo's Hair Boutique

## Overview

**Creative North Star: "The Issue"**

The site is a printed fashion issue, not a salon website. Her finished hair is the entire argument, so every structural decision hands the page back to the photographs: a full-bleed cover plate with the logo lockup as masthead, a feature well of plates with numbered captions, a contents page for services, a colophon for booking. There is no salon-template hero, no icon-card service grid, and none of the cream/serif/terracotta vocabulary of the site it replaced.

The ground is near-black ink with chalk text, broken exactly once by a paper-white reading section. Colour arrives from the photography and nowhere else; the only manufactured warm value is the gold lifted out of the client's existing logo, spent on caption numbers, fact keys, focus rings and link hovers. Structure is carried by hairline rules and grid alignment, never by cards, panels, radii or shadows. One typeface does all of it: Archivo variable, worked through width, weight, case, tracking and scale.

The build is phone-first by construction. It is read at night on a small screen, so the display sizes are clamped against viewport width, the cover headline narrows its width axis rather than shrinking, and every text pair clears WCAG AA (measured floor 5.27:1, dimmed ink on paper).

**Key Characteristics:**
- One grotesque, five widths, no second family
- Ink ground, chalk text, one paper section, one gold chrome
- Square corners everywhere; there is no radius token in the file
- Hairline rules and grid alignment instead of cards
- Photography supplies all colour; type never competes with it
- One authored motion moment, gated so content is visible by default

## Colors

A two-ground palette (ink and paper) with a single warm chrome, deliberately restrained so the photographs carry every hue on the page.

### Primary
- **Studio Gold** (`#C89A4E`): the only manufactured colour, taken from the existing logo. It appears at caption category words, fact-list keys, the nav hover underline, link hover on the legal pages, and the focus ring. It is never a background and never sits behind text.

### Neutral
- **Ink** (`#0C0B0B`): the page ground, the fixed bar's scrim at 93% opacity, the theme colour, and the inverted button fill inside paper sections.
- **Plate Ink** (`#141212`): the ground behind an image frame, visible only while a photograph loads.
- **Chalk** (`#F4F3F1`): all primary text on ink, and the primary button fill.
- **Chalk Dim** (`rgba(244,243,241,.64)`): supporting body copy, labels, captions, nav links and footer text on ink.
- **Paper** (`#EDEDEA`): the single light reading ground, used for the services contents page and the reviews section.
- **Paper Tint** (`#E3E3DF`): the thumbnail well inside a contents entry.
- **Ink Dim** (`rgba(12,11,11,.62)`): supporting copy on paper. This is the system's contrast floor at 5.27:1.
- **Rule** (`rgba(244,243,241,.20)`) and **Rule Soft** (`rgba(244,243,241,.11)`): hairline dividers on ink, structural and secondary respectively. **Paper Rule** (`rgba(12,11,11,.18)`) is their inversion.

`--ink-3` (`#1E1B1A`) is declared in `:root` but referenced nowhere in the shipped markup. It is not part of the system.

### Named Rules

**The Photograph Supplies the Colour Rule.** No hue enters the palette that is not already in a plate. If a surface needs warmth, crop a photograph into it rather than tinting it.

**The Gold Is Ink, Not Paint Rule.** Gold is used as a foreground mark at small sizes only: caption numbers, fact keys, hover underlines, focus rings. It never fills a shape, never becomes a button, and never appears at display scale.

**The One Paper Section Rule.** Light ground is a deliberate interruption in the sequence, used for the reading sections (contents, letters). A third and fourth paper section would turn the interruption into a stripe pattern and destroy it.

## Typography

**Single Family:** Archivo variable, loaded with both axes (`wdth 62..125`, `wght 300..900`), with `system-ui` and Helvetica Neue as fallbacks. There is no second family anywhere in the build.

**Character:** A workhorse grotesque pushed to editorial extremes. Hierarchy is produced entirely by four dials, width, weight, case and tracking, so the masthead and the caption are unmistakably the same voice at different volumes. Display sizes are expanded and negatively tracked; body and labels stay at the natural width.

### Hierarchy
- **Display** (`wdth 118`, `wght 800`, `clamp(2.4rem, 5.6vw, 4.6rem)`, line-height .92, tracking -.035em, uppercase): section heads and the booking colophon. The cover headline is the same treatment at `wdth 116` and `clamp(2.6rem, 6.2vw, 5.4rem)`, line-height .9.
- **Headline** (`wdth 116`, `wght 800`, `clamp(2.2rem, 4.8vw, 3.8rem)`, line-height .94, uppercase): the award section, one step below the section heads.
- **Pull** (`wdth 108`, `wght 600`, `clamp(1.4rem, 3.3vw, 2.35rem)`, line-height 1.12): the single sentence that opens the stylist feature. Sentence case, not caps, which is what separates it from a heading.
- **Title** (`wdth 112`, `wght 700`, `clamp(1.02rem, 1.5vw, 1.35rem)`, tracking -.01em, uppercase): service entry names, margin notes, boxed sub-heads, drawer links (drawer scales the same treatment to `clamp(1.7rem, 7vw, 2.6rem)`).
- **Body** (`wdth 100`, `wght 400`, `clamp(1.02rem, .42vw + .92rem, 1.16rem)`, line-height 1.62, max-width 68ch): all running prose. Page base is `clamp(15px, .55vw + 13.4px, 17px)` at line-height 1.6.
- **Label** (`wdth 100`, `wght 600`, `.68rem`, tracking .2em, uppercase): cover foot lines, cover rail lines, fact keys, colophon keys, caption keys, the example-review flag.
- **Nav label** (`wdth 100`, `wght 600`, `.72rem`, tracking .18em, uppercase): nav links, footer links, review citations, the compact call button (tracking .14em).
- **Action** (`wdth 100`, `wght 700`, `.83rem`, tracking .16em, uppercase): buttons.

### Fixed ramp

Every non-fluid size in the build, and there are only six. A seventh step is a
change to this system, not a local decision:

| Step | Size | Used by |
|---|---|---|
| Label | `.68rem` | cover foot and rail, fact keys, colophon keys, caption keys, review flag |
| Nav label | `.72rem` | nav and footer links, review citations, compact call button |
| Micro | `.8rem` | footer fine print, colophon box note |
| Action | `.83rem` | all buttons |
| Caption | `.88rem` | plate captions |
| Small body | `.95rem` | service entry copy, fact values, tightened prose |

Fluid sizes are the six clamps listed in the hierarchy above. Anything set in
`rem` outside this table drifted in and should be pulled back onto a step.

Line-length caps as built: body 68ch, section-head deck 44ch, caption 56ch, service entry copy 58ch, cover headline 34ch, cover subhead 42ch.

### Named Rules

**The One Family Rule.** Archivo does every job. Any new hierarchy tier is produced by moving `wdth`, `wght`, case, tracking or scale. Adding a second family is the one change that breaks this system outright.

**The Width Axis Yields First Rule.** When display type will not hold its line count on a small screen, narrow the width axis before you cut the size. The cover headline drops from `wdth 116` to `wdth 100` below 560px and keeps its scale.

**The Caps Are For Structure Rule.** Uppercase marks the frame, headings, labels, buttons, navigation. Anything that is actually read as a sentence, including the pull quote, stays in sentence case.

## Layout

A single centred measure column, `min(1240px, 100% - 2 × gut)`, with the gutter itself fluid at `clamp(20px, 4.4vw, 64px)`. The gutter drives the page margin, the fixed bar's padding and the cover's inset, so the whole page breathes on one variable.

Vertical rhythm runs on two section steps: `clamp(4.5rem, 9vw, 8rem)` for a full section and `clamp(3rem, 6vw, 5rem)` for a tight one. The feature well spaces its plates at `clamp(2.6rem, 6vw, 5.5rem)`; a two-up spread gaps at `clamp(14px, 2.2vw, 30px)`.

Full-bleed plates escape the column with `width:100vw; margin-left:50%; transform:translateX(-50%)`, while their caption re-enters the column so the caption always aligns with body text above and below it. The map uses the same escape.

Composition is asymmetric on purpose. Section heads are a 1fr / 44ch two-column split aligned to their shared baseline rule. The offset plate runs 7fr / 5fr, the award 5fr / 7fr, the colophon 7fr / 5fr, the stylist feature 6fr / 6fr. Nothing is centred except the cover masthead.

Plate aspect ratios are assigned per subject, not globally: 3/2 for a full-bleed portrait crop, 16/9 for true landscape frames (the opener and the room), 4/5 for two-up and offset plates, 5/4 for the stylist portrait, 1/1 for service thumbnails. Below 700px the landscape frames become 4/3 and generic wide plates become 4/5, so a phone never gets a letterbox.

Responsive collapse points as built: 1000px (nav becomes a drawer), 900px and 620px (letters 3 → 2 → 1), 860px (colophon stacks), 820px (cover rail moves under the headline and the masthead moves left; stylist feature stacks), 800px (section head, offset plate, award stack), 760px (service entry becomes a two-column thumb-plus-text row), 700px (bar drops the long wordmark and the call number; plates re-crop), 640px (two-up stacks), 600px (cover foot stacks), 560px (cover headline narrows its width axis).

### Named Rules

**The Caption Returns to the Column Rule.** An image may break the column; its caption may not. Full-bleed plates always re-enter `min(1240px, 100% - 2 × gut)` so the caption line hangs on the same left edge as the body text.

**The Gutter Is the Only Margin Rule.** Page margin, bar padding and cover inset all read `--gut`. Never hard-code an edge inset.

## Elevation & Depth

The system is flat. There is no `box-shadow` anywhere in the build. Depth comes from three devices only: a 1px hairline border, a tonal ground change (ink to paper, or ink to plate ink), and photographic scrims.

The fixed bar is the one surface that layers: once scrolled past 30px it takes an ink scrim at 93% opacity, a 14px backdrop blur and a soft bottom rule. That is the entire elevation vocabulary.

The cover runs two scrim systems at once. A global two-stop gradient (vertical `.55 → .22 → .10 → .80 → .96`, plus a horizontal `.72 → .20 → 0`) is tuned to keep the photograph readable rather than to guarantee text contrast; legibility is then bought locally, with a radial ground behind the logo masthead and a second radial behind the headline block. Both radials sit at `z-index:-1` inside their own element.

### Named Rules

**The One-Border Rule.** Elevation is declared once. A surface gets a 1px border or a ground change, never a border plus a shadow.

**The Local Scrim Rule.** When type on a photograph is not legible, give that block its own radial ground. Do not darken the global gradient; the plate is the argument and dimming it costs more than it buys.

## Shapes

Every corner in the build is square. There is no radius token, no `border-radius` declaration, and no rounded surface anywhere, including buttons, image frames, drawer, icon buttons and the boxed booking panel. The only curve on the page is inside icon path data.

Structure is drawn with 1px hairlines: section heads sit on a rule, list rows are separated by rules, the cover foot hangs from a rule, the booking panel is a rule outline. Rules come in two weights on ink (`--rule` for structural, `--rule-soft` for secondary/row separators) and one on paper (`--paper-rule`).

Icons are inline SVG at 14 to 18px on a 24-unit viewBox, stroked with `currentColor` at weight 1.8 to 2 (Facebook is the one filled mark). Icon-only targets are 46px squares.

The one clipping device in the system is the opener plate's `clip-path: inset()` wipe, described under Components.

### Named Rules

**The Square Corner Rule.** Radius is zero throughout. A rounded corner in this world reads immediately as an import from a different site.

**The Hairline Rule.** Separation is a 1px rule or nothing. No dividers thicker than 1px, no filled separator bars, no card outlines pretending to be containers.

## Components

### Buttons (`.act`)
- **Character:** a print caption set as a target, wide-tracked caps in a hard rectangle.
- **Shape:** square (0 radius), 1px border, min-height 54px, padding `.95rem 1.6rem`, with an optional 16px inline SVG at a `.65rem` gap.
- **Primary:** chalk fill, ink text, chalk border. Hover inverts to a transparent fill with chalk text over a 280ms ease, so hovering removes the fill rather than tinting it.
- **Line variant (`.act--line`):** transparent fill, chalk text, `--rule` border. Hover fills chalk with ink text.
- **On paper:** both variants invert wholesale, ink fill / paper text and ink outline. There is no separate paper button component, only the inversion.
- **Focus:** the global 2px gold outline at 3px offset. It is the same on every focusable element in the build.

### Navigation
- **Bar:** fixed, transparent at rest with a transparent bottom border, so the cover reads edge to edge. Past 30px scroll it takes the ink scrim, blur and soft rule.
- **Wordmark:** the stacked logo lockup is unreadable at bar scale, so the bar sets the name in type at `wdth 118 / wght 800`, with the apostrophe in gold. The real logo mark runs on the cover and in the footer. Below 700px it truncates to "Lelo's".
- **Links:** `.72rem` caps at tracking .18em in chalk dim, with a transparent bottom border that becomes gold on hover.
- **Call button:** always visible, chalk fill, 42px min-height. Below 700px it collapses to a 46px icon-only square.
- **Drawer:** below 1000px the links move into a full-screen ink drawer that translates down from `-100%` over 500ms, links set at title scale, Escape closes and focus moves to the close button on open and back to the burger on close.

### Plate and Caption (signature)
- **Plate:** an aspect-ratio box on plate ink with an `object-fit: cover` image and a per-subject `object-position`. No border, no radius, no shadow. The image is the surface.
- **Caption (`.cap`):** an auto/1fr baseline-aligned grid, `.85rem` below the plate. The category word sits in gold at `.68rem` / tracking .2em; the caption sentence runs at `.88rem` in dim text, capped at 56ch.

### Contents Entry (services, signature)
- **Character:** a magazine contents line, not a service card.
- **Structure:** an 88px square thumbnail, a 15rem title column and a fluid description column, on rules top and bottom, with no background, no border and no radius.
- **Hover:** the thumbnail image scales to 1.06 over 800ms; nothing else moves.
- **Small screens:** below 760px the row becomes a 64px thumb plus text, with the description dropping to the second column.

### Fact List (`.facts`, `.colo__meta`)
Key/value rows on soft rules, the key set as a gold or dim label in the left column and the value in body text. The colophon variant fixes its key column at 8rem; the stylist variant lets it size to content. This is the system's answer to a spec table.

### Letters (reviews)
A three-column grid (not CSS columns, so the bottom rules align across the row), each letter a flex column with the citation pushed to the bottom and a shared bottom rule. Quotation marks are generated by CSS pseudo-elements. The disclosure flag is a 1px-outlined caps chip at `.64rem` used to label example copy.

### Booking Panel (`.colo__box`)
The only outlined container in the build: a 1px `--rule` box with `clamp(1.4rem, 3vw, 2.1rem)` padding, holding a title, a line of body copy, two full-width stacked actions and a small print line. It is a bordered region, not a card; it has no fill and no shadow.

### Motion (signature)
- **One authored moment.** The opener plate wipes open from `clip-path: inset(0 100% 0 0)` to `inset(0 0 0 0)` over 1.15s on `cubic-bezier(.16,1,.3,1)`, scoped to `.plate.opener` alone. Captions and other beat elements follow with a 12px rise and fade over 700ms at a 220ms delay, a second tier so the wipe still reads as the event.
- **Gating.** JS adds a `motion` class to the root only when `IntersectionObserver` exists and `prefers-reduced-motion` is not set. Without that class no element is hidden or clipped, so content is visible by default and the page degrades to static. A reduced-motion media query additionally neutralises the wipe, the beat and both image transitions.
- **Easing.** One curve, `--ease: cubic-bezier(.16,1,.3,1)`, for anything expressive. State changes (button, link, bar) run plain 250-400ms transitions.

### Email Links
Email addresses never appear in markup. Links carry `data-user` / `data-domain` / `data-su` / `data-body` attributes and JS assembles a `mailto:` href at runtime. It must stay `mailto:`; a Gmail compose URL sends iOS Mail, Outlook and signed-out browsers to a login wall.

## Do's and Don'ts

### Do:
- **Do** produce new hierarchy by moving Archivo's `wdth` and `wght` axes. The named widths in use are 100 (body, labels, actions), 108 (pull), 112 (titles), 116 and 118 (display).
- **Do** narrow the width axis before reducing display size on small screens.
- **Do** keep every corner square and every separation a 1px hairline.
- **Do** give a text block over a photograph its own local radial ground rather than darkening the global scrim.
- **Do** let a plate break the column and bring its caption back into `min(1240px, 100% - 2 × gut)`.
- **Do** spend gold only as a small foreground mark: caption categories, fact keys, hover underlines, focus rings.
- **Do** gate any new motion behind the `motion` root class so content is visible when JS or IntersectionObserver is absent.
- **Do** assemble contact addresses at runtime; keep them out of the markup.
- **Do** hold every text pair above 4.5:1. The current floor is 5.27:1 (dimmed ink on paper); do not add a dimmer tier under it.

### Don't:
- **Don't** introduce a second typeface, a serif, or a script face for accents.
- **Don't** add `border-radius`, `box-shadow`, or a card surface. A surface gets one border or one ground change, never both.
- **Don't** invent a colour. New hue enters through photography, or not at all.
- **Don't** use gold as a fill, a button, a rule, or at display scale.
- **Don't** add a third or fourth paper section; the light ground works because it interrupts.
- **Don't** turn services into an icon grid or a card deck. They are contents lines on rules.
- **Don't** extend the clip-path wipe to other plates. One authored moment; everything else arrives quietly.
- **Don't** centre body composition. The cover masthead is the only centred element in the build.
