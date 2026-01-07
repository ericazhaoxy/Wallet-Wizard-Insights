# Wallet Wizard Insights

A personal finance web app for expense tracking and cash-flow clarity — with recurring charge detection (subscriptions).

## Motivation

As my life got busier (travel, moves, more credit cards and subscriptions), it became harder to stay on top of spending. I’d occasionally log expenses, but still miss recurring charges, forget what was “fixed” each month, or realize too late that I overspent.

Wallet Wizard Insights is my attempt to solve that with a simple loop:
**track expenses → compare against budgets → surface cash-flow insights → highlight recurring charges**.

## What it does

### Expense Tracking (Core)

- Add / edit / delete expenses
- Category-based organization
- Weekly / monthly summaries

### Cash-Flow Insights (Dashboard)

- Monthly cash-flow trend (income vs expense)
- Budget vs Actual by category
- Spending breakdown with drill-down into transactions

### Recurring Charges (Subscriptions)

- Detect recurring transactions (merchant + cadence + amount similarity)
- Subscription list (monthly cost, next charge date)
- “Cancel impact” what-if analysis (estimate monthly savings)

## Demo

- Live demo: (coming soon)
- Screenshots: (coming soon)

## Tech Stack

- Frontend: React, Next.js
- Backend: Node.js (Next.js API routes)
- Database: PostgreSQL
- Version control: Git/GitHub

## Architecture (High level)

Client (Next.js) → API (Next.js routes) → PostgreSQL

## Local Setup (WIP)

> I’m currently polishing documentation and aligning local/dev environments.  
> A fully reproducible setup guide will be added here (env vars, DB schema, seed, and start scripts).

## Docs

- Competitive analysis: [`docs/competitive-analysis.md`](docs/competitive-analysis.md)

## Roadmap

- v1.1: Dashboard charts + filters (date range, category)
- v1.2: Recurring detection with confidence score + reminders
- v1.3: Basic cash-flow forecasting (rolling average)
- v2: Multi-user support + export (CSV)

## Notes

This project is being iterated in a “product-style” workflow: incremental changes, clear commits, and continuous improvements to UX and insights.
