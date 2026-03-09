Stock Volatility Analysis 📊

This project analyzes the realized volatility of Apple Inc. (AAPL) stock prices using historical data from Yahoo Finance. 
It calculates daily logarithmic returns, computes monthly realized volatility, and visualizes the relationship between
price movements and volatility levels.

<img width="86" height="20" alt="image" src="https://github.com/user-attachments/assets/1c6aa145-8aca-4825-8c69-2d02a743c6b1" />
<img width="82" height="20" alt="image" src="https://github.com/user-attachments/assets/36e44449-4dde-4165-b93a-23f6dff466fe" />
<img width="116" height="20" alt="image" src="https://github.com/user-attachments/assets/28c96369-f770-49cf-9424-1cdcd9d1ee1b" />

🚀 Features
- Download historical stock data using yfinance
- Calculate daily logarithmic returns
- Compute monthly realized volatility and annualize it
- Visualize returns and volatility using matplotlib
- Save data and plots for documentation

📁 Project Structure
stock_volatility_analysis/
├── chapter.ipynb          # Jupyter Notebook with full analysis
├── README.md              # This file
├── requirements.txt       # Required Python packages
└── week1/
    └── ch1_im6.png        # Generated visualization of returns and volatility

🛠️ Installation
1. Clone the repository:
git clone https://github.com/liang-hao-h/stock_volatility_analysis.git
cd stock_volatility_analysis

2. Install dependencies:
pip install -r requirements.txt

📝 Usage
1. Open the Jupyter Notebook:
jupyter notebook chapter.ipynb

2. Run all cells sequentially to:
  - Download AAPL data (2010-2020)
  - Calculate log returns
  - Compute and visualize volatility
  - Save the plot to week1/ch1_im6.png

<img width="436" height="441" alt="image" src="https://github.com/user-attachments/assets/ca46c865-ea59-4e76-a9df-4653a70aef2d" />


📈 Results
The analysis produces a dual plot:
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/a6c85027-bc5f-4f62-b0fd-04320689b522" />
