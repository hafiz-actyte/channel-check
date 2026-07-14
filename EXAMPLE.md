# Example run — a real channel check, unedited

Test idea, checked live on **2026-07-14** with nothing but web search and web
fetch (no API keys, no paid tools):

> **"A note-taking app built around the #1 complaint in a popular note app's
> one-star reviews."**

## Step 0 — Buyer and search moment

First, find the complaint. Cross-checking review roundups and low-star review
analyses: **Notion's most persistent low-star complaint has been the lack of a
true offline mode** — cloud-first, locked out of your notes on a flight or an
outage. (Evernote's one-star pile is bigger but scattered: sync data loss, the
$59→$249 pricing hike, the Electron-rebuild performance collapse. Notion's is
one clean, recurring wound.)

So the derived idea is an **offline-first note app for Notion users**, and:

- **BUYER:** a Notion user on a plane/train whose pages won't load
- **SEARCH MOMENT:** types **"notion offline mode"** / **"notion offline
  alternative"** into Google, YouTube, or the App Store

Note the tense above: "has been." That word is where this idea dies. Every
check below hit the same wall — and the wall has a version number.

## Step 2 — Live checks (what actually came back)

**App Store search** — Apple's free search API. For `notion offline`, the top
hit is **Notion itself (88,307 ratings)** — the incumbent now answers the
buying keyword directly, because it shipped the feature. For `offline notes`,
the keyword is owned by Apple Notes (611,922 ratings) and Goodnotes (434,770),
with Obsidian, Simplenote and Standard Notes — all free — stocking the rest of
the page. The exact positioning is already shipped, at $0, under
600K-rating giants.

**Google SEO** — the SERP for the buying keywords is a **Zapier/XDA/itsfoss
listicle wall**, and **AFFiNE — a free open-source Notion alternative — already
ranks its own "offline Notion" comparison posts**. The
write-the-comparison-post play isn't open; it's being run by an incumbent
whose product costs nothing.

**Reddit** — direct reddit.com fetches are 403-blocked (as the skill warns),
and the stats sites lie by omission: search-snippet sources (subredditstats)
quoted **346K members for r/Notion**, but the live sidebar (verified in-browser
2026-07-14) says **115K** — third-party stats ran 3x stale, which is exactly
why the skill grades on what the page shows today. The sub is reachable for a
founder with a genuine build log — but reachable isn't winnable: the standing
answer in its recommendation threads is **free Obsidian or Anytype**, and the
complaint you'd be answering was **patched by Notion itself**.

**YouTube search** — the exact query no longer surfaces unserved demand. The
results are dominated by **"Notion Offline Mode Is Here!" (Aug 2025)
tutorials** — the platform is busy teaching users the feature that was supposed
to be your product. That's not a content gap; it's the pain's obituary,
on camera.

**Product Hunt** — this exact launch already happened, and someone else won it:
**Anytype** took **#1 product of the week, a 2023 Golden Kitty, and holds 4.9/5
across 104 reviews**. Free and open-source. The launch-day spike isn't
available; it's spent.

**Instagram/TikTok** — skipped: the buying moment here is a typed search
("notion offline mode"), not a feed scroll. **X** — skipped: login-walled, and
unmeasurable is never winnable.

## The scorecard

```
CHANNEL CHECK: offline-first note app for Notion users
BUYER: Notion user on a plane/train whose pages won't load — types "notion offline mode"
       / "notion offline alternative"

App Store search   SATURATED   "notion offline" top hit is Notion ITSELF (88,307 ratings);
                               "offline notes" owned by Apple Notes (611,922) and Goodnotes
                               (434,770), with Obsidian/Simplenote/Standard Notes free below
Google SEO         SATURATED   Zapier/XDA/itsfoss listicle wall — and AFFiNE already ranks
                               its own "offline Notion" comparison posts
Reddit             SATURATED   r/Notion reachable (115K members, live sidebar — not
                               subredditstats' stale 346K), but the rec-thread standing
                               answer is free Obsidian/Anytype, and Notion patched the
                               complaint itself
YouTube search     DEAD        exact-query results dominated by "Notion Offline Mode Is
                               Here!" (Aug 2025) tutorials — the pain's obituary, on camera
Product Hunt       SATURATED   Anytype already won this launch: #1 of the week, 2023 Golden
                               Kitty, 4.9/5 across 104 reviews
Instagram/TikTok   skipped     the buying moment is a typed search, not a feed
X                  skipped     login-walled — unmeasurable is never winnable

VERDICT: KILL
THE ONE SENTENCE: Notion shipped native offline mode (v2.53, Aug 19 2025, all plans
  including Free) — the core pain no longer exists — and the residual "local-first
  Notion" wedge is owned by four FREE open-source incumbents (Obsidian, Anytype,
  AppFlowy, AFFiNE) you cannot out-price.
FIRST MOVE: none — no winnable channel means don't build it.
```

One salvageable thread surfaced during the run: **"notion offline database
limit"** still has live complaint traffic — Notion's offline mode caps synced
databases, and people search the limit. That's content-SEO demand for a
**Notion companion/plugin audience** — a different buyer, a different idea, and
it gets its own check before anyone builds anything.

Note what happened: the idea SURVIVED demand validation — the pain was real,
recurring, documented in thousands of reviews — and a shallow pass over these
same channels even looked winnable. The deeper run killed it twice over: the
incumbent patched the pain (a fact with a version number and a ship date), and
every residual door is held by free open-source products you can't out-price.
A demand doc full of last year's complaints validates last year's idea. The
check costs 20 minutes; the KILL cost $0. **Validate the channel, not the
idea.**
