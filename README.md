# Personal Finance Tracker

A simple Python-based Personal Finance Tracker that allows you to manage your daily income and expenses. It uses a CSV file for data storage, and provides features to view transactions within a specific date range, calculate net savings, and plot income vs. expenses over time.

## Features
- **Add Transactions**: Easily record your income and expenses with date, category, amount, and description.
- **View Transactions**: Filter transactions by a date range to see a summary of your finances (Total Income, Total Expense, Net Savings).
- **Visualize Data**: Automatically generate a line plot comparing your income and expenses over the specified period using `matplotlib`.

## Requirements
- Python 3.x
- `pandas`
- `matplotlib`

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/AmmarAhmed-dot/Personal-Finance-Tracker.git
   cd Personal-Finance-Tracker
   ```

2. (Optional but recommended) Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run

Run the main script to start the application:
```bash
python main.py
```

Follow the on-screen prompts to navigate the application.

## Note on Data Privacy
By default, the `.gitignore` file is configured to ignore `finance_data.csv` and any other `.csv` files. This ensures your personal finance data is not accidentally uploaded to your GitHub repository.
