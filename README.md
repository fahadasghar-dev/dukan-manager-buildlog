
<p align="center">
  <img src="https://img.shields.io/badge/Oracle-APEX-F80000?style=flat&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/PL%2FSQL-Oracle-F80000?style=flat&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/Cloud-hosted-C74634?style=flat&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/WhatsApp-Cloud%20API-25D366?style=flat&logo=whatsapp&logoColor=white">
  <img src="https://img.shields.io/badge/AI-Claude-D97757?style=flat&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/Tests-Playwright-2EAD33?style=flat&logo=playwright&logoColor=white">
  <img src="https://img.shields.io/badge/Status-in%20real%20use-0A3E30?style=flat">
</p>

# Dukan Manager

A shop and **installment (qist)** app for small shops in Pakistan that sell TVs, fridges, ACs, phones and bikes on installments.
It replaces the paper register: sales, installment plans, payments, recovery, cash drawer (galla), stock, suppliers and reports, in one phone-first app with light and dark mode.

**Try the demo:** [kafacloud.com/demo](https://kafacloud.com/demo) &nbsp;·&nbsp; user `demo` · password `demo1234`


## What it does

- **Sales:** cash, credit (udhaar) and installment in one screen; advance, 3–24 month plans, markup per tenure, guarantors, CNIC photos
- **Installments:** due today and late lists, take payment in two methods, receipts, reminders, recovery visits with GPS proof
- **WhatsApp:** automatic receipts and reminders through the WhatsApp Cloud API; customer payment screenshots read by AI and sent to the owner as a phone alert
- **AI assistant:** answers the owner's questions from live shop data, read-only, in English or Roman Urdu
- **Shop:** stock and purchases, suppliers, expenses, cash drawer with day close, roles and permissions, multi-shop (tenant) setup
- **Reports:** sales, collection, profit, late customers, stock worth

## How it is built

- **Oracle APEX** (native components) on **Oracle Database**, business rules in **PL/SQL**; every shop sees only its own data
- **Playwright** end-to-end tests for every page, role and money flow, on phone and laptop, light and dark
- Designed and built end to end: business rules, PL/SQL packages, APEX screens, server setup and testing.

## About this repository

The source code is private. This repository is a public **build log**: every product change is one commit here, with its real date and time (client names hidden), and it updates automatically.
See the [commit history](../../commits/main) or [BUILD_LOG.md](BUILD_LOG.md).

---

**Fahad Asghar** · Senior Oracle APEX Developer · Karachi
[LinkedIn](https://www.linkedin.com/in/fahad-asghar25) · [kafacloud.com](https://kafacloud.com) · kafacloud.info@gmail.com
