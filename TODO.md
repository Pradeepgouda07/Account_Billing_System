# TODO: Allow Users to View Their Own Reports

## Tasks

- [x] Remove admin role requirement from reports route in `backend/server.js`
- [x] Implement `getMonthlyReport` function in `backend/routes/reports.js` to fetch and aggregate user-specific data (totalInvoices, totalPayments, totalExpenses, netIncome) filtered by userId and month/year

## Followup Steps

- [ ] Test the changes by running the backend server and verifying that authenticated users can access their own reports via the frontend
- [ ] Ensure report data is correctly filtered and aggregated for the specified month and year
