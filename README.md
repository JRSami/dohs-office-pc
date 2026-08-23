# Dhaka Office PC Sourcing

A single-page buying guide for equipping one office staff desk in Dhaka — desktop, mini PC or laptop, plus monitor, UPS and the software licence, with retail prices in taka.

Written for a small business kitting out a staff member who spends the day in Excel, Word, email and a database front-end.

**Live page:** `https://<your-username>.github.io/<repo-name>/`
_(fill this in after you enable Pages — see below)_

---

## What's in the repo

| File | What it is |
|---|---|
| `index.html` | The whole guide. Self-contained — no build step, no dependencies, no JavaScript framework. Open it in any browser. |
| `scorecard.html` | Interactive scorecard. Set how much price, speed, memory, warranty, availability and the rest matter to you, and thirteen machines re-rank live. |
| `README.md` | This file. |

The two pages link to each other, so uploading both gives you a small two-page site.

The page is a single HTML file with the CSS inlined. The only external request is to Google Fonts for two typefaces, and it degrades to system fonts if that's blocked. It follows the reader's light/dark preference and has a manual toggle in the top right.

---

## Publishing it on GitHub Pages

### Option A — through the GitHub website (no command line)

1. Go to <https://github.com/new> and create a repository. A public repo is required for free GitHub Pages. Name it something like `dhaka-office-pc-guide`.
2. On the empty repo page, click **uploading an existing file**.
3. Drag in `index.html`, `scorecard.html` and `README.md`, then click **Commit changes**.
4. Go to **Settings → Pages** in that repo.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**. Set the branch to `main` and the folder to `/ (root)`. Click **Save**.
6. Wait about a minute, then reload the Settings → Pages screen. Your URL appears at the top: `https://<your-username>.github.io/<repo-name>/`

That URL is the link you share. Anyone can open it — no GitHub account needed on their end.

### Option B — from the command line

```bash
cd dhaka-office-pc-guide
git init
git add .
git commit -m "Dhaka office PC sourcing guide"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then follow steps 4–6 above to turn Pages on.

### Updating it later

Edit `index.html`, commit, and push. GitHub Pages redeploys automatically, usually within a minute. The URL never changes, so a link you've already shared stays current.

```bash
git add index.html
git commit -m "Update monitor prices, checked 12 September"
git push
```

---

## Keeping the prices honest

Every figure in the guide is a Bangladeshi retail listing collected on **21 August 2026**. Hardware prices in this market move week to week, and memory and SSD prices are unusually volatile right now — treat everything as indicative, not as a quotation.

If you correct a figure, please note the date you checked it in the commit message. That way anyone reading the page later knows how stale it is.

**Sources used:** [Star Tech](https://www.startech.com.bd/), [Ryans](https://www.ryans.com/), [TechLand BD](https://www.techlandbd.com/), [BDStall](https://www.bdstall.com/), [Eastern IT](https://www.eit.com.bd/desktop), [Qbits](https://qbits.com/), [Tofa](https://tofa.com.bd/), [Pickaboo](https://www.pickaboo.com/), [Daraz](https://www.daraz.com.bd/), [LKEY](https://lkey.info/) for Microsoft and Google licensing.

## A note on scope

This is one person's research write-up, not a sponsored comparison and not a substitute for a quotation from a shop. No retailer or brand mentioned had any input into it. Prices for the same item genuinely differ between shops in Dhaka — check two before you buy.

## Licence

Text and layout are free to reuse and adapt. Please keep the "prices as of" date visible if you republish it, so readers can judge how current it is.
