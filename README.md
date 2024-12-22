# 📈 BittStock  [Stock Trend and Future Prediction Application] 
<center>

![Logo](./BittStock/assets/logoam.gif)  
</center>
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
BittStock/  
├── assets/                    
│   └── logo.gif             
├── reports/                   
├── src/                       
│   ├── main.py                           
├── README.md                # Project documentation  
├── requirements.txt         # Python dependencies  

## 🔧 Installation

### Prerequisites
- Python 3.8 or higher

### Ensure you have the required libraries installed:
```bash
pip install -r requirements.txt

## Running the Application
Clone the repository:

'''bash
git clone https://github.com/your-username/StockTrendPrediction.git
Navigate to the project directory:

'''bash
cd StockTrendPrediction
Run the application:

'''bash
python src/main.py
