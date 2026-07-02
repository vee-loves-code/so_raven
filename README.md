# So Raven — Catering & Personal Chef Website

A fast, SEO-optimized one-page site for **So Raven Catering & Personal Chef Services**
(Charlotte, NC & Greenville, SC). Plain HTML/CSS/JS — no build step.

```
raven-donae-chef/
├── index.html          # all content + SEO meta + FoodEstablishment schema
├── css/styles.css      # red & black brand styling (responsive, animated)
├── js/main.js          # nav, scroll reveals, count-up stats, form UX
├── assets/img/         # placeholder images (SWAP THESE — see below)
├── netlify.toml · robots.txt · sitemap.xml
```

## Preview locally
```bash
cd raven-donae-chef
python3 -m http.server 8080   # then visit http://localhost:8080
```

## Deploy to Netlify (2 minutes, free)
1. Go to https://app.netlify.com/drop
2. Drag the whole `raven-donae-chef` folder onto the page → instant live URL.
3. Site settings → *Change site name* → `soraven` → live at `https://soraven.netlify.app`.

The **order/booking form works automatically on Netlify** (Netlify Forms).
Submissions appear under *Forms* in the dashboard; add email alerts there.

## Real details already baked in (verified on her Instagram @so.raven_)
- **Brand:** So Raven (full: So Raven Catering & Personal Chef Services)
- **Chef:** Raven Latimore
- **Tagline:** "Comfort food, with a little luxury" (her own words)
- **Location:** Charlotte, NC & Greenville, SC
- **Contact:** (864) 404-8777 (call/text) · soraven825@gmail.com
- **Services:** Weekly Meal Prep · Athlete/Fitness Prep · Private Dining · Full-Service
  Catering · Personal Chef for Travel · Diabetic-Friendly Meals
- **Meal-prep pricing:** Basic $100 (5) · Standard $160 (10–15) · Couples $175 (5–15) ·
  Family $180 (3–7) · Weekly special: 6 meals $90
- **Menu (from her real posts):** Lamb Chops & Pasta, Honey Garlic Shrimp, Jumbo
  Loaded Potato, Marry Me Chicken, Blackened Salmon Alfredo, Signature Salmon Plate
- **Reviews:** two real client quotes (Shenee's salmon plate + "…made me feel like I made it!").

## Images — still placeholders (on purpose)
Her Instagram is mostly Reels with marketing text baked into the frames, so there are
no clean, text-free food photos to pull in. Best options, in order:
1. Ask Raven for her original photos (no text overlay) → drop into `assets/img/`
   using the filenames `hero.jpg`, `about.jpg`, `dish-1…6.jpg`, `gram-1…6.jpg`.
2. Or use licensed stock photos of the matching dishes as a stand-in for the pitch.

## Before you pitch — quick swaps (search the code for `REPLACE`)
- **Images** — replace the files in `assets/img/` with real photos from her Instagram
  (keep the same filenames and they just work).
- **⚠️ Confirm her Instagram handle** — I used `so.raven_` (the reply box in your
  screenshot was cut off at `so.raven_…`). If the full handle is different, search
  `so.raven_` in `index.html` and fix all links.
- **Double-check pricing/menu** against her current offers before it goes live.
