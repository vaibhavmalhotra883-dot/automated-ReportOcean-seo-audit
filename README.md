# Automated International SEO Audit & Reporting Pipeline (Python + Google Sheets + Looker Studio)

An end-to-end technical SEO automation workflow designed to crawl, audit, prioritize, and visualize international (Japanese) SERP metadata at scale.

## 🚀 Project Overview
Manual SEO audits do not scale for large content repositories. This project automates the extraction and evaluation of page titles for **Report Ocean Co.jp**, translating raw technical errors into business impact metrics and executive-ready dashboards.

### Key Features
* **Automated Extraction (Python):** Crawls target URLs and extracts page titles and metadata using Google Colab.
* **Localized SERP Validation (Google Sheets):** Audits Japanese character lengths against strict SERP pixel/character limits (flagging titles `< 15` or `> 32` full-width characters to prevent truncation).
* **Business Impact & Priority Scoring:** Automatically maps technical errors to business outcomes (e.g., *Low CTR Impact*, *Missed Search Intent*) and assigns triage tiers (`P1` to `P3`).
* **Executive Visualization (Looker Studio):** Connects the live audit dataset to an interactive Looker Studio dashboard for stakeholder reporting.

## 🛠️ Tech Stack
* **Python** (Google Colab) – Web scraping & data processing
* **Google Sheets** – Automated formula logic, conditional auditing, and priority scoring
* **Looker Studio** – Interactive data visualization & KPI tracking

## 🔗 Live Project Links
* **Interactive Looker Studio Dashboard:** [View Dashboard](https://datastudio.google.com/reporting/8c3595c8-741b-46ce-8d6f-abb2c25d3573)
* **Google Colab Notebook:** [Run Python Script](https://colab.research.google.com/drive/1uQFhB2n-Q_YPJHvRMwPaVUKkDVPRTD2t?usp=sharing)
* **Live Audit Dataset & Formulas:** [View Google Sheet](https://docs.google.com/spreadsheets/d/15UQyMtmWSjTPuRmH_SNBcQZgJkO1hG-KZQWsDnSnqxU/edit?usp=sharing)

## 📊 Key Findings (Sample Audit of 100+ URLs)
* Identified **[X]%** of audited Japanese pages suffering from SERP title truncation (`>32` characters), risking lower organic CTR.
* Automated triage into **P2 (Optimize Soon)** vs. **P3 (Optimal Growth)** to focus engineering and content resources on high-impact pages first.

## ⚙️ How to Run
1. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1uQFhB2n-Q_YPJHvRMwPaVUKkDVPRTD2t?usp=sharing).
2. Input your target sitemap or URL list.
3. Run all cells to export metadata directly into the structured audit schema.
