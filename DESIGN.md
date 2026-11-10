---
version: alpha
name: Angold Engineering
description: A released engineering sheet for a California mechanical PE. Ink, gold, and bond paper on a steel board.
colors:
  primary: "#15181C"
  on-primary: "#F7F6F3"
  secondary: "#4A535B"
  tertiary: "#D9A527"
  tertiary-hover: "#C4921A"
  on-tertiary: "#15181C"
  neutral: "#F7F6F3"
  board: "#C5CAD0"
  surface: "#FFFFFF"
  line: "#C9CDD2"
  line-soft: "#E2E4E7"
  accent-ink: "#5C430C"
  board-line: "#A8B0B7"
  board-dark: "#0C0F12"
  neutral-dark: "#161A1E"
  surface-dark: "#1E252C"
  primary-dark: "#F3F5F7"
  secondary-dark: "#C5CED4"
  line-dark: "#3A434C"
  line-soft-dark: "#2A3238"
  accent-ink-dark: "#E4C36A"
  board-line-dark: "#2A3138"
typography:
  display:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: 4.15rem
    fontWeight: 800
    lineHeight: 0.94
    letterSpacing: -0.02em
  headline:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: 1.6rem
    fontWeight: 800
    lineHeight: 1
    letterSpacing: 0.01em
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: 1.15rem
    fontWeight: 650
    lineHeight: 1.3
    letterSpacing: 0em
  deck:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: 1.05rem
    fontWeight: 650
    lineHeight: 1.35
    letterSpacing: 0em
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0em
  label:
    fontFamily: "Azeret Mono, ui-monospace, SF Mono, Consolas, Menlo, monospace"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: 0.04em
rounded:
  none: 0px
spacing:
  2xs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  section: 52px
  sheet: 1120px
components:
  button-primary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-tertiary}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    height: 44px
    padding: 18px
  button-primary-hover:
    backgroundColor: "{colors.tertiary-hover}"
    textColor: "{colors.on-tertiary}"
  button-secondary:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    height: 44px
    padding: 18px
  button-secondary-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
  button-secondary-dark:
    backgroundColor: "{colors.neutral-dark}"
    textColor: "{colors.primary-dark}"
    rounded: "{rounded.none}"
    height: 44px
  button-secondary-dark-hover:
    backgroundColor: "{colors.primary-dark}"
    textColor: "{colors.neutral-dark}"
  sheet:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: 22px
  sheet-dark:
    backgroundColor: "{colors.neutral-dark}"
    textColor: "{colors.primary-dark}"
    rounded: "{rounded.none}"
    padding: 22px
  header:
    backgroundColor: "{colors.board}"
    textColor: "{colors.primary}"
    height: 64px
  header-rule:
    backgroundColor: "{colors.board-line}"
    height: 1px
  header-dark:
    backgroundColor: "{colors.board-dark}"
    textColor: "{colors.primary-dark}"
  header-rule-dark:
    backgroundColor: "{colors.board-line-dark}"
    height: 1px
  link:
    textColor: "{colors.accent-ink}"
    typography: "{typography.body}"
  link-dark:
    textColor: "{colors.accent-ink-dark}"
    typography: "{typography.body}"
  label:
    textColor: "{colors.accent-ink}"
    typography: "{typography.label}"
  label-dark:
    textColor: "{colors.accent-ink-dark}"
    typography: "{typography.label}"
  lede:
    textColor: "{colors.secondary}"
    typography: "{typography.body}"
  lede-dark:
    textColor: "{colors.secondary-dark}"
    typography: "{typography.body}"
  case:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: 18px
  case-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.primary-dark}"
    rounded: "{rounded.none}"
    padding: 18px
  hairline:
    backgroundColor: "{colors.line}"
    height: 1px
  hairline-soft:
    backgroundColor: "{colors.line-soft}"
    height: 1px
  hairline-dark:
    backgroundColor: "{colors.line-dark}"
    height: 1px
  hairline-soft-dark:
    backgroundColor: "{colors.line-soft-dark}"
    height: 1px
  dimension-tick:
    backgroundColor: "{colors.tertiary}"
    width: 28px
    height: 3px
  titleblock:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: 12px
  note:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    rounded: "{rounded.none}"
    padding: 16px
---

## Overview

Angold Engineering should look like a drawing that was released, not like a software marketing page. The reader is a plant manager or a contractor with a machine that has to keep running. The page is one sheet of bond paper sitting on a steel board, with a double rule, a title block, and gold used the way a shop uses it: on the mark, on a witness line, and on the one action that starts the job.

The voice is already written. It is specific, a little dry, and willing to name the unglamorous part (a file hash, a datum, a pit in a bag). Agents keep those sentences. They do not punch them up, and they do not sand the em dashes out of them.

Imagery is the mark and the sheet. The mark is a gold hexagon stroke around an A, taken from the firm stamp. It is drawn in SVG. There are no stock photos, no generated people, no isometric plants, and no decorative icon tiles. A later project article can carry a photograph only when a real one is supplied. Until then, the sheet stays typographic.

The system is ready for a project article without a new palette: the same sheet, one `h1`, a spec header (scope, problem, outcome), and body text at the reading measure. That page is not part of the homepage. Do not invent its facts.

## Colors

Light is the default. Dark follows `prefers-color-scheme` and the same roles. Gold is a material, not a text color, except where the pair clears WCAG AA.

- **Ink, primary (`#15181C`).** Headlines, rules, the sheet border, and text on the gold button. In dark mode the ink flips to `#F3F5F7` and the sheet border flips with it.
- **Bond, neutral (`#F7F6F3`).** The sheet. Cool, not beige. The body background is not this color.
- **Board (`#C5CAD0`).** The table the sheet sits on, and the sticky header. Dark board is `#0C0F12`.
- **Surface (`#FFFFFF` / `#1E252C`).** Spec cards and the title block, one step off the sheet.
- **Secondary (`#4A535B` / `#C5CED4`).** Body that is supporting, not headlines. Both pairs are above 7:1 on their sheet.
- **Gold, tertiary (`#D9A527`).** The hex stroke, the 3px witness tick, and the primary button fill. Hover is `#C4921A`. Button text on gold is always `#15181C`, in both themes (7.9:1, 6.3:1 on hover).
- **Brass, accent-ink (`#5C430C` / `#E4C36A`).** Small labels that need to be gold-family and still readable. Do not set 12px type in `#D9A527` on bond. That pair is about 2:1.

## Typography

Two faces, and a system face for reading. Do not add a third webfont.

- **Display.** Archivo, weight 800 only. That is the file that is embedded. Use it for the `h1`, section titles, the ethos line, and the contact pitch. Uppercase, tracking no tighter than `-0.03em` and no looser than `0.01em` on a heading. `text-wrap: balance`. The `h1` tops out at `4.15rem` and drops to `1.8rem` below 340px so "ENGINEERING" stays inside the sheet border.
- **Reading face.** The system UI stack, 17px, line-height 1.55. It is not Inter, Roboto-as-a-brand, or any other default. `text-wrap: pretty`. Measure stays near 64 characters.
- **Annotation.** Azeret Mono, weight 500, 12px minimum, tracking `0.04em`. Only for the title block, revision line, spec labels (Scope, Problem, Outcome), and the short capability stamps. Not for navigation, not for buttons, not for paragraphs.

Nothing functional is smaller than 12px. Navigation and buttons are 13–14px, at least 44px tall.

## Layout

The page is one centered sheet, max 1120px, with 10px of board visible at the viewport edge so the double rule can be seen. Desktop hero is two columns: the statement, then the title block, bottom-aligned. Below 800px the title block stacks under the actions. It is never removed.

Sections are stacked notes, not cards-in-cards. A section title sits on a 1px rule with a 28×3px gold tick at the left of the rule. Space above a heading is larger than the space between the heading and its first line.

Capabilities are rows: a 12px stamp in the left column, the title and paragraph in the right. On a narrow screen the stamp drops under the title, never above it. Selected work is a spec table. Industries are one line of names, not chips. Contact is the same section header as the others, then the pitch, then the assembled email and phone.

A future article uses the same sheet and the same spec header. It does not get a hero grid, a new display face, or a second accent.

## Elevation & Depth

Flat. The sheet is separated from the board by the double rule (2px ink, 6px of bond, 1px ink), not by a shadow. Spec blocks are a white (or dark-panel) fill with a 1px ink border. Hover on a button changes fill. Hover on a note that is not a link does nothing. There is no blur, no glass header, and no drop shadow.

## Shapes

Corners are square (`0px`). The only non-rectangular form is the hexagon in the mark, and it stays the mark. Do not clip paragraphs into hexes, shields, or circles. The old capability cells did that and cut the last lines off.

The one motion is the gold tick under the `h1`, a 0.55s scale from the left with an ease-out. It does not run when `prefers-reduced-motion` is set. Content is visible with JavaScript off. The contact script only assembles the address and the phone number.

## Components

### Header

Sticky on every width, on the board, not on the sheet. Wordmark left. Phone right, filled by the same script as the contact block, linking to the contact anchor until the script runs. Four text links, 44px tall. Below 640px the phone stays on the wordmark row and the links wrap as their own row.

### Buttons

Primary is gold fill, ink text, square, uppercase, 44px tall. It is the only filled gold rectangle on the page. Secondary is a 1px ink outline. Both are real actions: start a project, see the work. The phone is a text link, not a third button.

### Title block

Five rows: Firm, Sheet, Rev, Scale, Status. 2px outer rule, 1px internal rules, 12px labels, 14px values. Visible at every width, including under the hero actions on a phone.

### Capability row

Title, then the mono stamp, then the paragraph. The stamp is a label, not an icon tile, and it does not sit above the heading.

### Spec case

A bordered block. Header holds the job name and the client category. Rows are Scope, Problem, Outcome. A case with no Problem row stays a two-row case. Do not invent the missing row.

### Note

The production-down note is a 1px ink box with 16px of padding. The strong words are ink, not gold.

### Focus, selection, type

Focus is a 2px ink outline, offset 3px, so it clears on both bond and gold. Selection is gold with ink text. The system scrollbar uses the steel and the board.

## Do's and Don'ts

These are for agents editing this repo.

- Do keep the page one static `index.html` document, with the two embedded faces and no framework, no build step, and no new network request.
- Do reuse the sheet, the double rule, the title block, the spec rows, and these tokens on any new page. A project article is that sheet plus one story. It does not get its own theme.
- Do keep every existing sentence, including the em dashes, the footer line, and the four industries. The em-dash advisory from a slop detector is not a license to rewrite the copy.
- Do keep client categories as written: "California dried-fruit processor" and "Utility-scale solar contractor". The third case is "Food processor".
- Do keep the phone and email out of the static source. The script assembles them. A new link to the phone uses that script.
- Do keep contrast at WCAG AA: 4.5:1 for text, 3:1 for the focus ring and for large type. Gold `#D9A527` is a fill and a stroke, not small type on bond.
- Do keep hit targets at least 44px high, and type at least 12px.
- Don't set the page background to warm cream or beige (`#F5F3EF` and its neighbors). That was the old sheet, and it reads as the default generated page. Bond is `#F7F6F3`. The board is steel.
- Don't draw a CSS graph-paper grid, a purple or blue gradient, a glass blur, or a mesh background.
- Don't put a tiny tracked label above a heading. No eyebrows, no "SEC 01". If the words matter, they go under the heading or beside it.
- Don't number sections for decoration.
- Don't use monospace to make ordinary UI look technical. Mono is for sheet data.
- Don't clip text with `clip-path`. Don't build a row of equal icon-plus-heading cards.
- Don't use a thick colored bar on the left of a quote, a card, or a list.
- Don't introduce Inter, Roboto as a brand face, Space Grotesk, DM Sans, or a serif display. Archivo 800 is the display face. The reading face stays the system stack.
- Don't add a second accent. Green, red, and blue do not enter unless a real status needs them, and even then they are not the brand.
- Don't invent facts, counts, testimonials, response times, license numbers, or client names. Do not write Traina or NextPower. Do not mention a security clearance. Do not add the unpublished project story, its dollar figure, or any yield or grant figure.
- Don't add schema, a sitemap, or social cards in a visual pass unless the copy they point at is already on the page. Preserve the title, description, canonical URL, and Open Graph tags that are already in the head.
