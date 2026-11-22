# AGENTS.md — jonathanmccallum-tl (Tagalog (Filipino) mirror of jonathanmccallum.com)

Tagalog (Filipino) mirror site. Same theme and design as the main site (Paper Light),
content translated into Tagalog (Filipino), meaning-first. Repo: streamjonathan/jonathanmccallum-tl.
Live (when approved): tl.jonathanmccallum.com. Proof: jonathanmccallum-tl.pages.dev.

## Mission

Mirror jonathanmccallum.com in Tagalog (Filipino) — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Tagalog (Filipino) site goes live on tl.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Register: direct address is ikaw / ka / mo throughout (warm, friend-to-friend,
  no "po"). FLAG for Jonathan: ikaw vs kayo (+ po) touches every article — if
  he prefers kayo, every ikaw/ka/mo becomes kayo/ninyo. Short plain sentences,
  no preaching, no "dapat" / "kailangan" commands.
- Names (never vary): Jesus (not Hesukristo), Diyos, Adan at Eba, Aslan, Narnia,
  Lucy, Digory, Tirian, Peter (unchanged). Book titles: Ang mga Kronika ng
  Narnia, Ang Pamangkin ng Mago, Ang Dakilang Paghihiwalay, Ang Trilohiya sa
  Kalawakan, Ang Huling Labanan.
- Bible verses: no direct verse quotations appear in these 5 articles. The
  bread/water of life lines are Jonathan's paraphrase — tinapay ng buhay /
  tubig ng buhay — never quoted as Scripture. No direct Lewis quotations either.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
