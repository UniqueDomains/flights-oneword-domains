# Available .FLIGHTS One-Word Domains (12,604)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C604%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .flights one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,604 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,604 domains · **Median ask:** $65.43 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
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

- `flights.csv` — public CSV extract (1,000 rows)
- `flights.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/flights-oneword-domains/main/flights.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar      |
| -------------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------- |
| Ryan.flights               | available | $75.98    | —             | 60             | 44     | 4      | namecheap      |
| holidays.flights           | resell    | —         | —             | 78             | 23     | 8      | Name.com, Inc. |
| Tools.flights              | premium   | $280      | $280          | 56             | 40     | 5      | namecheap      |
| shortcuts.flights          | available | $59.99    | —             | 48             | 41     | 10     | name.com       |
| toys.flights               | premium   | $118.80   | $118.80       | 60             | 24     | 4      | namesilo       |
| whynot.flights             | available | $59.99    | —             | 74             | 39     | 7      | name.com       |
| vacations.flights          | premium   | $500      | —             | 56             | 19     | 9      | name.com       |
| spectra.flights            | available | $59.99    | —             | 62             | 34     | 7      | name.com       |
| executives.flights         | premium   | $118.80   | $118.80       | 64             | 12     | 10     | namesilo       |
| etc.flights                | available | $59.99    | —             | 58             | 34     | 3      | name.com       |
| LongBeach.flights          | premium   | $138.60   | $138.60       | 62             | 11     | 10     | namecheap      |
| Cats.flights               | available | $75.98    | —             | 59             | 33     | 4      | namecheap      |
| DistrictofColumbia.flights | premium   | $138.60   | $138.60       | 52             | 4      | 20     | namecheap      |
| teams.flights              | available | $59.99    | —             | 62             | 32     | 5      | name.com       |
| William.flights            | available | $75.98    | —             | 74             | 31     | 7      | namecheap      |
| letsgo.flights             | available | $59.99    | —             | 57             | 31     | 7      | name.com       |
| slots.flights              | available | $58.99    | $58.99        | 49             | 31     | 5      | namesilo       |
| dogs.flights               | available | $59.99    | —             | 76             | 28     | 4      | name.com       |
| gems.flights               | available | $58.99    | $58.99        | 70             | 28     | 4      | namesilo       |
| forms.flights              | available | $59.99    | —             | 54             | 28     | 5      | name.com       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,604 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/flights?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/flights?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .flights domains. That makes the comparison straightforward: the extension is consistent, so most of the difference in quality comes from the word itself, the asking price, and any obvious legal or renewal risk. Some names are direct and travel-relevant, while others are abstract or unusually broad, such as alight.flights, problem.flights, or arithmetic.flights. For founders, the strongest options are usually memorable words that fit aviation or booking without confusion. For investors, the better candidates are names where the ask leaves room for resale and the keyword has plausible commercial use within travel.

- All results use the .flights extension
- Median ask across this set is 65.43
- Travel-fit words usually beat broad or awkward terms
- Avoid names with clear trademark exposure

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .FLIGHTS One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .FLIGHTS page](https://unique.domains/domains/tld/flights?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_flights_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
