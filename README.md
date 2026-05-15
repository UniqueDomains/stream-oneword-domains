# Available .STREAM One-Word Domains (12,228)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C228%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .stream one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,228 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,228 domains · **Median ask:** $279.97 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
**Canonical page:** `https://unique.domains/domains/tld/stream`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/stream?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./stream.csv">CSV</a> / <a href="./stream.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .STREAM search](https://unique.domains/domains/tld/stream?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .STREAM search](https://unique.domains/domains/tld/stream?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .STREAM one-word domain catalog.

### Files

- `stream.csv` — public CSV extract (1,000 rows)
- `stream.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/stream-oneword-domains/main/stream.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| boats.stream       | available | $9.98     | —             | 52             | 24     | 5      | namecheap       |
| apartments.stream  | resell    | —         | —             | 60             | 21     | 10     | Dynadot Inc     |
| travelers.stream   | premium   | $437.50   | —             | 58             | 61     | 9      | name.com        |
| CapeCod.stream     | available | $9.98     | —             | 78             | 22     | 8      | namecheap       |
| ships.stream       | resell    | —         | —             | 54             | 15     | 5      | Key-Systems LLC |
| cars.stream        | premium   | $12,500   | —             | 66             | 47     | 4      | name.com        |
| flights.stream     | available | $5.25     | $6.25         | 61             | 22     | 7      | namesilo        |
| jobs.stream        | premium   | $1,250    | —             | 79             | 42     | 4      | name.com        |
| results.stream     | available | $9.98     | —             | 59             | 22     | 7      | namecheap       |
| Tools.stream       | premium   | $490      | $70           | 56             | 40     | 5      | namecheap       |
| wheels.stream      | available | $9.98     | —             | 76             | 20     | 6      | namecheap       |
| events.stream      | premium   | $6,250    | —             | 68             | 37     | 6      | name.com        |
| communities.stream | available | $9.98     | —             | 68             | 19     | 11     | namecheap       |
| etc.stream         | premium   | $625      | —             | 58             | 34     | 3      | name.com        |
| pestcontrol.stream | available | $9.98     | —             | 74             | 18     | 12     | namecheap       |
| inspiration.stream | premium   | $437.50   | —             | 88             | 30     | 11     | name.com        |
| houses.stream      | available | $9.98     | —             | 66             | 18     | 6      | namecheap       |
| rewards.stream     | premium   | $3,125    | —             | 62             | 30     | 7      | name.com        |
| whitewater.stream  | available | $9.98     | —             | 82             | 17     | 11     | namecheap       |
| popup.stream       | premium   | $437.50   | —             | 84             | 29     | 6      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,228 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/stream?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/stream?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely made up of one-word .stream domains. The extension gives every name a clear streaming, broadcast, live, or media-adjacent angle, so the best fits are words that still read cleanly with .stream attached. Examples like pink.stream, electric.stream, create.stream, raise.stream, and overtime.stream show the range: descriptive, energetic, and highly brandable terms. When comparing these domains, focus on whether the word becomes more memorable with .stream, whether the meaning is broad enough for a company or project to grow into, and whether the asking price is justified by clarity, commercial use, and renewal tolerance.

- All names in this selection use the .stream TLD
- Median ask is about $280 across 12,226 domains
- Best picks read naturally with “.stream” attached
- Check trademark overlap before treating a word as ownable

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .STREAM One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .STREAM page](https://unique.domains/domains/tld/stream?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
