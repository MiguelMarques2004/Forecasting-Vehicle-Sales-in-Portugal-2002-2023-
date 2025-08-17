# Forecasting Vehicle Sales in Portugal (2002–2023)

This project applies **time series analysis** methods to forecast new vehicle sales in Portugal from **2002 to 2023**.

---

## Main Steps

### 1. Data Preparation
- Transformation of the original dataset (**Year + Month → Date**)  
- Creation of a `tsibble` object

### 2. Exploratory Analysis
- Identification of **trend**, **seasonality**, and **variance**

### 3. Statistical Transformations
- Application of **square root transformation**  
- **Box-Cox Transformation**  
- Seasonal and first-order differencing to achieve **stationarity**

### 4. Modeling
- Comparison of different **ARIMA/SARIMA** models  
- Selection based on **AICc**

### 5. Validation
- Diagnostics of **residuals**  
- Statistical tests: **ADF** (Augmented Dickey-Fuller) and **Ljung-Box**

### 6. Forecasting
- Split between **training (2002–2021)** and **testing (2022–2023)**  
- Conclusion that the most suitable model was:  
  **ARIMA(2,1,2)(0,1,2)[12]**

---

## Results
The study highlights the **trends and fluctuations of the Portuguese automotive market** and demonstrates the practical application of modern forecasting techniques in R:  
- `fpp3`  
- `tsibble`  
- `forecast`  

---

## Visualization
The HTML version of the report is available on **GitHub Pages**:  
👉 [Open Report](https://miguelmarques2004.github.io/Forecasting-Vehicle-Sales-in-Portugal-2002-2023-/)

---
