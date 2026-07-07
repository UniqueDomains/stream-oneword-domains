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

**Public extract:** 1,000 rows · **Live catalog:** 12,228 domains · **Median ask:** $408.41 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
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

- `stream.csv`, public CSV extract (1,000 rows)
- `stream.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/stream-oneword-domains/main/stream.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| yes.stream       | premium   | $625      | —             | high           | medium | 3      | name.com        |
| clean.stream     | premium   | $1,107    | $116          | high           | low    | 5      | namesilo        |
| door.stream      | available | $9.98     | —             | high           | low    | 4      | namecheap       |
| axis.stream      | resell    | —         | —             | medium         | medium | 4      | NameSilo, LLC   |
| ADS.stream       | premium   | $625      | —             | high           | medium | 3      | name.com        |
| evil.stream      | available | $5.25     | $6.25         | high           | low    | 4      | namesilo        |
| sign.stream      | resell    | —         | —             | high           | low    | 4      | Dynadot Inc     |
| ane.stream       | premium   | $625      | $81.25        | low            | low    | 3      | name.com        |
| Jody.stream      | available | $9.98     | —             | high           | low    | 4      | namecheap       |
| design.stream    | resell    | —         | —             | high           | medium | 6      | Dynadot Inc     |
| atp.stream       | premium   | $625      | —             | medium         | low    | 3      | name.com        |
| pail.stream      | available | $5.25     | $6.25         | high           | low    | 4      | namesilo        |
| mantra.stream    | resell    | —         | —             | high           | low    | 6      | NameSilo, LLC   |
| awe.stream       | premium   | $625      | —             | high           | low    | 3      | name.com        |
| poor.stream      | available | $5.25     | $6.25         | medium         | low    | 4      | namesilo        |
| wallet.stream    | resell    | —         | —             | high           | medium | 6      | NameSilo, LLC   |
| bce.stream       | premium   | $625      | —             | medium         | low    | 3      | name.com        |
| suit.stream      | available | $5.25     | $6.25         | high           | low    | 4      | namesilo        |
| investing.stream | resell    | —         | —             | high           | low    | 9      | Key-Systems LLC |
| bud.stream       | premium   | $625      | —             | high           | low    | 3      | name.com        |

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

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list gathers one-word .stream domain names drawn from a pool of 12,228 listings, with a median asking price around $408. Names such as out.stream, half.stream, and christmas.stream show the pattern: short, everyday words paired with the streaming-focused .stream extension. When comparing these domains, weigh the asking price against renewal cost, check for existing trademarks, and favor names that are easy to spell and pronounce. Updated daily.

- Median ask near $408 across this .stream set
- One-word, brandable names ready to compare
- Renewal cost matters as much as sticker price
- 12,228 .stream domains, updated daily

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .STREAM One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .STREAM page](https://unique.domains/domains/tld/stream?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_stream_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
