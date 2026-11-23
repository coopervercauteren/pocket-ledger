# Pocket Ledger

A personal income statement in a single web page. Track income and expenses, see them grouped by category, and get a projection of how much you'll save (or lose) by the end of the month.

## Features

- **Month-end projection**: net savings or loss you're on track for, plus your projected savings rate
- **Income statement**: income and expenses by category, with actual, projected and % of income
- **Charts**: running net through the month and spending by category
- **Auto-categorization**: categories are suggested from the description (e.g. "Trader Joe's" → Groceries)
- **Repeating items**: mark rent, paychecks or subscriptions as monthly and they're projected into future months
- **Bank CSV import** and **CSV export**

## How the projection works

Repeating items from earlier months that haven't been logged yet this month are added on their usual day. Everyday spending is projected at your daily pace so far, blended with your average daily pace from the previous three months. One-off income isn't projected.

## Your data

Everything is stored in your browser's local storage. Nothing is sent to a server. Clearing site data, or opening the page in another browser or device, starts a fresh ledger, so export a CSV now and then as a backup.

The page opens with example transactions. Press **Clear examples** to remove them.

## Running it

It's one static file, `index.html`. Open it in a browser, or host it with GitHub Pages.
