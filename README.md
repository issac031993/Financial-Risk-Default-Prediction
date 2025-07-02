# 💹 Financial Risk & Default Prediction: End-to-End Analysis
Predicted corporate default risk using balance sheet indicators. Modeled stock volatility through mean-variance analysis to assess market risk. Informed creditworthiness and investor decision-making strategies.

The FRA project consists of **two parts**:

- **Part A:** Focuses on default prediction and financial analysis, assessing a company's ability to meet its debt obligations.  
- **Part B:** Involves market risk analysis by calculating the mean and standard deviation of stock returns, providing insights into stock performance and volatility.

✅ These analyses are valuable tools for **investors, financial institutions, and stakeholders** to make informed decisions about creditworthiness and investment strategies.

---

## 🚀 Skills & Tools Covered
- 💳 **Default Prediction**
- 📊 **Financial Analysis & Balance Sheet Interpretation**
- 📝 **Creditworthiness Assessment**
- 📈 **Market Risk & Volatility Analysis**
- 🐍 Python: pandas, numpy, seaborn, matplotlib, scikit-learn

---

## 🏦 Part A: Default Prediction & Financial Health Analysis

### 🔍 Overview
Analyzed company financial metrics to predict defaults, helping financial institutions proactively manage credit risk.

- **Dataset:** 2,058 companies, 58 financial features
- **Target:** `Default` (1 = defaulted, 0 = not defaulted)
- **Process:** Dropped identifiers, imputed nulls, capped outliers, selected top correlated features.

### 🚀 Key Results
| Model                | Accuracy | AUC   | Precision (Default) | Recall (Default) |
|-----------------------|----------|-------|---------------------|------------------|
| Logistic Regression   | 0.77     | 0.86  | 0.28                | 0.82             |
| Random Forest         | 0.92     | 0.77  | 0.74                | 0.25             |
| LDA                   | 0.91     | 0.80  | 0.60                | 0.37             |

✅ **Recommendation:**  
- Use Logistic Regression for highest **discriminatory power (AUC)**.
- Use Random Forest for **overall accuracy**.
- Explore ensemble approaches for robust performance.

### 📈 Key Visualizations
![Heatmap of top 10 corelated features](https://github.com/user-attachments/assets/05d10352-b630-429e-864a-20245681862e)

![ROC Curve Logistic Regression](https://github.com/user-attachments/assets/a121cc87-f3cc-46c0-b1b5-b043fee55463)

![ROC Curve Random Forest](https://github.com/user-attachments/assets/e496b254-86a1-4acd-98ca-9b9d3f386119)

!ROC Curve Linear Discriminant Analysis](https://github.com/user-attachments/assets/ff671a03-0d77-48c8-a9d7-eec5af5ecf81)

---

## 📊 Part B: Market Risk Analysis of Indian Stocks

### 🔍 Overview
Performed risk analysis on 6 years of weekly prices for 10 Indian stocks, calculating log returns, means, and standard deviations to understand volatility and returns.

### 🚀 Key Findings
| Stock             | Mean Return | Std Dev (Volatility) |
|-------------------|-------------|----------------------|
| Infosys           | 0.0028      | 0.035                |
| Indian_Hotel      | 0.0003      | 0.047                |
| SAIL              | -0.0035     | 0.062                |
| Idea_Vodafone     | -0.0106     | 0.104                |
| Jet_Airways       | -0.0095     | 0.098                |

✅ **Insights:**  
- Higher returns generally tied to higher volatility (**risk-return tradeoff**).
- Stocks like `Idea_Vodafone` & `Jet_Airways` show **high volatility with negative returns**, indicating riskier profiles.

### 📈 Key Visualizations
![Stock Price Trend of Indian Hotel over Time](https://github.com/user-attachments/assets/2aa054eb-e480-4f0f-9d90-c581089d6484)

![Stock Price Trend of Indian Hotel over Time](https://github.com/user-attachments/assets/20e87b48-5e62-48c0-8a0c-26715da8157c)

![Relationship Between Stock Means and Standard Deviation](https://github.com/user-attachments/assets/89d750c4-b658-44e4-930f-353989862fa3)

---

## ⚙️ How to Run
📌 This repo includes Jupyter notebooks.  
- Clone the repo, install dependencies (`pip install -r requirements.txt`), and open notebooks to explore.

---

## 🤝 About Me
I completed this project independently, showcasing end-to-end capabilities from data wrangling and EDA to advanced machine learning, risk analysis, and actionable business recommendations.

🔗 [LinkedIn](https://linkedin.com/in/yourprofile)

---

✅ **Thanks for exploring my financial risk & market analysis projects!**
