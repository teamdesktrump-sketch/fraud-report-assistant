# Fraud Report Assistant

A clone of the FTC's [ReportFraud.ftc.gov](https://reportfraud.ftc.gov/assistant) — a multi-step wizard for reporting fraud, scams, and bad business practices.

## Features
- 6-step wizard: Category → Detail → What Happened → Contact Info → Review → Confirmation
- 10 fraud categories with dynamic sub-categories
- Progress bar, FTC styling (blue #1a4480), USA government banner
- Reports saved to database (`FraudReport` entity)
- Confirmation screen with fake FTC-style report number

## Structure
- `app/index.html` — Full single-file React-less app (vanilla JS + Tailwind CDN)
- `entities/FraudReport.json` — Database entity schema

## Built with
- [Base44](https://base44.com) Superagent
- Vanilla JavaScript, Tailwind CSS
