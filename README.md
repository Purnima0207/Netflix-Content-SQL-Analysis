# 🎬 Netflix SQL Analysis

## 📖 About The Project

This project explores the Netflix Movies and TV Shows dataset using SQL to answer real-world business questions and generate actionable insights.

The analysis focuses on understanding Netflix's content library, identifying trends in content production, audience ratings, release patterns, and geographical distribution of movies and TV shows.

This project demonstrates practical SQL skills used in Data Analytics and Business Intelligence roles.

---

## 🎯 Project Goals

- Analyze Netflix content distribution
- Compare Movies vs TV Shows
- Identify top-producing countries
- Explore rating classifications
- Understand content growth trends
- Practice advanced SQL querying techniques

---

## 🛠️ Tech Stack

- SQL
- PostgreSQL / MySQL
- Jupyter Notebook
- Python
- Pandas

---

## 📂 Dataset Information

The dataset contains:

- Show ID
- Title
- Type (Movie / TV Show)
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre (Listed In)
- Description

---

## 🔍 Business Problems Solved

### Content Analysis
- Total number of Movies and TV Shows
- Percentage distribution by content type
- Most common ratings

### Country Analysis
- Top countries contributing content
- Country-wise content trends

### Genre Analysis
- Most popular genres on Netflix
- Genre frequency comparison

### Time Series Analysis
- Content added by year
- Release trends over time
- Netflix catalog growth

### Advanced SQL Queries
- Aggregations
- Joins
- CTEs
- Window Functions
- Ranking Functions
- Subqueries

---

## 📊 Key Insights

- Movies represent the majority of Netflix content.
- The United States contributes the largest content share.
- TV Shows have grown significantly over recent years.
- TV-MA is one of the most common content ratings.
- Netflix expanded its content library rapidly after global expansion.

---

## 📁 Repository Structure

```text
Netflix_SQL_Analysis/
│
├── Netflix_SQL_Analysis.ipynb
├── netflix_titles.csv
├── README.md
└── screenshots/
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/yourusername/Netflix_SQL_Analysis.git
```

### Navigate to Project

```bash
cd Netflix_SQL_Analysis
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Netflix_SQL_Analysis.ipynb
```

---

## 💻 Sample Query

```sql
SELECT type,
       COUNT(*) AS total_titles
FROM netflix
GROUP BY type;
```

---

## 📈 Skills Demonstrated

- SQL Querying
- Data Cleaning
- Data Exploration
- Data Analysis
- Business Intelligence
- Problem Solving
- Analytical Thinking

---

## 🔮 Future Enhancements

- Build a Power BI Dashboard
- Create Interactive Visualizations
- Perform Recommendation Analysis
- Automate SQL Reporting

---

## 👨‍💻 Author

**Nishant Deshwal**

Aspiring Data Analyst | SQL | Python | Data Visualization

### Connect With Me

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

⭐ If you found this project helpful, please consider starring the repository.
