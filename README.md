# Financial News Sentiment and Stock Price Analysis

## 📌 Project Overview
This project explores the relationship between financial news headlines and stock market movements for five major tech companies: **AAPL, AMZN, GOOG, META, and NVDA**. 

The goal was to determine if the "sentiment" (mood) of the news acts as a leading indicator for stock returns using Natural Language Processing (NLP) and Quantitative Analysis.

## 🛠️ Tech Stack
*   **Language:** Python 3.x
*   **Data Analysis:** Pandas, NumPy
*   **NLP:** NLTK (VADER Sentiment Analysis)
*   **Technical Analysis:** TA-Lib (SMA, RSI)
*   **Visualization:** Matplotlib, Seaborn

## 🚀 Tasks Completed

### Task 1: Sentiment Analysis
*   Cleaned and preprocessed a large dataset of financial news headlines.
*   Applied **VADER Sentiment Analysis** to assign a "Compound Score" (ranging from -1 to 1) to each headline.
*   Identified news publication trends and sentiment spikes over time.

### Task 2: Quantitative Analysis (Technical Indicators)
*   Calculated daily stock returns for the selected tickers.
*   Implemented technical indicators using **TA-Lib**:
    *   **SMA (20-Day):** To identify price trends.
    *   **RSI (Relative Strength Index):** To identify overbought or oversold conditions.
    *   **Rolling Volatility:** To measure market risk.
*   Generated a **Correlation Heatmap** to see how tech stocks move in relation to one another.

### Task 3: Sentiment & Price Correlation
*   Aligned news dates with stock market trading days.
*   Aggregated daily sentiment scores per stock.
*   Calculated the **Pearson Correlation Coefficient** between news sentiment and daily price returns.
*   Visualized findings with a regression scatter plot.

## 📊 Key Visualizations
1.  **Stock Technical Analysis:** Combined plot of closing prices and RSI indicators.
2.  **Return Correlation Matrix:** Heatmap showing how closely these tech giants are linked.
3.  **Sentiment vs. Returns:** Scatter plot showing the mathematical link between news mood and market direction.
## 📂 Project Structure
```text
news-sentiment-analysis/
├── data/                  
├── notebooks/       
├── src/                
├── requirements.txt    
└── README.md