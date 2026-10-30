# 💳 PayFlow | Fintech Payment Analysis

## 📌 Project Overview

For this study, I performed a comprehensive payment analysis using transaction data from a fictional fintech platform called PayFlow. Throughout this process, my focus was on examining overall payment performance, identifying key failure patterns across transactions, and translating my data-driven findings into strategic recommendations for product management.

## 🎯 Business Problem

To guide my analysis, I structured the primary business problem around evaluating PayFlow's payment ecosystem, examining overall performance, and addressing transaction drop-offs. Specifically, I set out to answer the core questions defined for this study:

- How successful are payment attempts?
- Which payment methods have higher failure rates?
- What are the most common failure reasons?
- How does transaction volume differ
  across payment methods and categories?
- Which areas should be investigated further?

## 📊 Dataset

The dataset contains 1,200 synthetic payment
transactions from January to June 2026.

Each row represents one payment attempt.

The dataset includes transaction dates,
payment methods, transaction amounts,
transaction statuses, customer segments,
merchant categories, and failure reasons.

The data was created for educational purposes.

## 🛠️ Tools

- Microsoft Excel
- Microsoft SQL Server (SSMS) & T-SQL
- Google Sheets
- Looker Studio
- GitHub

## ❓ Business Questions

1. How many transactions are recorded?
2. How are transactions distributed by status?
3. What is the average successful transaction amount?
4. Which payment method has the highest
   successful transaction volume?
5. What are the most common failure reasons?
6. Which customer segment has the highest
   average transaction amount?
7. How does successful transaction volume
   differ by merchant category?
8. Which city generates the highest
   successful transaction volume?

## 🔄 Analysis Process

### 1. Data Exploration

I conducted an initial exploratory data analysis in Excel to inspect data quality, audit missing values, and verify field data types prior to SQL ingestion.

### 2. SQL Analysis

I wrote structured T-SQL queries in SSMS using SELECT, WHERE, GROUP BY, and ORDER BY clauses along with functions like COUNT, SUM, AVG, and TOP. This enabled me to aggregate transaction metrics, analyze status distributions, and identify key performance patterns effectively.

### 3. Data Visualization

I designed an interactive Looker Studio dashboard to visualize transaction performance and category comparisons.

### 4. Business Interpretation

I translated analytical query results into actionable findings, core business insights, and strategic recommendations.

## 📈 Dashboard

📄 [View Payment Performance Dashboard (PDF)](dashboard/PayFlow_-_Payment_Transactions_Dashboard.pdf)

🔗 Live Looker Studio Dashboard:
[View Dashboard](https://datastudio.google.com/s/rxvHbRuOYyk)

### 💡 Key Insights

### Payment Method Performance

Credit Card generated the highest transaction volume among all available payment methods, followed by Debit Card and Digital Wallet, while Bank Transfer recorded the lowest volume.

### Merchant Category Performance

Travel generated the highest transaction volume, while Grocery and Dining recorded higher successful transaction counts.

### Regional Performance

Based on the regional distribution, Istanbul stood out as the leading hub with the highest transaction volume and transaction count


## 🚀 Recommendations

 *Optimize card and digital payments.
 *Leverage high-value travel segments.
 *Streamline high-frequency daily categories.
 *Prioritize regional growth in IstanbuL.

## 🏁 Conclusion

This project demonstrates the process of
transforming raw payment data into
business insights.

By combining data exploration, SQL analysis,
dashboard development, and storytelling,
the analysis identifies areas for further
investigation and potential improvement.

## 📁 Project Structure

- `data/` — Source dataset
- `sql/` — SQL queries
- `dashboard/` — Dashboard screenshot and PDF
- `insights/` — Findings and recommendations


