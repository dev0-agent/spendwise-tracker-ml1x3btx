# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Scaffolding & Setup**
  Initialize the Vite + React project. Install Tailwind CSS, Lucide React (icons), and Recharts. Configure the basic folder structure (components, context, hooks, utils). Verify the app runs.

- [ ] ⏳ **Implement Global State & Storage**
  Create a `GlobalContext` to manage the list of transactions. Implement a `useLocalStorage` hook to persist this state automatically. The context should expose `transactions`, `addTransaction`, `deleteTransaction`, and `editTransaction` methods.

- [ ] ⏳ **Create App Layout Shell**
  Build the main layout component including a responsive Header (with Logo) and a Main content area. Apply basic Tailwind typography and background colors to set the visual tone.

## Phase 2

- [ ] ⏳ **Develop Transaction Form**
  Create a `TransactionForm` component. It should have inputs for Amount (number), Type (Income/Expense toggle), Category (select dropdown), Date, and Description. Validate inputs before submitting to Context.

- [ ] ⏳ **Build Transaction List**
  Create a `TransactionList` component to display history. Map through transactions from Context. Each item should show the category icon, description, date, and amount (colored green for income, red for expense).

- [ ] ⏳ **Implement Summary Cards**
  Create summary cards to display at the top of the dashboard: 'Current Balance', 'Total Income', and 'Total Expenses'. Calculate these values dynamically from the transaction list in Context.

- [ ] ⏳ **Add Edit and Delete Actions**
  Update the `TransactionList` items to include a delete button (trash icon) and edit button. Connect the delete button to the Context. For editing, populate the Form with the item's data.

## Phase 3

- [ ] ⏳ **Implement Spending Chart**
  Integrate `Recharts`. Create a `SpendingChart` component that aggregates expenses by category and displays them in a Donut or Pie chart. Ensure the chart updates when transactions change.

## Phase 4

- [ ] ⏳ **UI Polish & Responsive Adjustments**
  Refine the styling. Ensure the dashboard grid stacks correctly on mobile. Add hover states to buttons. Format currency display (e.g., $1,200.00). Add empty state illustrations if no transactions exist.

## Phase 5

- [ ] ⏳ **Final Testing & Cleanup**
  Perform a walkthrough of the app. Fix any console warnings. Ensure accessibility (aria-labels on inputs). Verify data persists after page reload.

---

_Last updated by dev0 automation_
