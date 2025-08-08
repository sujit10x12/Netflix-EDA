# 📊 Netflix Movies and TV Shows Data Analysis using Python
![netflix_logo](https://github.com/user-attachments/assets/fac8704e-0b48-4cf9-a636-54ba635e5059)

---

## 👀 What’s This Project About?

This project explores and visualizes the **Netflix Movies and TV Shows dataset**, originally sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). The goal is to uncover patterns in Netflix's content library over time, including trends by genre, country, type, and more. The project also demonstrates data cleaning, EDA, and visualization techniques using Python.

> ✅ **You can access the complete notebook here:** [🔗 View Jupyter Notebook](/Netflix_Data_Exploration.ipynb)

---

## 🎯 Objective
The goal of this project is to explore the characteristics and patterns of the Netflix Streaming data and communicate the findings effectively using data visualization tools. By answering the following questions I've conducted an exploratory data analysis of the streaming data of Netflix.

---

## 🛠️ Tech Stack
 - Python 3.x
 - Jupyter Notebook
 - Pandas, NumPy
 - Matplotlib, Seaborn
 - Github

---

## 📁 Dataset Details

**File:** `netflix_titles.csv`  
**Source:** [Kaggle - Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)  
**Last Updated:** 2021 (as per source)

---

## 📊 Columns Description

| Column Name    | Description |
|----------------|-------------|
| `show_id`      | Unique identifier for each show |
| `type`         | Either *Movie* or *TV Show* |
| `title`        | Title of the Movie or TV Show |
| `director`     | Director(s) of the content |
| `cast`         | Leading actors/actresses |
| `country`      | Country where the content was produced |
| `date_added`   | Date when the content was added to Netflix |
| `release_year` | Year when the content was originally released |
| `rating`       | Maturity rating (e.g., TV-MA, PG, R) |
| `duration`     | Length of the content — in minutes for Movies, or number of seasons for TV Shows |
| `listed_in`    | Genre(s) or categories |
| `description`  | Brief summary of the show or movie |

---

## ❓ Key Business Questions
 - What is the total number of movies and TV shows available on Netflix?
 - How has the distribution of content (movies and TV shows) changed over time? For example, how many movies and TV shows were released in each year?
 - What are the most common genres of movies and TV shows on Netflix?
 - Which country produces the most movies and TV shows on Netflix?
 - What are the most popular ratings on Netflix?
 - Which were the top years in terms of the number of titles released?
 - What are the Number of Content Items in Each Genre?
 - Which Months and days Have the Most Content Releases?

---

## ✅ Solution
Insights or key findings for the questions mentioned above. Include relevant graphs and visualizations.

### 1. What is the total number of movies and TV shows available on Netflix?  
   <img width="389" height="409" alt="image" src="https://github.com/user-attachments/assets/da7bdbfd-8aed-40c3-987e-8892eb51f407" />
   
### 2. How has the distribution of content (movies and TV shows) changed over time? For example, how many movies and TV shows were released in each year?
   <img width="1160" height="545" alt="image" src="https://github.com/user-attachments/assets/aca5261f-83c4-43db-9a6d-edcaf317082b" />

### 3. What are the Number of Content Items in Each Genre?
   <img width="1389" height="589" alt="image" src="https://github.com/user-attachments/assets/c7a3a932-26e6-4af2-83d8-bfeb86c883e4" />

### 4. Which country produces the most movies and TV shows on Netflix?  
   <img width="1245" height="525" alt="image" src="https://github.com/user-attachments/assets/fee12cac-d286-4834-891c-2fe8869af245" />
   
### 5. What are the most popular ratings on Netflix?  
   <img width="1389" height="589" alt="image" src="https://github.com/user-attachments/assets/2c759772-2e87-4919-8bbd-4f2b215fdef0" />

### 6. Which Months have the Most Content Releases?  
   <img width="1160" height="595" alt="image" src="https://github.com/user-attachments/assets/dd28c8dd-95d3-4a02-9f4f-61598fc19c59" />

### 7. Which Days have the Most Content Releases?  
   <img width="1169" height="578" alt="image" src="https://github.com/user-attachments/assets/5da7e2c0-200d-4cd2-9b01-eca34f5abbcd" />
   
---

##  🔍 Key Insights & Conclusions

- **`Broad Content Mix`:** Movies make up ~70% of the dataset; TV shows ~30%.

- **`Genre Highlights`:** International TV shows are top performers; Drama dominates movies.

- **`Top Content Origins`:** The U.S., India, and U.K. are leading producers.

- **`Seasonality`:** July, September, and December see the highest release activity.

- **`Peak Year`:** 2018 had the most movie releases—a benchmark year.

- **`Viewer Ratings`:** *TV-MA* is the most frequent rating, followed by *TV-14*, *TV-PG*, and *R*.

- **`Strategic Recommendations`:** Focus on international TV, drama movies, mature content, and release timing in July/September/December. Monitor trends to maintain engagement.

---
