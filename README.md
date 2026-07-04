![Expense Overview](screenshots/expense_overview.png)
![Spending Patterns](screenshots/spending_patterns.png)

# 💰 Personal Financial Health Dashboard

A personal finance dashboard that automatically tracks expenses, investments, and monthly budget — built with Google Forms, Google Sheets, and Power BI. Expenses are logged from a phone in seconds, stored automatically in Google Sheets, and visualised in Power BI with a single Refresh click.

## 📊 What's in the report

The dashboard has two pages:

### 1. Expense Overview

KPI cards for Total Money Spent and Total Invested (investments tracked separately, never mixed with spending). Bar chart: Total Spending by Category showing where money goes each month. Line chart: Monthly Spending Trend across March–July 2026. Clustered bar chart: Budget vs Actual per category, showing overspending at a glance. Donut chart: Payment Method Breakdown (UPI, Credit Card, Net Banking, Cash). Month Year slicer to filter all visuals to any specific month — synced across both pages.

### 2. Spending Patterns

Bar chart: Total Spending by Day of Week, revealing which days of the week spending peaks. Donut chart: Weekday vs Weekend split, showing what percentage of spending happens on work days vs rest days. Line chart: Daily Spending Trend across the full date range, where each spike represents a large one-day expense (typically monthly Rent).

## 🧠 Skills demonstrated

Building a live data pipeline using Google Forms → Google Sheets → Power BI Web connector. Writing DAX measures: Total Spending (expenses only, using CALCULATE to exclude investments) and Budget Target. Data modelling with three related tables: Expenses, Budget, and a custom DateTable. Date intelligence using a DAX-built DateTable with helper columns for Month Year, Day of Week, Day Type, and sort keys to ensure correct calendar ordering. Bidirectional cross-filtering between Budget and Expenses tables for accurate per-category comparisons. Synced slicers across multiple report pages.

## 🛠️ Tools & Data

**Tools:** Power BI Desktop, Google Sheets, Google Forms, iPhone Shortcuts

**Data:** Personal expense data logged daily via Google Form, covering from march 2026, updating daily. Budget targets set manually per category in a separate Budget tab.

**Categories tracked:** Rent · Grocery · Travel · Utilities · Eating Out · Shopping · EMI · Investments · Miscellaneous
