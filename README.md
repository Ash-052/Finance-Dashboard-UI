# Finance-Dashboard-UI

A simple responsive finance dashboard built with React and Vite.

## Features

- Summary cards for balance, income, and expenses
- Time-based balance trend visualization
- Category-based spending breakdown
- Transaction list with search, filter, and sort
- Role toggle for `Viewer` and `Admin`
- Admin can add new transactions
- Insights section with spending highlights
- Local storage persistence for role, theme, and transactions
- Dark mode theme toggle
- Mock API data loading from static JSON
- Export filtered transaction data as CSV or JSON
- Advanced filtering with category, date range, and grouping

## Getting started

1. Install dependencies

```bash
npm install
```

2. Run the app

```bash
npm run dev
```

3. Open the local URL shown in the terminal

## Notes

- The app uses mock data and simulates role-based UI behavior on the frontend.
- The `Admin` role enables transaction creation and edit buttons.
- The dashboard handles empty lists and filter states gracefully.
