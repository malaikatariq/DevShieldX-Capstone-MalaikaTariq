# Comprehensive Cyber Reconnaissance and Threat Intelligence Audit on Mozilla Corporation

## 📌 Project Overview
This repository contains the complete portfolio and technical artifacts for the Capstone Project completed during the Open Source Intelligence (OSINT) Internship Program at **DevShieldX**. The objective of this project was to perform a non-destructive, passive, and defensive security audit on **Mozilla Corporation (mozilla.org)** to map out its global infrastructure, technical assets, and potential external exposure.

* **Submitted By:** Malaika Tariq
* **Intern ID:** DSX-CYB-67
* **Organization:** DevShieldX
* **Submission Date:** 17-07-2026

---

## 📂 Repository Layout & Structure

* 📄 **README.md** - Main documentation dashboard (This file).
* 📄 **Report.pdf** - Full compiled professional PDF report.
* 📂 **[Evidence/](https://github.com/malaikatariq/DevShieldX-Capstone-MalaikaTariq/tree/main/Evidence)** - Extracted structural lists, subdomains, and harvested data logs.
* 📂 **[Screenshots/](https://github.com/malaikatariq/DevShieldX-Capstone-MalaikaTariq/tree/main/Screenshots)** - Visual proof of tool dashboards, Shodan lookups, and Google Dorks.
* 📂 **[Tools/](https://github.com/malaikatariq/DevShieldX-Capstone-MalaikaTariq/tree/main/Tools)** - Complete reference index of OSINT utilities utilized during audit.
* 📂 **[Scripts/](https://github.com/malaikatariq/DevShieldX-Capstone-MalaikaTariq/tree/main/Scripts0)** - Practical query command strings and search logic frameworks.
* 📂 **[Resources/](https://github.com/malaikatariq/DevShieldX-Capstone-MalaikaTariq/tree/main/Resources)** - Standard knowledge references, internet routing archives, and data registries.

---

## 🔍 Executive Intelligence Summary

* **Infrastructure Footprint:** Mozilla operates **848 distinct assets** directly exposed to the web, heavily backed by Fastly's redundant Content Delivery Network (CDN) layers and Amazon cloud node blocks to absorb volumetric DDoS traffic.
* **Network Exposures:** Active evaluation identified **733 secure nodes (Port 443)**, alongside **45 secondary administrative/testing endpoints (Port 8443)** which form part of the target's outer attack surface.
* **Social Engineering / Recon Vector:** Employee email naming conventions are highly predictable (`First@mozilla.org` handles 51% of corporate addresses), and valid personal endpoints were systematically confirmed using defensive validation engines.

---

## 🛡️ Top Recommended Remediations
1. **Enforce Global Anti-Indexing:** Use explicit `robots.txt` directives and the `X-Robots-Tag: noindex` response header to mask old technical document paths and development threads.
2. **Obfuscate Corporate Communication Paths:** Hide plain-text corporate addresses behind web contact forms secured by advanced automated CAPTCHA services.
3. **Gateway Protection on Port 8443:** Restrict all alternative port administrative portals behind an enterprise Zero Trust Network Access (ZTNA) or enterprise VPN tunnel integrated with multi-factor authentication (MFA).

---
*Note: This security investigation was conducted entirely using passive data correlation and completely safe reconnaissance guidelines. No active exploitation or aggressive scans were executed against Mozilla Corporation assets.*
