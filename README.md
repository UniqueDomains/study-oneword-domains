# Available .STUDY One-Word Domains (12,607)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C607%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .study one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,607 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,607 domains · **Median ask:** $97.46 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/study`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/study?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./study.csv">CSV</a> / <a href="./study.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .STUDY search](https://unique.domains/domains/tld/study?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .STUDY search](https://unique.domains/domains/tld/study?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .STUDY one-word domain catalog.

### Files

- `study.csv` — public CSV extract (1,000 rows)
- `study.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/study-oneword-domains/main/study.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| geton.study         | available | $50.98    | —             | 82             | 10     | 6      | namecheap |
| dogsit.study        | available | $50.98    | —             | 96             | 2      | 6      | namecheap |
| playin.study        | available | $50.98    | —             | 80             | 10     | 7      | namecheap |
| pierogi.study       | available | $50.98    | —             | 82             | 7      | 7      | namecheap |
| stirup.study        | available | $50.98    | —             | 82             | 3      | 7      | namecheap |
| dogsick.study       | available | $50.98    | —             | 90             | 1      | 7      | namecheap |
| rumcake.study       | available | $50.98    | —             | 81             | 3      | 8      | namecheap |
| FabFour.study       | available | $2.19     | $38.99        | 82             | 3      | 8      | namesilo  |
| surebet.study       | available | $50.98    | —             | 82             | 8      | 8      | namecheap |
| keepthechange.study | available | $50.98    | —             | 46             | 59     | 15     | namecheap |
| insight.study       | premium   | $62.50    | —             | 76             | 69     | 8      | name.com  |
| whynot.study        | available | $50.98    | —             | 74             | 39     | 7      | namecheap |
| makers.study        | premium   | $53.92    | $53.92        | 62             | 67     | 6      | namesilo  |
| commonground.study  | available | $50.98    | —             | 74             | 28     | 13     | namecheap |
| cars.study          | premium   | $625      | —             | 66             | 47     | 4      | name.com  |
| webshop.study       | available | $50.98    | —             | 76             | 22     | 8      | namecheap |
| robots.study        | premium   | $53.92    | $53.92        | 62             | 47     | 6      | namesilo  |
| Tshirts.study       | available | $50.98    | —             | 70             | 20     | 8      | namecheap |
| stories.study       | premium   | $62.50    | —             | 58             | 36     | 7      | name.com  |
| ebooks.study        | available | $50.98    | —             | 62             | 19     | 6      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,607 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/study?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/study?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=related_pricing)

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

These domains are one-word names on the .study extension. The set spans dictionary-style words, action words, and short brandable terms such as Acup.study, Matcha.study, Popup.study, and Useit.study. With a median ask of 97.46, many names may look inexpensive upfront, so the better comparison is whether the word is easy to remember, clearly relevant to learning or research, and unlikely to create trademark friction. Names like Chanel.study or Trex.study deserve extra caution for rights risk. When choosing among these domains, weigh price against clarity, resale flexibility, and whether the term still makes sense on a .study ending.

- One-word .study domains with broad naming styles
- Median ask across this selection is 97.46
- Best picks fit education, learning, or research use
- Check trademark risk on branded terms before buying

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .STUDY One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .STUDY page](https://unique.domains/domains/tld/study?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_study_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
