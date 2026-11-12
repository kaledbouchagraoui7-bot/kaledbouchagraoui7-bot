<h2 align="center">Kaled Bouchagraoui — Open-Source Scientific &amp; Data Engineering</h2>

<p align="center">
  <strong>17-year-old high-school student in France building free, open-source Python tools for biomedical literature synthesis, public registry parsing, and reproducible reporting.</strong><br/>
  <a href="https://kaledbouchagraoui7-bot.github.io/computational-biology-portfolio/">Live Zero-Install PRISMA 2020 Web Demo</a> ·
  <a href="https://github.com/kaledbouchagraoui7-bot/computational-biology-portfolio">Flagship Repository</a>
</p>

---

### Flagship Project

| Repository | Focus | Highlights |
|---|---|---|
| **[`computational-biology-portfolio`](https://github.com/kaledbouchagraoui7-bot/computational-biology-portfolio)** | **Biomedical Literature &amp; Biostatistics Automation**<br>NCBI PubMed, Europe PMC, PRISMA 2020, RefSeq, Table 1 | • **Zero-install browser demo:** [PRISMA 2020 Explorer](https://kaledbouchagraoui7-bot.github.io/computational-biology-portfolio/)<br>• **Ground-truth benchmark:** Reproduces published `PMC13739473` PubMed query (`226` vs. `225` reported, `99.56%` match) and cross-database deduplication (`422 -> 251` unique)<br>• **Automates mechanical prep:** PMID/DOI deduplication, exact count conservation, `.ris`/`.bib` export, and baseline Table 1 math (human PICO &amp; bias review required) |

---

### Supporting Open-Source CLI Utilities

| Repository | Plain-English Description |
|---|---|
| **[`pms-clinicaltrials-openfda-monitor`](https://github.com/kaledbouchagraoui7-bot/pms-clinicaltrials-openfda-monitor)** | Python CLI querying public US FDA MAUDE adverse-event counts, recalls, 510(k) clearances, and ClinicalTrials.gov v2 studies into structured Excel/Word tables with monthly Z-score flags for human review (raw counts, not incidence rates). |
| **[`sentinel-compliance-auditor`](https://github.com/kaledbouchagraoui7-bot/sentinel-compliance-auditor)** | Python CLI performing strictly passive external checks of public DNS records (`DMARC`, `SPF` lookup count, `CAA`), TLS metadata, and HTTP security headers into structured reports. |
| **[`medtech-regulatory-compliance-suite`](https://github.com/kaledbouchagraoui7-bot/medtech-regulatory-compliance-suite)** | Unified CLI orchestrator bundling the literature, public-registry, and passive DNS/HTTP scripts into a single command-line package. |

---

### Core Engineering Principles

- **Zero Fabrication &amp; Transparent Boundaries:** Missing DOIs, abstracts, or denominators are never guessed—empty fields are flagged in amber for human verification.
- **100% Free Public APIs (MIT License):** Built strictly on NCBI Entrez, Europe PMC REST, OpenFDA (CC0), ClinicalTrials.gov v2, and public DNS-over-HTTPS—no paid SaaS dependencies.
