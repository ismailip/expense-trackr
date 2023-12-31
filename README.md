# Expense Tracker React App

This is a simple expense tracking React app that allows users to add, view, and filter expenses. Users can input details such as the expense title, amount, and date. The app provides a visual representation of expenses using a chart, and users can filter expenses by year.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ismailip/expense-trackr.git
   ```

2. Navigate to the project directory:

   ```bash
   cd expense-tracker-react-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Run the app:

   ```bash
   npm start
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. **Add Expense:**
   - Click the "Add New Expense" button to add a new expense.
   - Fill in the details such as title, amount, and date in the form.

2. **Filter Expenses:**
   - Use the filter dropdown to select the desired year.
   - The app will display expenses for the selected year.

3. **View Expenses:**
   - The app displays a list of expenses and a chart representing the total expenses for each month.

4. **Chart:**
   - The chart provides a visual representation of monthly expenses.

## Components

### 1. App.js

The main component that manages the state of expenses and handles the addition of new expenses.

### 2. NewExpense.js

Responsible for rendering the form to add a new expense and managing the editing state.

### 3. ExpenseForm.js

A form component for entering expense details. Handles user input and submission.

### 4. Expense.js

The main expense component that displays the filter, chart, and list of expenses.

### 5. ExpensesFilter.js

A dropdown component for filtering expenses by year.

### 6. ExpensesChart.js

Generates a chart based on the total expenses for each month.

### 7. Chart.js

A reusable chart component for displaying data points.

### 8. ChartBar.js

A bar within the chart representing a specific data point.

### 9. ExpensesList.js

Displays a list of expenses or a fallback message if no expenses are available.

### 10. ExpenseItem.js

Represents an individual expense item within the list.

### 11. ExpenseDate.js

Displays the date of an expense in a visually appealing format.

## Contributing

If you'd like to contribute to the project, please follow the standard GitHub fork and pull request workflow.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
