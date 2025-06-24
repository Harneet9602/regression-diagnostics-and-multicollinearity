 📊 Regression Diagnostics & Multicollinearity Analysis

This repository contains code and explanations for performing Multiple Linear Regression and verifying the necessary statistical assumptions using synthetic datasets. It includes multicollinearity analysis using Variance Inflation Factor (VIF), residual diagnostics, and data improvement techniques like feature transformation and reduction.

 📁 Contents

- `Q1`: Simulated geographical dataset  
  - Multiple Linear Regression with Statsmodels  
  - Linearity checks using pairplots  
  - Residual normality (histogram, Q-Q plot, Shapiro-Wilk test)  
  - VIF calculation to detect multicollinearity  
  - Durbin-Watson test for autocorrelation  
  - Residuals vs. Fitted plot for homoscedasticity  
- `Q2`: Simulated sports performance dataset  
  - Initial VIF analysis  
  - Feature transformation (combining correlated variables)  
  - VIF analysis after transformation  

 🛠️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Statsmodels
- Seaborn
- Matplotlib
- Scipy (for statistical tests)

 📌 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/regression-diagnostics-and-multicollinearity.git
