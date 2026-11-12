<div align="center">
  <img src="assets/sentinel_logo_full.png" alt="Sentinel — MedTech, Privacy & Regulatory Compliance Suite" width="780" />
</div>

<h2 align="center">Sentinel Regulatory &amp; Technical Operations</h2>

<p align="center">
  <strong>Automated EU MDR / Swiss nFADP Digital Compliance Auditing, OpenFDA Post-Market Surveillance (PSUR), PRISMA 2020 Clinical Literature Synthesis, and RA Submission Gatekeeping.</strong><br/>
  <a href="https://kaledbouchagraoui7-bot.github.io/medtech-regulatory-compliance-suite/">Executive Storefront &amp; Sample Dossiers (EN / FR)</a> ·
  <a href="https://kaledbouchagraoui7-bot.github.io/medtech-regulatory-compliance-suite/terms.html">Terms (EN)</a> ·
  <a href="https://kaledbouchagraoui7-bot.github.io/medtech-regulatory-compliance-suite/cgv.html">CGV (FR)</a>
</p>

---

### Turnkey Regulatory &amp; Compliance Deliverables

| Engine &amp; Repository | Target Audience &amp; Standards | Client-Ready Deliverables |
|---|---|---|
| **[`medtech-regulatory-compliance-suite`](https://github.com/kaledbouchagraoui7-bot/medtech-regulatory-compliance-suite)** | **MedTech OEMs, SaMD, CROs &amp; RA Leadership**<br>EU MDR 2017/745, Swiss nFADP, GSPR 17.2, eCTD M1–M5 | • Unified Executive Dossier &amp; Upstream SLA Attribution Brief (`.docx`)<br>• 4- &amp; 6-Sheet Filterable Compliance &amp; eCTD Workbooks (`.xlsx`)<br>• Swiss-Editorial 300-DPI Briefings (`.png` &amp; `.pdf`)<br>• ALCOA+ SHA-256 Provenance &amp; Signed QA Checklist |
| **[`sentinel-compliance-auditor`](https://github.com/kaledbouchagraoui7-bot/sentinel-compliance-auditor)** | **Life Sciences, Digital Health, Law/IP &amp; Fiduciary**<br>Swiss nFADP / LPD, EU GDPR Art. 13/44, RFC 7489, EAA / WCAG 2.1 AA | • 25-Control Passive External Posture Scorecard (`.png` / `.pdf`)<br>• Landscape Executive Audit &amp; Risk Matrix (`.docx` &amp; `.xlsx`)<br>• Copy-Paste DMARC/SPF/CAA &amp; Nginx/Cloudflare `_headers` |
| **[`pms-clinicaltrials-openfda-monitor`](https://github.com/kaledbouchagraoui7-bot/pms-clinicaltrials-openfda-monitor)** | **QA/RA Directors, PRRCs &amp; Pharmacovigilance**<br>EU MDR Art. 83–86, MDCG 2022-21 PSUR, FDA 21 CFR Part 803 | • Automated OpenFDA MAUDE, Recalls &amp; 510(k) Digest (`.docx`)<br>• 4-Sheet Workbook with Clickable ClinicalTrials.gov NCT Links (`.xlsx`)<br>• 300-DPI Safety &amp; Trial Landscape Dashboard (`.png` &amp; `.pdf`) |
| **[`computational-biology-portfolio`](https://github.com/kaledbouchagraoui7-bot/computational-biology-portfolio)** | **Medical Writers, Biostatisticians &amp; Biotech R&amp;D**<br>EU MDR Annex XIV, MEDDEV 2.7/1 Rev 4, ICH E6(R2)/E9, ALCOA+ | • PRISMA 2020 Flow Diagram &amp; Vancouver Word Table (`.docx`)<br>• 4-Sheet Screening Matrix with soft amber QA verification flags (`.xlsx`)<br>• Reproducible Baseline Table 1 &amp; NCBI RefSeq QC Logs |

---

### Public Dataset Research &amp; Benchmark Studies

- **[OpenFDA MAUDE Z-Score Triage (`n = 2,056,124` Insulin Pump MDRs)](https://github.com/kaledbouchagraoui7-bot/pms-clinicaltrials-openfda-monitor/blob/main/case_studies/01_insulin_pump_maude_zscore_study.md)** — Quantifies trailing-baseline window sensitivity (`12m` vs. `35m`) and notes July reporting spikes (`Z = +5.11` / `+2.10`) **flagged for review** (raw counts, not incidence rates).
- **[GLP-1 Cardiorenal PRISMA 2020 Precision Audit (`135 -> 25` studies)](https://github.com/kaledbouchagraoui7-bot/computational-biology-portfolio/blob/main/computational-biology-portfolio/case_studies/01_glp1_prisma2020_reproducibility_study.md)** — **Automates the mechanical prep** (dual-database PubMed + Europe PMC deduplication and PRISMA count accounting) while documenting clinical false-positive boundaries for human screening.
- **[Passive External Hygiene Failure Modes (`RFC 7208`, `DMARC`, `nFADP`)](https://github.com/kaledbouchagraoui7-bot/sentinel-compliance-auditor/blob/main/case_studies/01_external_hygiene_failure_modes_study.md)** — Anonymized technical analysis of SPF recursion limits and pre-consent tracker leaks.

---

### Core Operating Guarantees

- **100% Passive External Observation (`StGB Art. 143bis`):** Domain and privacy checks evaluate strictly public DNS records (`TXT`, `MX`, `CAA`), TLS certificates, and a single standard HTTPS response — identical to an ordinary web browser visit, with zero intrusive probing.
- **Strict ALCOA+ &amp; Zero-Fabrication Integrity:** Clinical literature, safety counts, and trial statuses originate directly from NCBI PubMed, Europe PMC, OpenFDA (CC0), and ClinicalTrials.gov REST API v2. Missing fields are highlighted in soft amber for human verification rather than guessed.
- **Qualified QA / PRRC Sign-Off Workflow:** Deliverables accelerate technical &amp; regulatory preparation and require final qualified internal RA/PRRC/DPO sign-off before regulatory filing or production DNS deployment.
