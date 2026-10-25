# 🦉 ODigger

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.0-cyan?style=flat-square"/>
</p>

> **ODigger** — Username OSINT Hunter

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ODigger performs username OSINT across a large set of platforms to help authorised investigators map online presence. It supports single and batch usernames, optional variation generation, category filters, and multiple export formats. Offline and proxy options support constrained or privacy-sensitive assessments.

---

## ✨ Features

- Username hunting across 100+ platforms with category filters
- Batch scans from a username list file
- Optional common variation generation for a seed username
- Configurable threads, timeouts, and HTTP/SOCKS proxy support
- Export to TXT/JSON/CSV/HTML (or all) with quiet/JSON modes
- Offline mode for sandboxed or air-gapped review workflows

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ODigger -u alice
./ODigger -b usernames.txt -t 20 --export json -o reports/
./ODigger -u alice --variations -c social --offline
./ODigger --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
