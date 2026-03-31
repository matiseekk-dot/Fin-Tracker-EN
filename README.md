# FinTrack PRO 🇬🇧

A powerful personal finance tracking app. Built with React + Vite.

## Features

- **Dashboard** — financial overview, health score, daily budget, forecasts
- **Transactions** — add, edit, quick templates, multi-currency support
- **Payments** — track bills, subscriptions, loans with monthly checkboxes
- **Goals** — savings goals, category limits, vacation budget module
- **Analytics** — charts, rankings, month comparisons, category trends
- **Accounts** — manage bank and investment accounts

## Installation

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Stack

- React 18
- Vite 5
- Recharts (charts)
- XLSX (export/import)
- Lucide React (icons)
- localStorage (data persistence)

## Data

All data is stored locally in the browser (localStorage).
Export/import available in Settings as .xlsx or JSON file.

## Customization

1. Replace demo transactions in `INITIAL_TRANSACTIONS`
2. Update accounts in `INITIAL_ACCOUNTS`
3. Adjust categories in `BASE_CATEGORIES`
4. Set your billing cycle day in Settings

---
*FinTrack PRO — Your finances, under control*
