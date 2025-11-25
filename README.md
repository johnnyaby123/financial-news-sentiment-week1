# Predicting Price Moves with News Sentiment

## Project Overview
This project analyzes the relationship between financial news sentiment and stock price movements.  
The focus is on:

1. **Task 1:** Setting up GitHub repository, Python environment, and project folder structure.
2. **Task 2:** Quantitative analysis of stock data using PyNance and TA-Lib; calculating technical indicators and daily returns.
3. **Task 3:** Placeholder workflow for news sentiment correlation (ready for integration once news data is available).

This challenge demonstrates skills in **Data Engineering, Financial Analytics, and Machine Learning Engineering**.

---

## Folder Structure
├── data/
│ ├── AAPL.csv
│ ├── AMZN.csv
│ ├── GOOG.csv
│ ├── META.csv
│ ├── MSFT.csv
│ ├── NVDA.csv
│ └── task3_workflow_ready.csv
├── notebooks/
│ ├── Task2_Stock_Analysis.ipynb
│ └── Task3_Sentiment_Correlation.ipynb
├── scripts/
│ └── init.py
├── tests/
│ └── init.py
├── .gitignore
├── requirements.txt
└── README.md


---

## How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/johnnyaby123/financial-news-sentiment-week1
cd financial-news-sentiment-week1

2. Set up Python environment and install dependencies:
python -m venv venv
# Windows
source venv/Scripts/activate
# Mac/Linux
source venv/bin/activate
pip install -r requirements.txt

Run the Notebooks:

Task 2: notebooks/Task2_Stock_Analysis.ipynb

Performs technical analysis (MA, RSI, MACD)

Calculates daily stock returns

Creates visualizations for trends and indicators

Task 3: notebooks/Task3_Sentiment_Correlation.ipynb

Workflow for news sentiment correlation

Placeholder for missing news dataset (daily_sentiment column with zeros)

Prepares data for correlation analysis when news dataset is added

Note: Task 3 can be fully executed once the news dataset (financial_news.csv) is available.

Key Insights (Tasks 1 & 2)

Stock data for AAPL, AMZN, GOOG, META, MSFT, NVDA analyzed.

Technical indicators calculated using TA-Lib.

Daily returns computed for each stock.

Task 3 workflow prepared for sentiment correlation, ready for integration with news headlines.

Future Steps (Task 3)

Integrate real news dataset (financial_news.csv).

Compute sentiment scores for headlines (positive, neutral, negative).

Aggregate daily sentiment and correlate with daily stock returns.

Update visualizations and insights accordingly.

Author

Yohannnes Abayneh Lemma / https://github.com/johnnyaby123

10 Academy Week-1 Challenge Submission
