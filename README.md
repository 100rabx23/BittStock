# 📈 Stock Trend and Price Prediction Application  

![Logo](./assets/logo.gif)  

**An interactive Python-based application for analyzing stock trends, calculating metrics, and predicting future prices.**  

---

## 🚀 Features  
- **Data Upload**: Easily upload your stock data in CSV format.  
- **Trend Detection**: Identify bullish, bearish, or neutral trends using moving averages.  
- **Stock Metrics**: Calculate key financial metrics:
  - Average Daily Return  
  - Volatility  
  - Sharpe Ratio  
  - Total Returns  
- **Price Prediction**: Predict future stock prices for the next 30 days using Linear Regression.  
- **Interactive Graphs**: Visualize stock trends, moving averages, and predictions using Plotly.  
- **Report Generation**: Create detailed PDF reports summarizing stock performance and trends.  
- **User-Friendly Interface**: A Tkinter-based GUI for easy interaction.  

---

## 🛠️ Technologies Used  

- **Programming Language**: Python  
- **Libraries**:  
  - Data Processing: `pandas`, `numpy`  
  - Machine Learning: `sklearn`  
  - Visualization: `plotly`, `matplotlib`  
  - PDF Generation: `reportlab`  
  - GUI: `tkinter`  

---

## 📂 Project Structure  

```plaintext
StockTrendPrediction/  
├── assets/                  # Folder for images, logos, and GIFs  
│   └── logo.gif             # Logo GIF  
├── data/                    # Folder for sample or uploaded datasets  
├── reports/                 # Folder for generated PDF reports  
├── src/                     # Source code  
│   ├── main.py              # Main application file  
│   ├── utils.py             # Helper functions for data processing  
│   ├── model.py             # Machine learning model implementation  
├── README.md                # Project documentation  
├── requirements.txt         # Python dependencies  
