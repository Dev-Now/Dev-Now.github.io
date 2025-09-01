---
layout: post
title: "Announcing Zakaty 1.0.0 – A Windows app for accurate Zakat calculation"
date: 2025-09-01
categories: software zakat
---

![Zakaty Logo](https://raw.githubusercontent.com/Dev-Now/zakaty/v1.0.0/assets/icons/logo.png)

Zakaty 1.0.0 is now released. It's a Windows desktop application (Flutter, x64) that helps you calculate and track your Zakat with confidence, while keeping all your data fully local and private.

<p style="margin:1.2em 0;">
	<a href="https://github.com/Dev-Now/zakaty/releases/download/v1.0.0/zakaty_setup.exe" style="background:#2563eb;color:#fff;text-decoration:none;font-weight:600;padding:12px 22px;border-radius:6px;display:inline-flex;align-items:center;gap:8px;box-shadow:0 2px 4px rgba(0,0,0,.15);">
		⬇️ Download Zakaty 1.0.0 (Windows .exe)
	</a>
</p>

## Why Zakaty?
Keeping yearly Zakat records in scattered spreadsheets is error‑prone. Zakaty gives you a focused interface: multiple calculation sheets, multi‑currency support with automatic conversion, historical tracking, and clear separation between savings and advance Zakat payments.

## Key Features
- Multiple calculation sheets (organize scenarios or family members)
- Multi‑currency savings with automatic conversion on a chosen due date
- Live recalculation (2.5% rate) as you type
- Track historical sheets & revisit past years
- Manage due dates for accurate FX rates
- Advanced Zakat (early / late payments) with include / exclude toggle
- Exploration mode (play safely without saving)
- Fully local storage (no cloud upload)

## Installation (Windows 10+)
1. Download the latest `zakaty_setup.exe` from the release page.
2. Run the installer and follow the wizard.
3. Launch "Zakaty" from Start Menu (or desktop shortcut).

Release: [https://github.com/Dev-Now/zakaty/releases/tag/v1.0.0](https://github.com/Dev-Now/zakaty/releases/tag/v1.0.0)

### Troubleshooting
- If it doesn't start: try Run as Administrator.
- Check antivirus / Windows Defender blocks.
- Ensure system meets: 100MB disk, 4GB RAM, internet for FX rates.

## Quick Start
1. App opens with an "Exploration" sheet—click around freely.
2. Create a real sheet: "Add new calculation sheet".
3. Add savings entries (bank, cash, etc.).
4. (Optional) Add advance Zakat payments—toggle inclusion depending on timing.
5. Read header summary: Total Savings, Calculated Zakat, ToDo (remaining).

## Configuration
A config file is created automatically at first run (see README for details). You can adjust supported currencies or working directory there.

## Zakat Rules (Implemented)
- Rate: 2.5% of eligible savings.
- Assumes Nisab already maintained for the lunar year (no automatic Nisab check).
- User responsible for verifying Nisab threshold and special cases.

> Disclaimer: Always consult a qualified scholar for complex situations (business assets, mixed investments, debts, etc.).

## Privacy & Data
- All financial data stays on your machine.
- Only FX rate lookups call external public APIs.
- No telemetry, no account needed.

## License Summary
Custom Proprietary License (personal use only). No commercial use, modification, or redistribution. © All rights reserved.

Full license: see the repository `LICENSE` file.

## Contribute / Support
- Issues & feedback: open a GitHub Issue.
- Bug report tips: include Windows version, app version, reproduction steps, screenshots.

Repo: [https://github.com/Dev-Now/zakaty](https://github.com/Dev-Now/zakaty)

## Screenshots

Below are a few interface glimpses (v1.0.0):

![Sheet operations buttons](https://raw.githubusercontent.com/Dev-Now/zakaty/master/assets/sheet_ops.png)
<div style="height:8px"></div>

![Sheet header live summary](https://raw.githubusercontent.com/Dev-Now/zakaty/master/assets/sheet_hdr.png)
<div style="height:8px"></div>

---
Enjoy the release. May it help keep your charitable obligations organized and accurate.
