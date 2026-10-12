# Diamond Inventory & Pricing: Analytics Report

A business-style analytics report on the Diamonds dataset (53,790 cleaned records), written for merchandising and pricing stakeholders.

## Business objective
Understand where inventory value is concentrated, how size and quality grades affect price, and which areas need attention.

## Files
- `Diamonds_Analytics_Report.ipynb`: full analysis with code, charts and findings
- `Diamonds_Analytics_Report.docx`: report with executive summary, insights and recommendations

## Key findings
- Stones up to 0.5 ct are 35% of units but 7.5% of value; stones above 1 ct are 32.5% of units but 69% of value.
- I1 and SI2 stones are 18% of units but 23% of value, at the lowest price per carat.
- In 1 to 1.5 ct stones, IF earns about 3.5x the price per carat of I1; Ideal earns about 44% more than Fair.
- Price per carat jumps about 25% at the 1.0 carat mark.

## Recommendations
Price by size band first, reduce exposure to large low-clarity stones, review slow small-stone holdings, use the 1.0 ct threshold in merchandising, and add sales and margin data for the next stage.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook, Power BI

## How to run
`pip install pandas numpy matplotlib seaborn jupyter`, then open the notebook. It loads the data from a public URL.
