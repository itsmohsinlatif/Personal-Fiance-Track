```markdown
# Personal Finance Tracking Program

This is a Python-based Personal Finance Tracking program that allows you to efficiently manage and track your financial transactions. You can add transactions, view them within a specific time range, categorize them as income, expense, or savings, and even visualize your financial status with a line graph. The program saves and manages data using a CSV file for persistence.

## Features

- **Add Transactions**: Record your financial transactions specifying amount, date, and category.
- **View Transactions**: Display transactions within a specific time range.
- **Categorize Transactions**: Categorize transactions as income, expense, or savings.
- **Data Storage**: Persist transactions in a CSV file.
- **Data Visualization**: Plot a line graph showing income, expense, and savings over time.
- **User-friendly Menu**: Operate the program using a simple menu-driven interface.

## Requirements

- Python 3.x
- `pandas`
- `matplotlib`

You can install the required packages using pip:

```bash
pip install pandas matplotlib
```

## Usage

1. **Clone the Repository** (if applicable):
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Run the Program**:
    ```bash
    python finance_tracker.py
    ```

3. **Menu Options**:
    - `1. Add Transaction`: Add a new financial transaction. You will be prompted to enter the amount, date (in `YYYY-MM-DD` format), and category (income/expense/savings).
    - `2. Show Transactions`: Display all transactions within a specified date range.
    - `3. View Balance`: Show current balance categorized as income, expense, and savings.
    - `4. Plot Line Graph`: Visualize your transactions over time with a line graph.
    - `5. Exit`: Exit from the program.

## Example

### Adding a Transaction

![Add Transaction](images/add_transaction.png)

### Viewing Transactions

![Show Transactions](images/show_transactions.png)

### Plotting a Line Graph

![Line Graph](images/line_graph.png)

## CSV Data Format

The transactions are stored in a CSV file named `transactions.csv` with the following columns:

- `Date`: The date of the transaction in `YYYY-MM-DD` format.
- `Category`: The category of the transaction (income/expense/savings).
- `Amount`: The amount of the transaction.

Example:

```csv
date,amount,category,description
01-01-2024,372.9,Income,Salary
02-01-2024,200.58,Expense,Transportation
03-01-2024,150.42,Income,Investment Return
04-01-2024,320.33,Income,Freelance
```

## Directory Structure

```
personal-finance-tracker/
├── main.py
├── data_entry.py
├── finance_data.csv
└── README.md
```

## Contact

For any questions or feedback, please reach out to [itsmohsinlatif@gmail.com].

---

Thank you for using the Personal Finance Tracking Program!
```
