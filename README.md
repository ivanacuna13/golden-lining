# Golden Lining Corpus

## What this is

A research and strategy corpus for **Kush Nathu's Golden Lining YouTube channel**, assembled by Ivan Acuna in September 2026 to ground a channel strategy and launch.

It contains the raw materials — not the finished strategy. The finished work (10 launch concepts, reference thumbnails, audio briefings) lives in a separate strategy artifact; this repo is the evidence underneath it, packaged so another AI or strategist can pick up the project cold.

## The project

**Golden Lining** is the brand/channel of Kush Nathu, a hotel and real-estate operator.

On **September 16, 2026**, Ivan Acuna, Haziel Luna, and Kush Nathu held a strategy call to set a new direction for the channel. Ivan's work since then:

1. Pulled and normalized **214 video transcripts** (~178,000 words) from the actual Golden Lining channel (`UC1nhg-YVVbaSdLFiFYhx_bw`) — 7 hashtag Shorts could not be recovered.
2. Synthesized **CHANNEL_BRAIN.md** — an evidence record of what the *old* channel was: what to keep, what to quarantine. Built from the channel itself, not the strategy call.
3. Built 12 strategy context documents (audience, pain points, messaging, offer, content pillars, funnels, voice, competitive landscape).
4. Drafted **10 launch video concepts** ("Golden Lining Strategy Corpus"), each mapped to a proven reference video with its real thumbnail, plus audio briefings.

### The controlling strategic correction

On September 23, Ivan corrected the framing: **hotels are the vehicle, not the topic.** The channel should teach broad business/operator lessons that solve the audience's problems; Kush's hotel experience supplies the proof, stories, and examples — it should not automatically appear in titles. Only content drawn directly from Kush's history necessarily foregrounds hotels.

## What's in this repo

| Path | Contents |
|---|---|
| `CHANNEL_BRAIN.md` | Evidence record of the old channel — what to keep, what to quarantine |
| `context/` | 12 strategy docs: master index, client profile, ICP profiles, pain points & objections, messaging & verbiage rules, offer & positioning, content pillars & frameworks, funnels & CTA, voice & tone profile, competitive landscape, deliverables roadmap, collection checklist |
| `transcripts/` | 214 normalized YouTube transcripts (~178K words) |
| `manifest.json` | Full video manifest (IDs, titles, word counts) |
| `transcript_stats.json` | Per-video word counts |

## What it's for / how to use it

Hand this repo to an AI (or a strategist) so it can:

- Understand the channel's history and what the old content actually was (channel brain + transcripts).
- Understand the audience — ambitious operators roughly in their 20s to early 40s who want ownership but lack an operator's lens — plus the secondary audience of established operators, developers, and capital allocators. Never combine both audiences into one video promise.
- Generate on-brand content ideas, scripts, or packaging that follow the strategy: broad operator lessons, hotels as proof/vehicle.
- Audit new ideas against the messaging rules, voice profile, and quarantine list.

## Known caveats

- The **strategy-call transcript itself is not in this repo** (private business conversation).
- Transcripts are normalized from YouTube captions; expect minor errors.
- 7 hashtag Shorts are missing from the corpus (unrecovered).
- Related concept work had title-template defects under correction (unverified figures in some draft titles) — treat any numbers in derivative materials as unverified until confirmed by Kush.

## Current state (as of September 24, 2026)

- 10 launch ideas drafted under the "hotels as vehicle" framing; the strategy artifact holds the concepts, reference thumbnails, and audio briefings.
- Open: final verification pass on the strategy artifact (navigation, audio players, title corrections).
