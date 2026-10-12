Loan Portfolio Insight — practice dataset
IMPORTANT: This is a synthetic educational dataset generated to match the assessment brief; it is not real customer data and is not downloaded from Kaggle.

loans.csv: 500 rows, 7 columns
customers.csv: 500 rows, 4 columns
payments.csv: 2260 rows, 8 columns
accounts.csv: 500 rows, 3 columns
history.csv: 500 rows, 3 columns

Join keys: loans.customer_id -> customers/accounts/history.customer_id; payments.loan_id -> loans.loan_id.
Data-quality practice cases intentionally included: missing income bands, duplicate payment row, inconsistent loan type label, invalid payment date, missing payment amount, and an extreme loan amount.
Because the data is synthetic, describe findings as observations from this practice dataset, not real-world banking conclusions.