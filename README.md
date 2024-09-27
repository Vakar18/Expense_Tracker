# Expense Tracker App

This is a **Personal Expense Tracker** web application that allows users to track their daily expenses, visualize spending patterns, and manage their wallet balance. The application features expense and income management, data visualization using bar charts and pie charts, and a responsive user interface.

## Features

- **Add Income and Expenses**: Add, edit, and delete expenses, as well as track income to maintain your wallet balance.
- **Expense Categories**: Expenses are categorized into `Food`, `Entertainment`, `Travel`, `Shopping`, `Grocery`, and `Others` for easy tracking.
- **Data Visualization**: View your expenses via:
  - Bar chart (Top expenses by category).
  - Pie chart (Expense distribution).
- **Responsive Design**: The app works across devices and adjusts for screen sizes.
- **Local Storage**: User data (wallet balance, expenses) is persisted in the browser's local storage.
- **Pagination**: Recent transactions are paginated for better viewing.
- **Modal-based Editing**: Edit or update transactions via pop-up modals.

## Tech Stack

- **Frontend**: React.js
- **Charts and Graphs**: Recharts.js
- **Icons**: React Icons
- **Styling**: CSS
- **LocalStorage**: Persisting data locally

## Components Overview

1. **Dashboard**: The main entry point displaying wallet balance, expenses, and data visualizations.
   - Displays charts and lists the top recent transactions.
   
2. **WalletExpensesComponent**: Manages income and expenses with modals for adding new income or expenses.
   - Shows wallet balance and total expenses.
   - Handles data updates and syncing with local storage.

3. **ExpensesTable**: Displays the list of recent transactions with pagination.
   - Allows users to edit or delete expenses.

4. **LineBarChart**: Displays a bar chart of expenses by category.

5. **RoundChart**: Displays a pie chart representing expense distribution across different categories.

## Installation and Setup

To run this project locally, follow these steps:

### Prerequisites

- **Node.js** (v12+)
- **npm** or **yarn**

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/expense-tracker-app.git
   cd expense-tracker-app
   
2. **Install dependencies:**

   ```bash
   npm install

3. **Run the application**

   ```bash
   npm start

This will start the development server. Open your browser and navigate to http://localhost:3000 to view the application.

## Usage

- **Adding Income:** Click the + Add Income button, enter the income amount, and submit to update your wallet balance.
- **Adding Expenses:** Click the + Add Expense button, fill in the details (title, amount, category, date), and submit. The expense will be deducted from your wallet balance.
- **Edit/Delete Expenses:** Use the Edit (pencil icon) or Delete (trash icon) buttons in the recent transactions list to modify or remove expenses.
- **View Charts:** The app displays a bar chart for top expenses and a pie chart for expense distribution.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
