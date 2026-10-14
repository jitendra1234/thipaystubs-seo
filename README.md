# Thi Pay Stubs — SEO text

This repo holds the SEO text for **thipaystubs.com**: page titles, meta descriptions, H1 headings,
the SEO section and FAQs at the bottom of each page, and the template for the 50 state paycheck
calculator pages.

## How to edit

**Easiest:** go to **https://thipaystubs.com/admin**, sign in with GitHub, change the text, and click
**Publish**.

**Or on GitHub:** open `seo.json`, click the pencil (Edit), change the text, and **Commit changes**.

The website rebuilds automatically and your change is live in about **3–5 minutes**.

## Rules

- Change the **text** only. Do not rename or delete keys (`title`, `description`, `h1`, page names…).
- `url` is for reference only — page addresses are changed by the developer.
- In the state pages section, `{state}` is replaced by the state name ("Texas").
- Best lengths: **title up to 60 characters**, **description up to 160**. Longer text works but Google
  may cut it off. Hard limits: title 75, description 200, H1 80.
- Plain text only — no HTML.
- Words like "fake", "forged", "novelty" or "proof of income" are not allowed (they misdescribe the
  product and put our payment accounts at risk).

## If your change does not appear

Every update is checked before it goes live. If something is wrong (too long, missing, a blocked
word, or broken JSON), the update is **rejected** and the site keeps showing the previous version.
Ask the developer for the check's error message, or check the **Actions** tab of this repo for the
JSON check.
