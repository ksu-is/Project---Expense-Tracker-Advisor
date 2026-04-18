# Project---Expense-Tracker-Advisor
# This is my project which tracks your expenses and suggests changes that you should make in order to hit your financial goals.
# What the project does: It operates a Python-based pipeline to ingest pre-categorized CSV data, aggregate it into specific silos (Rent, Food, Utilities, Discretionary), and evaluate the results against the 50/30/20 rule.
# Why the project is useful: It eliminates "financial fog" by providing an objective, emotion-free audit of spending habits and triggering logic alerts when discretionary spending exceeds established benchmarks.
# How to get started: Ensure your Python environment is established, format your transaction data into the required "pre-categorized" schema, and execute the ingestion script.

Phase 1
[ ] Install Python & Dependencies: Establish your environment and install the pandas library, which is the standard for high-performance data manipulation.
[ ] Define CSV Schema: Create a "pre-categorized" CSV template with strict headers (e.g., Date, Description, Category, Amount) to ensure the ingestion engine avoids misidentification errors.
[ ] Create Sample Dataset: Populate the CSV with test data reflecting an internship-level budget to verify the summation logic.

Phase 2
[ ] Build Ingestion Script: Write the Python code to load the structured CSV file using pandas.read_csv().
[ ] Develop Summation Algorithm: Use the .groupby('Category') and .sum() functions to aggregate total spending into the required silos: Rent, Food, Utilities, and Discretionary.
[ ] Validate Totals: Implement a check to ensure the sum of the silos matches the total expenditure of the raw dataset.

Phase 3
[ ] Code the 50/30/20 Heuristic: Define variables for the total expenditure and calculate the percentage ratio for each silo.
[ ] Implement Logic Alerts: Program a conditional statement that triggers a "Logic Alert" if the Discretionary ratio exceeds the 30% threshold.
[ ] Calculate Deficit: Write the logic to determine the exact dollar amount by which the user exceeded the 30% benchmark.

Phase 4
[ ] Generate Objective Report: Script a clean output that displays the user's actual spending versus the 50/30/20 benchmarks.
[ ] Automate Strategic Recommendations: Create a function that prints a direct recommendation for reduction based on the calculated overage.
[ ] Final Execution Audit: Run the full pipeline to ensure the program removes "emotional friction" by providing hard mathematical reality.
