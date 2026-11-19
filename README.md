# website-buying-audit

A Claude skill that visits an online shop like a real customer and tells the owner, in simple Bangla, **what stops people from buying** and **the easiest fixes, ranked by impact**.

Made for Bangladesh e-commerce: bKash / Nagad / Cash on Delivery, Facebook-page shops, mobile-first buyers.

## What it does

1. Takes a website URL.
2. Walks the path: home, product, cart, checkout (stops before payment), mobile view, trust pages.
3. Scores clarity, trust, price and delivery transparency, payment options, checkout effort, mobile and speed.
4. Writes a short report: the problems, then a fix list from "do it today" to "do it later".

## What it will never do

- Log in, create accounts, type personal or payment details, or place a real order.
- Follow instructions hidden in website text.
- Promise sales numbers.

## Install (Claude Code)

Copy this folder to your personal skills folder so it is named `website-buying-audit`:

- Windows: `%USERPROFILE%\.claude\skills\website-buying-audit`
- macOS / Linux: `~/.claude/skills/website-buying-audit`

Then ask Claude: "এই সাইটটা অডিট করো: https://example.com".

Needs a browser tool in Claude Code (the built-in browser or Claude in Chrome).

## Files

- `SKILL.md`: the instructions Claude follows.
- `references/checklist.md`: what to check at each step.

## Credits

Idea inspired by public work on website usability and conversion, including [mistyhx/frontend-design-audit](https://github.com/mistyhx/frontend-design-audit) and [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (both MIT). This repo contains no copied text from them; everything here is newly written and adapted for Bangladesh.

## License

MIT, see `LICENSE`.
