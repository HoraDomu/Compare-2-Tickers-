📈 Stock Comparison Graph

A Python tool for fetching and visualizing stock closing prices. Compare two stocks’ year-to-date performance with a clean, interactive graph. Ideal for quick analysis or portfolio tracking.

💡 Features

Fetch year-to-date stock data from Yahoo Finance using yfinance.

Compare two stocks side by side on a single graph.

Beautiful matplotlib visualization with custom colors and labels.

Simple command-line interface—just enter tickers and view results instantly.


🛠 Installation

Clone this repository:

git clone <repository_url>
cd <repository_folder>


Install dependencies:

pip install yfinance matplotlib pandas numpy scipy scikit-learn

🚀 Usage

Run the script:

python main.py


Enter the stock tickers when prompted:

Please Enter First Stock Ticker: AAPL
Please Enter Second Stock Ticker: MSFT


View the resulting graph comparing closing prices.

🔮 Future Improvements

Add regression analysis to quantify trends.

Allow interactive date ranges for comparisons.

Enable multiple stock plotting.

Export graphs as images or PDFs for reporting.

📦 Dependencies

yfinance
: Stock data fetching.

matplotlib
: Plotting and visualization.

pandas
: Data manipulation.

numpy
: Numerical operations.

scipy
: Scientific computing.

scikit-learn
: Linear regression and evaluation (future expansion).
