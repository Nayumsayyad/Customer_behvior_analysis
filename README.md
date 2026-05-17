🛒📊 Customer Shopping Behavior Analysis

Turning Raw Shopping Data into Actionable Business Insights 🚀

---

🌟 Project Overview

This project analyzes customer shopping behavior using transactional and demographic data to uncover:

* 💰 Revenue patterns
* 🛍️ Product preferences
* 👥 Customer segments
* 🎯 Subscription behavior
* 📦 Shipping trends

The complete analytics pipeline was built using:
🐍 Python • 🗄️ SQL • 🐘 PostgreSQL • 📈 Power BI • 🎨 Gamma AI

---

📂 Dataset Information

| Feature          | Details                  |
| ---------------- | ------------------------ |
| 📄 Rows          | 3,900                    |
| 📊 Columns       | 18                       |
| 🧑 Customer Data | Age, Gender, Location    |
| 🛒 Purchase Data | Category, Amount, Season |
| 🎁 Promotions    | Discounts, Promo Codes   |
| ⭐ Reviews        | Product Ratings          |
| 🚚 Shipping      | Standard & Express       |

---

🛠️ Tech Stack

👨‍💻 Programming & Analysis

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 📊 Seaborn

🗄️ Databases

* 🐘 PostgreSQL
* 🐬 MySQL
* 🏢 SQL Server

🔌 Database Connectivity

* ⚡ psycopg2
* 🔗 SQLAlchemy

📈 Visualization & Reporting

* 📊 Power BI
* 🎨 Gamma AI
* 📑 PowerPoint

---

🔄 Project Workflow

1️⃣ Data Loading

✔️ Imported dataset using Pandas
✔️ Checked data structure and summary statistics

```python id="xix7bh"
df.info()
df.describe()
```

---

2️⃣ Data Cleaning 🧹

Tasks Performed

* ❌ Handled missing values
* 📝 Renamed columns into snake_case
* 🔁 Removed redundant columns
* ✅ Fixed inconsistent values

Example

```python id="pf13kg"
df.columns = df.columns.str.lower().str.replace(' ', '_')
```

---

3️⃣ Feature Engineering ⚙️

Created new features like:

| Feature                    | Purpose                      |
| -------------------------- | ---------------------------- |
| 👨‍👩‍👧‍👦 age_group      | Customer segmentation        |
| 📅 purchase_frequency_days | Numerical frequency analysis |

---

📊 Exploratory Data Analysis (EDA)

Key Analysis Areas

💰 Revenue Analysis

* Gender-wise revenue
* Age-group contribution

 🛍️ Product Insights

* Top-rated products
* Best-selling categories

👥 Customer Behavior

* Loyal vs new customers
* Subscriber analysis

 🚚 Shipping Analysis

* Standard vs Express purchases

---

🗄️ SQL Business Analysis

🔥 Important SQL Questions Solved

✅ Revenue by Gender
✅ Top 5 Products by Ratings
✅ Loyal Customer Segmentation
✅ Discount Purchase Analysis
✅ Repeat Buyers vs Subscription
✅ Revenue by Age Group

---

📈 Power BI Dashboard

 Dashboard Includes

🎯 KPI Cards
📊 Revenue Trends
🛍️ Product Performance
👥 Customer Segmentation
🚚 Shipping Insights
⭐ Product Ratings
🎛️ Interactive Filters & Slicers

---

 💡 Key Business Insights

 📌 Findings

* Subscribers spend more on average 💰
* Certain products rely heavily on discounts 🎁
* Express shipping users generate higher revenue 🚚
* Loyal customers contribute major sales 📈
* Specific age groups dominate purchases 👥

---

 🚀 Business Recommendations

✅ Improve loyalty programs
✅ Promote subscription benefits
✅ Optimize discount strategies
✅ Focus on high-value customer segments
✅ Highlight best-selling products in campaigns

---

 ▶️ How to Run the Project

 1️⃣ Install Libraries

```bash id="5zdyio"
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

---

 2️⃣ Run Jupyter Notebook


 3️⃣ Connect PostgreSQL

from sqlalchemy import create_engine

engine = create_engine(
    "postgresql+psycopg2://username:password@localhost:5432/database_name"
)

 4️⃣ Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop 📊

---

 🎯 Project Outcome

This project demonstrates practical skills in:

✅ Data Cleaning
✅ Exploratory Data Analysis
✅ SQL Querying
✅ Database Integration
✅ Dashboard Development
✅ Business Reporting

---

👨‍💻 Author

 Nayum Sayyad

🚀 Aspiring Data Engineer | Data Analytics Enthusiast

💼 Skills:
Python • SQL • PostgreSQL • Power BI • Data Visualization • EDA
