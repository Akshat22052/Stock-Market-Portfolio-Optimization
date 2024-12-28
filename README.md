# Portfolio Optimization Model for Indian Market

### **Introduction**
This project focuses on developing a **Portfolio Optimization Model** for the Indian stock market, combining **Modern Portfolio Theory (MPT)** with **machine learning techniques**. It provides investors with actionable insights to balance risk and return effectively.

---

### **Motivation**
- The Indian financial market offers unique challenges and opportunities.
- Predicting **stock price volatility** over 90 and 180 trading days.
- Facilitating diversification across large-cap, mid-cap, and small-cap stocks in multiple sectors.
- Providing an optimized strategy for managing risks while maximizing returns.

---

### **Data Description**
- **Sectors**: Data from 9 Indian market sectors (IT, Banking, Pharmaceuticals, etc.).
- **Companies**: 10 companies per sector, spanning data from 2000 to 2023.
- **Features**:
  - **Sectoral Closing Prices**: Average daily closing prices of companies in each sector.
  - **Volatility**: Annualized standard deviation of returns for risk assessment.
  - **Other Indicators**: RSI, MACD, Moving Averages, etc.

---

### **Methodology**
1. **Volatility Prediction**:
   - Used **Artificial Neural Networks (ANN)** and **Random Forest (RF)**.
   - Evaluation Metrics:
     - Mean Squared Error (MSE)
     - Mean Absolute Percentage Error (MAPE)
     - Directional Accuracy

2. **Portfolio Optimization**:
   - Applied **Modern Portfolio Theory** using a covariance matrix to allocate investments.
   - Optimization Method: Sequential Least Squares Quadratic Programming (SLSQP).
   - Compared Strategies:
     - Max Return
     - Equal Allocation
     - Optimized Portfolio

---

### **Results**
- **Volatility Prediction**:
  - ANN performed better than RF for sectors like IT and Banking.
- **Portfolio Optimization**:
  - Optimized portfolio: 24% return with reduced risk compared to Equal Allocation (23%) and Max Return (29% with high risk).

---


   
