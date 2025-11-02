
# 🛍️ Customer Shopping Behavior Analysis – Retail Purchase & Subscription Insights  
**Analyzing customer behavior, segmentation, and discount impact to drive marketing and retention strategies using SQL, Python, and Power BI**

---

## 📌 Table of Contents  
- [Overview](#overview)  
- [Business Problem](#business-problem)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Project Structure](#project-structure)  
- [Data Cleaning & Preparation](#data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#research-questions--key-findings)  
- [Dashboard](#dashboard)  
- [How to Run This Project](#how-to-run-this-project)  
- [Final Recommendations](#final-recommendations)  
- [Author & Contact](#author--contact)  

---

## 📊 Overview  
This project analyzes 3,900 retail transactions to uncover customer behavior patterns, segment buyers, and evaluate the impact of discounts and subscriptions. The goal is to generate actionable insights for marketing, product positioning, and customer retention.

---

## ❓ Business Problem  
Retail businesses need to understand customer preferences and purchasing behavior to improve engagement and revenue. This project addresses:

- Segmenting customers based on purchase history  
- Identifying high-value behaviors linked to discounts and subscriptions  
- Evaluating product performance and shipping preferences  
- Recommending strategies to boost loyalty and profitability  

---

## 📂 Dataset  
- Located in the `data/` folder  
- File: `customer-shopping-behavior.csv`  
- Contains 3,900 customer transactions with demographics, product categories, purchase history, shipping type, and subscription status  

---

## 🛠️ Tools & Technologies  
- **Python**: pandas, matplotlib for cleaning, feature engineering, and EDA  
- **PostgreSQL**: structured queries for behavioral and financial insights  
- **Power BI**: interactive dashboard for stakeholder-style reporting  

---

## 🗂️ Project Structure  
```
customer-shopping-behavior/
├── SQL/                           # SQL queries and scripts
│   └── sql.sql
├── dashboard/                     # Power BI dashboards
│   └── power bi.pbix
├── data/                          # Raw dataset
│   └── customer-shopping-behavior.csv
├── images/                        # Visual assets
│   └── dashboard.png
├── notebooks/                     # Python notebooks
│   └── Exploratory-data-analysis.ipynb
└── README.md                      # Project documentation
```

---

## 🧹 Data Cleaning & Preparation  
- Imputed missing review ratings using category-wise medians  
- Removed redundant fields like `promo_code_used` after consistency checks  
- Created new features:
  - `age_group` from age bins  
  - `purchase_frequency_days` from purchase history  
- Loaded cleaned data into PostgreSQL for deeper analysis  

---

## 📊 Exploratory Data Analysis (EDA)  
**Customer Behavior Patterns:**  
- 80% of customers classified as **Loyal**  
- Repeat buyers (5+ purchases) more likely to be subscribers (958 vs. 2518)  

**Revenue Insights:**  
- Male customers generated **2× more revenue** than female customers ($157K vs. $75K)  
- **Young Adults** led revenue contribution ($62K), followed by Middle-aged and Adults  

**Product Ratings & Sales:**  
- Top-rated items: Gloves (3.86), Sandals, Boots  
- Best-sellers by category: Jewelry, Blouse, Sandals, Jacket  

**Discount Behavior:**  
- 839 customers used discounts yet spent **above average**  
- High discount dependency: Hat, Sneakers, Coat (~50%)  

**Shipping Preferences:**  
- Express shipping users spent slightly more ($60.48 vs. $58.46)  

**Subscription Impact:**  
- Subscribers = 27% of customer base  
- Higher repeat purchase rates among subscribers  

---

## 🔍 Research Questions & Key Findings  
- **Who are the most loyal and high-frequency customers?**  
- **Which products perform best by rating and sales?**  
- **Do discounts drive high-value purchases?**  
- **How do subscriptions affect repeat buying behavior?**  
- **What shipping preferences correlate with higher spending?**  

---

## 📈 Dashboard  
The Power BI dashboard includes:  
- Customer segmentation and loyalty analysis  
- Revenue breakdown by gender and age group  
- Product ratings and best-sellers  
- Discount usage and impact  
- Subscription behavior and shipping preferences  

📁 File: `dashboard/power bi.pbix`  
📷 Preview: `images/dashboard.png`  

---

## ⚙️ How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/swarnali2001/customer-shopping-behavior.git
   cd customer-shopping-behavior
   ```

2. **Explore the dataset**  
   - Located at `data/customer-shopping-behavior.csv`

3. **Run Python notebook for EDA**  
   - `notebooks/Exploratory-data-analysis.ipynb`

4. **Execute SQL queries for insights**  
   - `SQL/sql.sql`

5. **Open Power BI dashboard**  
   - `dashboard/power bi.pbix`  
   - Preview available in `images/dashboard.png`

---

## ✅ Final Recommendations  
- Promote subscriptions to repeat buyers  
- Launch loyalty programs for high-frequency customers  
- Refine discount strategies to protect margins  
- Prioritize top-rated products in marketing campaigns  
- Target high-revenue age groups and express-shipping users  

---


Would you like me to generate a badge section or a one-liner project summary for your LinkedIn profile next?
