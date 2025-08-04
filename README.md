📈 Stock Performance Analysis

📌 Project Objective

The goal of this project is to track and analyze the stock performance of five major companies — IBM, Microsoft, Tesla, Amazon, and Google — using a comprehensive, interactive dashboard. Data is fetched using the Alpha Vantage API, enabling users to gain valuable insights into price trends, volatility, and trading volume.

⚙️ Project Components

1️⃣ Data Extraction Source: Alpha Vantage API

Companies: AMZN, GOOGL, MSFT, IBM, TSLA

Data Fields: Open, Close, High, Low, Volume, Moving Averages

Time Frame: Last 2 years (up to Jan 29, 2025)

Tools: Python, following API documentation

2️⃣ ETL Pipeline ETL Process:

Extract: Pull historical stock data via Python scripts. ** Transform:** Feature engineering to calculate:

📈 Price Change: Close Price − Open Price

📊 Price Range**:** High Price − Low Price

🧮 Average Price: (High + Low + Close) / 3

⚡ Volatility: (High − Low) / Close × 100

Libraries Used: pandas, matplotlib, seaborn for EDA

Load:

Store cleaned data in a SQL database and visualize using Power BI.

🗄️ Data Storage Designed a SQL schema to organize stock prices and calculated metrics.

Used SQL queries for aggregations and trend analysis.

📊 Dashboard Highlights (Power BI) Date Table: Derived columns for Year, Month, Week Number, Day Number, and Weekend/Weekday.

KPIs: Close, Open, and Volume with DAX measures for:

Previous Day, Week, Month, and Year Comparisons

Month-on-month % change

Entity Relationship: Linked Date Table and Stock Data on Date for time-based filtering.

Visuals:

Slicers for Year, Month, and Date

Volatility calculation using standard deviation

Pie chart comparing trading volumes across companies

✅ Key Insights Track daily stock fluctuations and volatility.

Compare stock trading volumes to identify the most active stock.

Understand short- and long-term trends through dynamic visuals. ** 🧩 Tools & Tech Stack** Data Extraction & ETL: Python, Pandas, Matplotlib, Seaborn

Data Storage: SQL Database

**Dashboard & Visualization: **Power BI


## This is my Dashboard
![stock market dashboard](https://github.com/user-attachments/assets/b30731a8-7056-402a-9216-65a2d7e5aca4)

