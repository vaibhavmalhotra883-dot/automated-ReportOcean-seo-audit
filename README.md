# Automated Japanese SEO Title Tag Audit & CTR Pipeline (Python + Google Sheets + Looker Studio)

An automated SEO workflow built to extract, audit, and prioritize **Page Title Tags** at scale for international (Japanese) SERPs.

## 🚀 Project Overview
Page titles are one of the highest-leverage on-page SEO factors for Organic Click-Through Rate (CTR). In Japanese SERPs, full-width characters take up roughly twice the pixel width of English characters, causing standard titles to truncate early.

This project automates the title tag auditing process for **Report Ocean Co.jp** across 100+ URLs, turning raw title lengths into prioritized CTR optimization tasks.

### Key Features
* **Automated Title Extraction (Python):** Crawls target URLs and extracts `<title>` tags cleanly using Google Colab.
* **Japanese SERP Length Validation (Google Sheets):** Uses custom spreadsheet formulas to evaluate character counts against Japanese SERP display limits (flagging titles `< 15` chars as weak intent and `> 32` chars as truncation risks).
* **CTR Impact & Priority Scoring:** Automatically maps title length errors to business impact (*Low CTR Impact*, *Missed Search Intent*) and assigns priority tiers (`P2 - Optimize Soon` vs. `P3 - Optimal Growth`).
* **Interactive Dashboard (Looker Studio):** Visualizes title health distribution and optimization priorities for quick stakeholder review.

## 🛠️ Tech Stack
* **Python** (Google Colab) – Automated URL crawling & `<title>` extraction
* **Google Sheets** – Dynamic length validation, error flagging & priority scoring
* **Looker Studio** – Executive reporting & visual KPI tracking

## 🔗 Live Project Links
* **Interactive Looker Studio Dashboard:** [View Dashboard](https://datastudio.google.com/reporting/8c3595c8-741b-46ce-8d6f-abb2c25d3573)
* **Google Colab Notebook:** [Run Python Script](https://colab.research.google.com/drive/1uQFhB2n-Q_YPJHvRMwPaVUKkDVPRTD2t?usp=sharing)
* **Live Audit Dataset & Formulas:** [View Google Sheet](https://docs.google.com/spreadsheets/d/15UQyMtmWSjTPuRmH_SNBcQZgJkO1hG-KZQWsDnSnqxU/edit?usp=sharing)
