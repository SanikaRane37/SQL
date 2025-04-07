# Netflix Dataset SQL Analysis

This project explores and analyzes the **Netflix dataset** using SQL. The goal is to gain meaningful insights into the content available on Netflix, such as distribution by type, most common ratings, trends over time, and other useful patterns.

---

## 📁 Dataset

The dataset used is the **Netflix Movies and TV Shows dataset**, which includes:

- `show_id`: Unique ID for every show  
- `type`: Type of content – Movie or TV Show  
- `title`: Title of the content  
- `director`: Director's name  
- `cast`: List of actors  
- `country`: Country of production  
- `date_added`: Date when the show was added to Netflix  
- `release_year`: Release year of the show  
- `rating`: Rating of the content (e.g., PG, TV-MA)  
- `duration`: Duration of the show  
- `listed_in`: Genre(s)  
- `description`: Short summary  

---

## 🔍 Key SQL Analyses Performed

1. Count the number of Movies vs TV Shows  
2. Find the most common rating for movies and TV shows  
3. List all movies released in a specific year (e.g., 2020)  
4. Find the top 5 countries with the most content on Netflix  
5. Identify the longest movie  
6. Find content added in the last 5 years  
7. Find all the movies/TV shows by director **Rajiv Chilaka**  
8. List all TV shows with more than 5 seasons  
9. Count the number of content items in each genre  
10. Find each year and the average number of content releases in India on Netflix. Return the **top 5 years** with the highest average.  
11. List all movies that are documentaries  
12. Find all content without a director  
13. Find how many movies actor **Salman Khan** appeared in during the last 10 years  
14. Find the top 10 actors who have appeared in the most movies produced in India  
15. Categorize the content based on the presence of the keywords **"kill"** and **"violence"** in the description field.  
    - Label content containing these keywords as **"Bad"** and all other content as **"Good"**  
    - Count how many items fall into each category  

---

## 🛠 Tools & Tech

- **SQL**: Core analysis language (tested on MySQL/PostgreSQL syntax)  
- **DBMS**: Compatible with MySQL, PostgreSQL, SQLite  
- **Data Source**: [Kaggle - Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  

---

## ✅ Requirements

- SQL-compatible database engine (e.g., MySQL, PostgreSQL, SQLite)  
- SQL client or interface (e.g., MySQL Workbench, DBeaver, pgAdmin)  

---

## 📊 Output

Most queries return:

- Clean tabular results  
- Grouped and aggregated values  
- Insightful breakdowns by type, year, genre, etc.  

You can also export query results and build visualizations using tools like:

- Power BI  
- Tableau  
- Jupyter Notebooks (Python)

---

## 🧠 Future Improvements

- Create SQL views and stored procedures for reusable insights  
- Build an interactive dashboard with data visualizations  
- Explore machine learning models or time-series forecasting  

---

## 🙌 Acknowledgments

- **Netflix** for content inspiration  
- **Kaggle** for hosting the dataset  
