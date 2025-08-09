# Trader Sentiment Analysis

This project explores how Bitcoin market sentiment (Fear vs. Greed) influences trader performance using real-world trading data and the Bitcoin Fear/Greed Index.

## Objective

- Analyze the relationship between market sentiment and trader outcomes.
- Uncover actionable patterns to help improve trading strategies in the Web3/crypto space.

## Datasets

- **Bitcoin Market Sentiment (Fear/Greed Index):**
  - Columns: Date, Classification (Fear/Greed)
- **Trader Data (from Hyperliquid):**
  - Columns: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.

## Methodology

1. **Data Cleaning:** Prepare and merge both datasets by date.
2. **Exploratory Analysis:** Visualize sentiment trends and trader performance metrics.
3. **Statistical Analysis:** Test for differences in trader outcomes during Fear vs Greed periods; assess correlations.
4. **Insights & Recommendations:** Summarize findings and suggest actionable strategies.

## Repository Structure

project-root/
├── data/
├── notebooks/
├── src/
├── outputs/
├── README.md
├── requirements.txt
├── .gitignore


## How to Reproduce

1. Clone the repository.
2. Download datasets from provided links (see `/data/README.md` for instructions).
3. Run the Jupyter Notebook in `/notebooks` for analysis.

## Results

Final insights and recommendations will be summarized in the notebook and an output report.

---

## Author

- Gopal Deswal
- Contact: gopudeswal1234@gmail.com
