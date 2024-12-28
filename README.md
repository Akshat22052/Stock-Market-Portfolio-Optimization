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

### **Future Enhancements**
- Add advanced machine learning models (e.g., XGBoost).
- Incorporate ensemble methods and hyperparameter tuning.
- Perform backtesting for validation.

---

### **Authors**
- **Akshat Karnwal (2022052)**: Literature review and model building.
- **Keshav Chhabra (2022247)**: Literature review and model building.
- **Ramish Jamal (2022395)**: Model building and evaluation.
- **Mohd Masood (2022299)**: Data preprocessing and model building.

---

### **References**
1. H. Markowitz, “Portfolio Selection,” *The Journal of Finance*, 1952.
2. Y. Huang et al., “Machine Learning for Stock Prediction,” IEEE, 2021.
3. X. Xu et al., “Dynamic Portfolio Optimization Using Deep Reinforcement Learning,” IEEE, 2021.
4. [Additional references from the report]

---

### **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/Akshat22052/Stock-Market-Portfolio-Optimization.git
