# 🔍 ODigger

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20OSINT-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-requests-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **ODigger** is a fast username OSINT hunter that searches for a given username across **50+ platforms** (social media, developer sites, gaming, forums, creative communities, and more). It provides live results, batch scanning, and exports to TXT, JSON, and CSV.

**Designed for authorized OSINT research and digital footprint mapping.**

---

## 📌 Overview

ODigger checks hundreds of popular websites for the existence of a username using HTTP status codes and platform-specific "not found" signals. It supports single username hunting, batch scanning from a file, and detailed reporting with category grouping.

It is fast, threaded, and produces clean, actionable reports.

---

## 🖥️ Modules

| # | Module                | Description |
|---|-----------------------|-------------|
| **[1]** | **Username Hunt**     | Single username search with live results |
| **[2]** | **Batch Scan**        | Scan multiple usernames from a text file |
| **[3]** | **Site Browser**      | Browse all 50+ platforms by category |

---

## 📊 Key Features

- **50+ Platforms** — Social, Dev, Gaming, Forums, Creative, and more
- **Smart Detection** — Combines HTTP status codes + platform-specific keywords
- **Threaded Scanning** — Configurable threads for speed
- **Live Progress** — Real-time colored results with status badges
- **Category Grouping** — Results organized by platform type
- **Batch Mode** — Scan hundreds of usernames from a file
- **Export Options** — TXT (human-readable), JSON (structured), CSV (spreadsheet)
- **Clean Terminal UI** — Professional colored output and clear sections

---

## ⚙️ Requirements

- **requests**:
  ```bash
  pip install requests
  chmod +x ODigger
  ./ODigger

  📁 Output

Live Terminal — Real-time colored results with platform and status
Summary Table — Total checked, found, by category
Export Files (in odigger_reports/):
odigger_username_YYYYMMDD_HHMMSS.txt — Human-readable report
odigger_username_YYYYMMDD_HHMMSS.json — Structured data
odigger_username_YYYYMMDD_HHMMSS.csv — Spreadsheet format



📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED OSINT RESEARCH & SECURITY TESTING USE ONLY
