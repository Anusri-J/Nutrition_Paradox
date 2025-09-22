**🍽️ Nutrition_Paradox**

A project that explores the global nutrition paradox — the coexistence of obesity and malnutrition — using WHO’s public datasets.
It transforms raw health data into actionable insights with Python, SQL, and Power BI/Streamlit, offering interactive dashboards for exploration and analysis.

**📌 Project Overview**

This project focuses on:

🥗 Tracking global malnutrition prevalence (underweight, stunting, wasting)
🍔 Analyzing obesity and overweight trends across countries, genders, and age groups
⚖️ Comparing malnutrition and obesity to reveal paradoxical coexistence in populations
📊 Providing a user-friendly Power BI dashboard for researchers, policymakers, and learners

**🧠 Skills Gained**

🔗 Connecting to and extracting structured data from WHO APIs
📄 Reading and organizing JSON & CSV data
🧹 Cleaning, transforming, and preparing data in Python
🗄️ Designing normalized SQL schemas for health datasets
🖥️ Building interactive dashboards in Power BI and Streamlit
⏱️ Writing efficient queries to analyze global nutrition trends

**🧩 Steps Involved**

✅ Step 1: Data Collection

Connected to the WHO API and downloaded datasets for obesity and malnutrition indicators.

✅ Step 2: Data Cleaning & Structuring

Processed missing values, standardized formats, and ensured consistency.

Created separate datasets for obesity, malnutrition, and combined indicators.

✅ Step 3: SQL Database Design

Built the database nutrition_paradox with:

obesity table

malnutrition table

combined table (joined on country, year, gender, age group).

✅ Step 4: Analytical SQL Queries

5 queries for obesity (e.g., top obese countries, gender patterns).

5 queries for malnutrition (e.g., stunting, wasting prevalence).

5 combined queries (e.g., obesity vs malnutrition trends by country).

✅ Step 5: Visualization & Dashboard

Created a Power BI dashboard with comparisons, breakdowns, and trends.

**📊 Sample Query Outputs**

Top Obesity Countries ➡️ Countries with highest average obesity rates.
Top Malnutrition Countries ➡️ Countries with highest stunting/wasting prevalence.
Gender-wise Comparison ➡️ Obesity vs malnutrition across male/female populations.
Age-group Trends ➡️ Breakdown of nutrition issues in children, adults, elderly.
Nutrition Paradox Countries ➡️ Nations facing both high obesity and malnutrition simultaneously.

**🛠 Tech Stack Used**

✅ Python – Data cleaning, preprocessing, and API integration
✅ MySQL / PostgreSQL – Structured storage of obesity & malnutrition data
✅ Power BI – Interactive dashboards for storytelling with visuals
✅ Pandas, Requests, Matplotlib/Seaborn – Data wrangling and EDA
✅ WHO Global Health Observatory API – Source of raw nutrition data

**🎯 Business Use Cases**

🌍 Global Health Policy – Identify regions suffering from both undernutrition & obesity
🏥 Healthcare Planning – Support interventions targeting vulnerable demographics
📚 Education & Awareness – Help learners understand the paradox of nutrition transition
🔍 Research – Enable comparisons of obesity vs malnutrition over time & geography

**🧩 Key Learnings**

📡 Accessing and parsing real-world APIs (WHO GHO)
🧾 Normalizing complex datasets into relational SQL schemas
🧠 Designing analytical queries for meaningful health insights
📈 Building intuitive dashboards to communicate results effectively

**📎 References**

🔗 WHO Global Health Observatory – https://www.who.int/data/gho

📘 Power BI Documentation – https://learn.microsoft.com/power-bi/

🐍 Streamlit Docs – https://docs.streamlit.io/

🗄️ SQL Docs – https://dev.mysql.com/doc/
