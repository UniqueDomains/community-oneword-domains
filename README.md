# Available .COMMUNITY One-Word Domains (11,058)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C058%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .community one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,058 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,058 domains · **Median ask:** $19.61 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/community`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/community?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./community.csv">CSV</a> / <a href="./community.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .COMMUNITY search](https://unique.domains/domains/tld/community?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .COMMUNITY search](https://unique.domains/domains/tld/community?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .COMMUNITY one-word domain catalog.

### Files

- `community.csv` — public CSV extract (1,000 rows)
- `community.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/community-oneword-domains/main/community.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| Ryan.community      | available | $58.98    | —             | 60             | 44     | 4      | namecheap         |
| skills.community    | resell    | —         | —             | 58             | 47     | 6      | Sav.com, LLC - 29 |
| farmers.community   | premium   | $46.20    | $46.20        | 54             | 59     | 7      | namecheap         |
| matcha.community    | available | $14.99    | —             | 86             | 39     | 6      | name.com          |
| europe.community    | resell    | —         | —             | 68             | 36     | 6      | Sav.com, LLC      |
| homes.community     | premium   | $123.75   | —             | 86             | 34     | 5      | name.com          |
| payments.community  | available | $14.99    | —             | 58             | 33     | 8      | name.com          |
| chain.community     | resell    | —         | —             | 64             | 34     | 5      | Dynadot Inc       |
| solutions.community | premium   | $123.75   | —             | 56             | 31     | 9      | name.com          |
| SanDiego.community  | available | $14.99    | —             | 74             | 29     | 9      | name.com          |
| slots.community     | resell    | —         | —             | 49             | 31     | 5      | Sav.com, LLC      |
| photos.community    | premium   | $123.75   | —             | 54             | 28     | 6      | name.com          |
| Jim.community       | available | $58.98    | —             | 78             | 28     | 3      | namecheap         |
| gray.community      | resell    | —         | —             | 68             | 30     | 4      | Sav.com, LLC - 38 |
| tips.community      | premium   | $123.75   | —             | 80             | 26     | 4      | name.com          |
| KFC.community       | available | $58.98    | —             | 74             | 27     | 3      | namecheap         |
| demand.community    | resell    | —         | —             | 78             | 21     | 6      | GoDaddy.com, LLC  |
| webs.community      | premium   | $118.80   | $118.80       | 56             | 21     | 4      | namesilo          |
| systems.community   | available | $14.99    | —             | 46             | 27     | 7      | name.com          |
| VHS.community       | premium   | $46.20    | $46.20        | 71             | 20     | 3      | namecheap         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,058 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/community?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/community?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .community domains. The names range from direct dictionary terms such as teeth.community and week.community to more expressive words such as forgive.community and hahaha.community. For founders, the main question is whether the word feels clear, memorable, and credible with the .community ending. For investors, the key issue is whether the entry price leaves room for resale despite a niche extension. With a median ask of 19.61, the pricing is low enough to compare several options, but word quality matters more than price alone in this set.

- All names in this selection use the .community extension
- Median ask is 19.61 across 11,058 listed domains
- Best fits are clear words that pair naturally with .community
- Be cautious with awkward, negative, or overly broad terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .COMMUNITY One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .COMMUNITY page](https://unique.domains/domains/tld/community?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_community_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
