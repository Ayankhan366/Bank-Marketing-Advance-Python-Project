# **Bank Market Data Analysis**

## **Overview**
This project analyzes customer application data from a financial institution to extract actionable insights.  
The analysis aims to improve decision-making processes in credit approval and risk management by understanding customer behavior and identifying key trends.

---

## **Dataset Details**
- **Total Records**: 49,999  
- **Features**: 122 columns  
- **File Size**: 46.5+ MB  

### **Key Attributes**
- **SK_ID_CURR**: Unique customer identifier.  
- **TARGET**: Loan repayment status (`1`: Default, `0`: Non-default).  
- **NAME_CONTRACT_TYPE**: Type of loan (e.g., Cash loans, Revolving loans).  
- **AMT_INCOME_TOTAL**: Annual income of the client.  
- **AMT_CREDIT**: Total credit amount for the loan.  
- **CNT_CHILDREN**: Number of children.  
- **FLAG_OWN_CAR**: Whether the client owns a car.  
- **FLAG_OWN_REALTY**: Whether the client owns real estate.  
- **AMT_REQ_CREDIT_BUREAU_X**: Frequency of credit inquiries (various timeframes).  

---

## **Objectives**
1. **Descriptive Analysis**:  
   - Understand customer demographics and financial patterns.  
   - Explore correlations between variables like income, loan amount, and default rate.  
2. **Data Exploration**:  
   - Visualize distributions and relationships among different variables.  
   - Identify any trends or patterns that could influence credit risk.  
3. **Risk Analysis**:  
   - Segment customers based on financial behavior and risk levels.  
   - Analyze the impact of factors like income, credit amount, and ownership on defaults.

---

## **Steps Undertaken**

### **1. Data Cleaning**
- Handled missing values in critical columns such as `AMT_REQ_CREDIT_BUREAU_*`.  
- Normalized numerical variables to standardize scales.  

### **2. Exploratory Data Analysis (EDA)**
- Visualized distributions of income, credit amounts, and default rates.  
- Analyzed categorical features like gender, contract type, and property ownership.  
- Explored relationships between income, loan amounts, and default status.

### **3. Feature Engineering**
- Created new features like `Debt-to-Income Ratio (DTI)`.  
- Grouped clients based on demographic and financial characteristics.  

### **4. Visualization**
- Developed plots to communicate key findings effectively:  
  - Income vs. Default Rate  
  - Loan Amount Distribution  
  - Correlation Heatmaps  

---

## **Key Findings**
- High-income clients tend to have lower default rates, but loan amount relative to income significantly impacts risk.  
- Customers with multiple credit inquiries are more likely to default.  
- Ownership of real estate correlates with reduced risk, while car ownership shows minimal impact.  

---

## **Technologies Used**
- **Python Libraries**:  
  - `pandas`, `numpy` for data manipulation  
  - `matplotlib`, `seaborn` for visualization  
- **Jupyter Notebook** for code and documentation  

---

## **Future Work**
- Expand analysis with additional datasets, such as transaction history.  
- Create dashboards for non-technical stakeholders to visualize key insights.  



