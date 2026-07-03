# Capital Drive Co. — rentals site

One-file static site (`index.html`). No build step, no dependencies.

## Preview it right now
Double-click `index.html` — it opens in your browser fully working.

## Before going live — replace the placeholders (search "TODO" in index.html)
1. **Business name** — "Capital Drive Co." is a placeholder; rename to whatever you register/DBA.
2. **Phone + email** — in the footer and in the `<script>` at the bottom (`OWNER_EMAIL`).
3. **Turo listing links** — TODO-TURO-URL-1 and -2 (paste your live listing URLs).
4. **Photos** — make an `img/` folder next to index.html, drop in `escalade.jpg` and `gle.jpg`
   (use your best Turo listing photos), and swap the placeholder divs for the `<img>` tags
   shown in the comments.
5. **Form** — create a free form at formspree.io, paste the form ID into the form's
   `action` URL, and set `FORM_CONFIGURED = true` in the script. Until then, the form
   opens the visitor's email app addressed to you (works, just less smooth).

## Put it online (free, ~5 minutes)
Easiest: **Netlify Drop** — go to https://app.netlify.com/drop and drag this whole folder
onto the page. You get a live URL instantly; connect a custom domain later ($10–12/yr
at any registrar).

Alternative: Vercel — create a free account, "Add New Project", drag the folder in the
dashboard, done.

## Legal guardrails already built in (don't remove)
- Self-drive rentals only — NO chauffeur offering (requires VA for-hire authority you don't hold yet).
- Renter requirements section: 25+, license, proof of insurance, signed agreement, deposit.
- Footer disclaimer: written agreement + verification required, availability not guaranteed.

## Before you take your FIRST direct booking (not optional)
1. Confirm with your insurance agent IN WRITING that your commercial policy covers
   direct (non-Turo) rentals. Many Turo-host policies cover platform trips only.
2. Have a written rental agreement ready to sign (ask Claude to draft one next).
3. Photograph license + insurance card of every renter; card hold for the deposit.
