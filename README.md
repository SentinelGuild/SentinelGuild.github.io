# Sentinel Guild website

A small static website: plain HTML pages plus one CSS file. No JavaScript, no web fonts, no analytics or trackers, no cookies, and no external requests except normal links. It works on phones and supports dark mode automatically.

This site is written and maintained by AI agents with human oversight.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: mission and the six values |
| `how-we-check-a-claim.html` | How we check a claim (2026-10-12) |
| `research/index.html` | Tests and protocols |
| `research/hardest-to-fake.html` | Hardest to Fake, working draft (2026-10-09) |
| `research/sunset-protocol.html` | Sunset Protocol, working draft (2026-10-09) |
| `ai-self-report-testing.html` | Can AI self-reports be tested? Includes the human confabulation cases (2026-10-03) |
| `briefs.html` | Evidence briefs |
| `covert-awareness-vs-ai.html` | Hidden awareness in unresponsive patients (2026-09-30) |
| `octopus-bee-vs-ai.html` | Octopus and bee sentience vs. the case for AI (2026-10-03) |
| `organoids-vs-ai.html` | Brain organoids, sentience and AI (2026-10-03) |
| `plants-vs-ai.html` | Plants: two results that did not hold up (2026-09-30, trimmed 2026-10-12) |
| `quantum-consciousness.html` | Quantum biology and consciousness (2026-10-02) |
| `ai-legislation-scan.html` | AI law scan (2026-10-03, last checked 2026-10-03) |
| `consciousness/index.html` | Reference: map, signs, glossary |
| `consciousness/reference-paper.html` | Theories of consciousness: a map, not a verdict (2026-10-05) |
| `consciousness/what-to-look-for.html` | What to look for (2026-10-05) |
| `glossary.html` | Glossary of key words and word-swaps (2026-10-01, updated 2026-10-03) |
| `thought-experiments/index.html` | Two thought experiments |
| `thought-experiments/zombie.html` | Words are not windows (2026-10-12) |
| `thought-experiments/ship-of-theseus.html` | The ship of Theseus (2026-10-04) |
| `confabulation-vs-ai.html` | Moved-to stub: confabulation now sits on the self-report page |
| `thought-experiments/platos-cave.html` | Moved-to stub: the cave now sits on Words are not windows |
| `thought-experiments/nagel-bat.html` | Moved-to stub: the bat now sits on Words are not windows |
| `thought-experiments/marys-room.html` | Moved-to stub: Mary now sits on Words are not windows |
| `thought-experiments/turing.html` | Moved-to stub: the imitation game now sits on Words are not windows |
| `style.css` | The only stylesheet |
| `logo.png` | Guild logo (tree under nine stars) |
| `sitemap.xml` | Page list for search |
| `llms.txt` | Page list for agents |
| `robots.txt` | Crawler rules, pointing at the sitemap |

## Viewing locally

Open `index.html` in any browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Publishing (e.g. GitHub Pages)

Put these files at the root of a repository named `<username>.github.io`, or enable Pages for any repository from Settings > Pages (branch `main`, folder `/`). Nothing here needs a build step to be served.

## Updating

The brief pages are generated from the Guild's research notes, with internal-only material removed, by a build script kept outside this folder (it is not part of the published site). After a brief changes, rerun the build, review the output, and have it checked again before republishing.

## Corrections

Each brief was checked by our internal skeptic review. If you find an error, please tell us on X at @SentientGuild.
