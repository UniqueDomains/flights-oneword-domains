# Available .FLIGHTS One-Word Domains (12,605)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C605%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .flights one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,605 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,605 domains · **Median ask:** $65.95 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/flights`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/flights?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./flights.csv">CSV</a> / <a href="./flights.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .FLIGHTS search](https://unique.domains/domains/tld/flights?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .FLIGHTS search](https://unique.domains/domains/tld/flights?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .FLIGHTS one-word domain catalog.

### Files

- `flights.csv`, public CSV extract (1,000 rows)
- `flights.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/flights-oneword-domains/main/flights.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| cod.flights       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo                   |
| united.flights    | resell    | —         | —             | high           | medium | 6      | NameCheap, Inc.            |
| all.flights       | premium   | $500      | $500          | high           | medium | 3      | name.com                   |
| dig.flights       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo                   |
| firsttime.flights | resell    | —         | —             | high           | low    | 10     | Squarespace Domains II LLC |
| bar.flights       | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                   |
| due.flights       | available | $59.99    | —             | high           | low    | 3      | name.com                   |
| job.flights       | premium   | $123.75   | —             | high           | low    | 3      | name.com                   |
| end.flights       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo                   |
| law.flights       | premium   | $128.70   | $128.70       | high           | medium | 3      | namecheap                  |
| kit.flights       | available | $58.99    | $58.99        | medium         | low    | 3      | namesilo                   |
| low.flights       | premium   | $123.75   | $123.75       | high           | low    | 3      | name.com                   |
| lan.flights       | available | $58.99    | $58.99        | medium         | low    | 3      | namesilo                   |
| ten.flights       | premium   | $123.75   | $123.75       | high           | low    | 3      | name.com                   |
| max.flights       | available | $58.99    | $58.99        | high           | medium | 3      | namesilo                   |
| try.flights       | premium   | $242      | $242          | high           | low    | 3      | namesilo                   |
| NYT.flights       | available | $58.99    | $58.99        | high           | low    | 3      | namesilo                   |
| cali.flights      | premium   | $118.80   | $118.80       | high           | low    | 4      | namesilo                   |
| pig.flights       | available | $59.99    | —             | high           | low    | 3      | name.com                   |
| game.flights      | premium   | $250      | $250          | high           | medium | 4      | name.com                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,605 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/flights?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/flights?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=related_pricing)

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

The .flights domain extension is built for travel, aviation, and journey-focused brands, making it a natural fit for airlines, travel agencies, booking platforms, and route-based services. This selection spans domains from short, everyday words to descriptive travel phrases, with a median asking price of about $66. Because pricing varies widely across .flights domains, comparing asking price against brandability and clarity is essential before choosing one for a new venture or portfolio.

- 12,605 one-word .flights domains tracked in this selection
- Median asking price near $66 across the set
- Travel- and journey-themed names fit airlines, agencies, and booking brands
- Updated daily to reflect current availability and pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FLIGHTS One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FLIGHTS page](https://unique.domains/domains/tld/flights?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
