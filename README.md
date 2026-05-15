# Available .LIVING One-Word Domains (12,612)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C612%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .living one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,612 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,612 domains · **Median ask:** $110.37 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-15  
**Canonical page:** `https://unique.domains/domains/tld/living`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/living?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./living.csv">CSV</a> / <a href="./living.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LIVING search](https://unique.domains/domains/tld/living?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LIVING search](https://unique.domains/domains/tld/living?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LIVING one-word domain catalog.

### Files

- `living.csv` — public CSV extract (1,000 rows)
- `living.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/living-oneword-domains/main/living.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| Ryan.living          | available | $48.98    | —             | 60             | 44     | 4      | namecheap       |
| brain.living         | resell    | —         | —             | 72             | 48     | 5      | Spaceship, Inc. |
| RedSox.living        | premium   | $490      | $700          | 72             | 60     | 7      | namecheap       |
| neuroscience.living  | available | $39.99    | —             | 80             | 37     | 12     | name.com        |
| happier.living       | resell    | —         | —             | 62             | 16     | 7      | Porkbun LLC     |
| regions.living       | premium   | $490      | $700          | 64             | 59     | 7      | namecheap       |
| stories.living       | available | $39.99    | —             | 58             | 36     | 7      | name.com        |
| indoor.living        | resell    | —         | —             | 72             | 15     | 6      | Dynadot, LLC    |
| keepthechange.living | premium   | $490      | $700          | 46             | 59     | 15     | namecheap       |
| Keith.living         | available | $48.98    | —             | 66             | 25     | 5      | namecheap       |
| agents.living        | premium   | $980      | $1,400        | 56             | 50     | 6      | namecheap       |
| schools.living       | available | $39.99    | —             | 72             | 24     | 7      | name.com        |
| coins.living         | premium   | $98       | $140          | 56             | 41     | 5      | namecheap       |
| gamers.living        | available | $5.49     | $39.99        | 62             | 24     | 6      | namesilo        |
| Tools.living         | premium   | $490      | $700          | 56             | 40     | 5      | namecheap       |
| superhero.living     | available | $39.99    | —             | 84             | 23     | 9      | name.com        |
| lets.living          | premium   | $245      | $350          | 77             | 39     | 4      | namecheap       |
| holidays.living      | available | $5.49     | $39.99        | 78             | 23     | 8      | namesilo        |
| justin.living        | premium   | $490      | $700          | 58             | 38     | 7      | namecheap       |
| motorsport.living    | available | $39.99    | —             | 74             | 23     | 10     | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,612 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/living?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/living?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .living domains. The set spans plain dictionary words, abstract terms, and more distinctive choices such as learn.living, average.living, dracula.living, and statement.living. For founders, the best options are usually the words that are easy to say, easy to remember, and naturally aligned with home, wellness, lifestyle, design, or modern residential themes. For buyers comparing value, the median ask of 110.37 sets a useful baseline for this extension. When comparing these domains, weigh semantic fit, tone, and renewal logic carefully, because a strong keyword in a niche TLD can be clear and brandable, but only when the word-extension pairing feels natural.

- Prefer words that read naturally with .living
- Use 110.37 as the median ask reference point
- Check trademark exposure on distinctive terms
- Favor clear, memorable dictionary words

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .LIVING One-Word Domains*. Version 2026-05-15. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIVING page](https://unique.domains/domains/tld/living?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_living_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
