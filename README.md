# 📡 Channel Check — a Claude Code skill that validates the CHANNEL, not the idea

Most founders validate demand and never validate reach: they prove people HAVE
the problem, then discover nobody can be told the solution exists. This skill
turns Claude Code into a distribution pathologist: it enumerates the channels
where your idea's users actually stand, runs live reachability checks with plain
web search (no API keys, no paid tools), grades each channel **WINNABLE /
SATURATED / DEAD** with evidence — and names the ONE launch channel, or a KILL.

Companion to **[Idea Autopsy](https://github.com/hafiz-actyte/idea-autopsy)**
(kills the idea) — this one kills the launch plan. I post the checks here:
**[YouTube @actyte](https://www.youtube.com/@actyte)** · **[Instagram @hafiz.actyte](https://www.instagram.com/hafiz.actyte/)** · **[LinkedIn](https://www.linkedin.com/in/hafizsiddiq15/)**.

## Install

**As a Claude Code plugin (recommended):**

```
/plugin marketplace add hafiz-actyte/channel-check
/plugin install channel-check@channel-check
```

**Or plain clone (works for any harness that reads skills folders):**

```bash
git clone https://github.com/hafiz-actyte/channel-check /tmp/channel-check \
  && cp -r /tmp/channel-check/skills/channel-check ~/.claude/skills/
```

Then, in any project:

```
check the channel for: <describe the idea>
```

## What it does

1. **Names the buyer and the search moment** — who the user is and the EXACT
   words they type when the pain hits. Can't name the phrase? That's finding #1.
2. **Enumerates 3–6 candidate channels** — App Store/Play search, Google SEO,
   Reddit, X, Instagram/TikTok, YouTube search, marketplaces/directories.
3. **Live reachability checks, free web only** — App Store rating counts as
   install proxies, SERP ownership, subreddit sizes and self-promo rules, top
   YouTube view counts, who owns each channel today. Every claim gets a number
   fetched during the check — no numbers from memory.
4. **Per-channel verdict** — WINNABLE / SATURATED / DEAD, one evidence line each.
5. **The scorecard** — the ONE launch channel plus the first concrete move you
   can test THIS WEEK before writing code, or KILL: no winnable channel = don't
   build it.

See **[EXAMPLE.md](EXAMPLE.md)** for a real, unedited run — an idea that
survived demand validation and still lost 3 of its 6 channels.

## Why check channels?

Building was never the problem — AI builds anything in a weekend now. And demand
research answers the wrong question: it tells you people are in pain, not
whether you can stand where they're searching. A channel owned by free
incumbents is closed no matter how good your product is. The check costs 20
minutes; shipping into a dead channel costs 3 months.

## Files

- `skills/channel-check/SKILL.md` — the check procedure Claude follows
- `EXAMPLE.md` — a full real run with live numbers, scorecard and verdict

## Watch checks and autopsies

One idea examined per week — comment yours; the most-liked one gets checked on
camera:

- YouTube: [@actyte](https://www.youtube.com/@actyte)
- Instagram: [@hafiz.actyte](https://www.instagram.com/hafiz.actyte/)
- LinkedIn: [Hafiz Siddiq](https://www.linkedin.com/in/hafizsiddiq15/)

MIT license. PRs welcome — especially channel checks that proved a verdict wrong,
with receipts.
