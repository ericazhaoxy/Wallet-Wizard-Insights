# Competitive Analysis — Wallet Wizard Insights

## Purpose

I reviewed common patterns across personal finance apps to decide what to build next and how to differentiate Wallet Wizard Insights.

## What users actually need (beyond logging)

As life gets busier (graduation, moves, travel, more credit cards/subscriptions), the hard part isn’t only recording expenses — it’s:

- seeing **cash flow trends** quickly,
- staying within **budget**,
- catching **recurring charges** that silently accumulate,
- and knowing **what to change** next.

## Market patterns (high-level)

### Pattern A: Expense tracking + cash flow clarity (Simplifi-like)

Strengths:

- Clean overview of spending and cash flow
- Trend-based insights (weekly/monthly)

Common gaps:

- Insights can feel passive (informational, not actionable)
- Recurring charges may not stand out as a primary driver of overspending

### Pattern D: Subscription / recurring charge focus (Rocket Money-like)

Strengths:

- Strong recurring detection and subscription visibility
- Clear “how much you can save” framing

Common gaps:

- Subscription insights are often separated from budgets and cash-flow views
- Users still need a single dashboard to connect “recurring costs” with “budget vs actual”

## Positioning

**Wallet Wizard Insights** combines:

- **cash flow clarity** (trends + budget vs actual + category breakdown),
  with
- **recurring charge detection** (subscriptions surfaced as a first-class insight),
  in one explainable dashboard designed to be useful within seconds.

## MVP scope (buildable + portfolio-friendly)

1. Expense CRUD with categories
2. Budget vs Actual by category
3. Monthly cash-flow trend (income vs expense)
4. Recurring detection (merchant + cadence + amount similarity)
5. Subscription list + next charge estimate + “cancel impact” what-if

## Success criteria (simple validation)

A user can answer within 30 seconds:

- Did I overspend this month?
- Which categories drove it?
- What recurring charges am I paying monthly?
- What’s the easiest cut to improve next month’s cash flow?
