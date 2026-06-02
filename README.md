# DecodeLabs-internship---Task-2

Goal: Analyze the cleaned dataset to uncover patterns, trends, and distributions.
What was done:

Computed descriptive statistics (mean, median, min, max, std) across all numerical columns
Identified a right-skewed distribution in TotalPrice — most orders are low-value with a few high-value outliers
Detected a small number of outliers in TotalPrice above $3,300 representing bulk purchases
Flagged a suspicious low-price Phone order at $11.39 — retained but noted
Analyzed order distribution across products — Printers lead but all categories are balanced
Found that Cancelled orders are the most frequent status while Delivered are the least — a potential business concern
Identified Instagram as the top customer acquisition channel
Revealed no consistent sales trend over time, with notable spikes in April 2023 and June 2024
Discovered June as the peak month for order volume, likely driven by summer spending

Visualizations: Histogram, Boxplots, Countplots, Line plot
Tools: Python, pandas, matplotlib, seaborn
