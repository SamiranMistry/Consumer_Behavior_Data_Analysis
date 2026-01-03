# 📊 Customer Shopping Behavior Analysis

## 📌 Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, discount impact, and subscription behavior to support data-driven business decisions.

The project demonstrates a complete end-to-end data analytics workflow, covering data preparation, analysis, visualization, and reporting.

---

## 📂 Dataset
- **Total Records:** 3,900  
- **Total Columns:** 18  

### Key Data Fields
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Shopping Behavior:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  

### Data Quality Notes
- Missing values were identified in the **Review Rating** column  
- Missing values were handled using median imputation by product category

---

## 🛠 Tools & Technologies
- **Python:** pandas, numpy  
- **Jupyter Notebook:** Data loading, EDA, data cleaning  
- **PostgreSQL:** SQL-based business analysis  
- **Power BI:** Interactive dashboard & visualization  
- **Microsoft Excel:** Initial data review  
- **Gamma:** Report and presentation creation  

---

## 🔄 Project Workflow

### 1. Data Loading & Exploration (Python)
- Loaded dataset using pandas  
- Reviewed dataset structure and summary statistics  
- Identified missing values and inconsistencies  

### 2. Data Cleaning & Feature Engineering
- Handled missing review ratings using category-level median values  
- Standardized column names to snake_case  
- Removed redundant fields  
- Created new features such as:
  - Age groups
  - Purchase frequency metrics

### 3. Database Integration (PostgreSQL)
- Loaded cleaned data into PostgreSQL  
- Prepared dataset for structured SQL analysis  

### 4. SQL Analysis (Business Use Cases)
- Revenue analysis by gender  
- Subscriber vs non-subscriber spending comparison  
- Identification of high-spending discount users  
- Top-rated products analysis  
- Shipping type impact on purchase value  
- Discount dependency analysis  
- Customer segmentation (New, Returning, Loyal)  
- Revenue contribution by age group  

### 5. Power BI Dashboard
- Built an interactive dashboard to visualize:
  - Revenue trends
  - Customer segmentation
  - Product performance
  - Discount and subscription insights  

---

## 📈 Dashboard
![Dashboard Model](/assets/Dashboard.png)

---

## ✅ Key Results & Insights
- Subscribers generate higher average revenue compared to non-subscribers  
- Loyal customers contribute significantly to total sales  
- Certain products show high dependency on discounts  
- Express shipping customers tend to have higher purchase values  
- Specific age groups contribute the most to overall revenue  

---

## 💡 Business Recommendations
- Strengthen subscription benefits to increase recurring revenue  
- Introduce loyalty programs for repeat customers  
- Optimize discount strategies to balance sales and profitability  
- Promote high-rated and high-performing products  
- Use targeted marketing for high-value customer segments  

---

## ▶️ How to Run the Project

### Python & EDA
1. Clone the repository
2. Open Jupyter Notebook and run the analysis notebook

### PostgreSQL

Import the cleaned dataset into PostgreSQL

### Execute SQL scripts from the sql folder

### Power BI

Open the .pbix file in Power BI Desktop

### Refresh data sources if required


## 📬 Contact

Author:**Samiran Mistry**
GitHub: https://github.com/SamiranMistry
LinkedIn: https://www.linkedin.com/in/samiranmistry
