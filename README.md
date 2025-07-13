# Streaming_Project
# 📊 Streaming Platform SQL Analysis Project

This project contains a comprehensive set of SQL queries to analyze various aspects of a hypothetical streaming platform, including subscriptions, content performance, user ratings, and consumption behavior.

---

## 📁 Project Overview

The SQL script (`STREAMING_PROJECT.sql`) is organized into the following sections:

- 📦 **Subscription Analysis** – Revenue, subscription growth, plan distribution.
- 🎬 **Content Analysis** – Genre distribution, content trends, average duration.
- ⭐ **Rating Analysis** – Rating categories, most rated content, gaps.
- 📈 **Data Context & User Behavior** – Watch time, top content, user acquisition.

---

## 🗃 Database Table Overview

This project assumes four main tables, each of which is used extensively in the queries:

| Table Name          | Description                                      |
|---------------------|--------------------------------------------------|
| `subscription_data` | Subscription plans, revenue, duration info       |
| `catalogue_data`    | Content metadata: titles, genres, country, status|
| `rating_data`       | User feedback and ratings                        |
| `consumption_data`  | Viewing duration, session details, content usage |

---

## 🔗 Dataset Download Links

Due to GitHub’s file size restrictions, the full datasets are hosted on Google Drive. Please download and import them into your SQL environment before running the queries.

| Dataset               | Download Link |
|------------------------|---------------|
| `subscription_data.csv` | [📥 Download](https://drive.google.com/file/d/1OWwdUJUSrGW33lwXOsbZ0zdVBeJlvkuY/view?usp=sharing) |
| `rating_data.csv`       | [📥 Download](https://drive.google.com/file/d/1u72xO0t-UhMptCLzXWmYqiCSTfWLYn5q/view?usp=sharing) |
| `consumption_data.csv`  | [📥 Download](https://drive.google.com/file/d/16Lgj4o7n4sjqT_IuPuQrZJ3si9Lceuot/view?usp=sharing) |
| `catalogue_data.csv`    | [📥 Download](https://drive.google.com/file/d/1H1jnG5DDX47c_REvgyqU27-x_NYiwCjQ/view?usp=sharing) |

---

## 🧠 SQL Concepts Covered

- Aggregations: `SUM()`, `AVG()`, `COUNT()`
- Grouping & Filtering: `GROUP BY`, `WHERE`, `HAVING`
- Window Functions: `LAG()`, `ROW_NUMBER()`
- Date Functions: `MONTH()`, `DATEPART()`, `DATEADD()`
- Conditional Logic: `CASE WHEN`
- Views: `CREATE VIEW`
- Joins: `INNER JOIN`, Cartesian joins

---

## 🔍 Sample Questions Answered

- What’s the revenue breakdown by plan type?
- Which months have the highest subscriptions and churn?
- What content genres are most common?
- Which Indian content performs the best?
- What’s the average duration of content?
- Which content drives the most user engagement?

---

## 🚀 How to Use

1. Clone this repository.
2. Download the datasets from the links above.
3. Import the CSV files into your SQL database (e.g., MySQL, PostgreSQL, SQL Server).
4. Open and run the `STREAMING_PROJECT.sql` file section by section.

> If you're using a specific SQL engine, you may need to adapt some syntax slightly (e.g., `DATEPART()` is T-SQL specific).

---



