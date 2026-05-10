## Financial News Sentiment Analysis & Stock Price Correlation
### 📌 Project Overview
This project is part of my Data Analyst role at Nova Financial Solutions. The goal is to analyze a large corpus of financial news data to discover correlations between news sentiment and stock market movements. This work assists the investment team in making data-driven decisions based on market narratives.

### 🛠️ Tech Stack
Language: Python 3.12

Environment: GitHub Actions (CI/CD)

Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn, TA-Lib

Version Control: Git/GitHub using Task-based branching.

### 📂 Project Structure
Plaintext
├── .github/workflows/   # CI/CD pipeline (YAML)
├── data/                # Raw and Processed data
├── notebooks/           # Jupyter Notebooks (Task 1: EDA)
├── src/                 # Source code for data processing
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation
### 🚀 Task 1: Exploratory Data Analysis (EDA)
In this initial phase, I analyzed the FNSPID (Financial News Sentiment and Stock Price Index Dataset). Key findings include:

Headline Lengths: Most headlines are concise (40-80 characters).

Publication Trends: Identified major spikes in news volume correlating with market events.

Publisher Analysis: Cleaned and analyzed the top 10 publishers contributing to the dataset.

Topic Modeling: Used keyword extraction to identify themes like "Price Targets," "Earnings," and "FDA Approvals."

### 📈 Task 2: Technical Indicators
(Work in Progress)

Implementation of Simple Moving Averages (SMA).

Calculation of RSI (Relative Strength Index) to measure price momentum.

Correlation analysis between sentiment scores and stock returns.

⚙️ Setup Instructions
Clone the repository:

``` bash
git clone <https://github.com/hk12214/news-sentiment-analysis.git>
```
Create and activate a virtual environment:

``` bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
Install dependencies:

``` bash
pip install -r requirements.txt
```