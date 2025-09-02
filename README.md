# Customer Support Data Analytics with Tableau Dashboards

## Project Objective
To analyze customer support interaction data and **classify Customer Satisfaction (CSAT) scores** using machine learning. The project also aims to uncover key drivers of satisfaction and build **Tableau dashboards** for business decision-making.

---

## Dataset
- **File**: `Customer_support_data.csv`  
- **Size**: ~5K records (Flipkart-like dataset)  
- **Key Fields**:  
  - Agent & shift details (`Agent_name`, `Supervisor`, `Manager`, `agent_shift`, `Tenure Bucket`)  
  - Order & issue timestamps (`Order_Date_Time`, `Issue_reported at`, `issue_responded at`, `Survey_response_Date`)  
  - Product & transaction details (`Item_price`, `category`, `Sub-category`, `channel_name`)  
  - Customer feedback (`Customer Remarks`, `csat_score`)  

---

## Tasks Performed
1. **Exploratory Data Analysis (EDA)**  
   - Data cleaning, missing value handling, outlier checks  
   - Distribution analysis of CSAT scores  
   - Temporal & categorical patterns  

2. **Feature Engineering**  
   - Response time metrics  
   - Text sentiment & remark length features  
   - Price bucket and high-value order flag  
   - Agent-wise average CSAT & category frequency  

3. **Modeling**  
   - ML algorithms: Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, KNN, MLP  
   - Handled imbalance using **SMOTE**  
   - Evaluated with Accuracy, F1-score, Confusion Matrix  

4. **Visualization**  
   - Python plots (Matplotlib, Seaborn, SHAP)  
   - Tableau dashboards for interactive insights  

---

## Key Insights
- Longer **response times** negatively impact CSAT.  
- Certain **categories/sub-categories** consistently score lower.  
- **High-value orders** correlate with higher risk of dissatisfaction.  
- **Agent-level differences** show training/monitoring needs.  
- Negative sentiment in **customer remarks** strongly predicts low CSAT.  

---

## Business Recommendations
- **Reduce response times** via workflow optimization & shift balancing.  
- **Targeted training** for low-performing agents & supervisors.  
- **Focus on at-risk categories** with better product/service policies.  
- Prioritize **high-value customers** for premium handling.  
- Integrate **real-time sentiment analysis** into support workflows.  

---

## Note
This repository is built as part of a **Data Analysis CV Project** to showcase skills in:  
- Data wrangling & visualization  
- Machine learning for classification  
- Feature engineering  
- Business intelligence with Tableau  
