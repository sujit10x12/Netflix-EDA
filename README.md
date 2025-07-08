# 📊 Netflix Movies and TV Shows Data Analysis using Python
![netflix](https://github.com/user-attachments/assets/0adde899-a024-467f-b899-c4fdcc8dc247)

---

## 👀 What’s This Project About?

This project explores and visualizes the **Netflix Movies and TV Shows dataset**, originally sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows). The goal is to uncover patterns in Netflix's content library over time, including trends by genre, country, type, and more. The project also demonstrates data cleaning, EDA, and visualization techniques using Python.

> ✅ **You can access the complete notebook here:** [🔗 View Jupyter Notebook](notebooks/netflix_eda.ipynb)

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

   ![image](https://github.com/user-attachments/assets/599945b0-3af3-4889-88af-30d18958dfa7)
   
### 2. How has the distribution of content (movies and TV shows) changed over time? For example, how many movies and TV shows were released in each year?
   ![image](https://github.com/user-attachments/assets/0dc1fe2a-bb1d-4182-a026-8a22d0f220f6)

### 3. What are the Number of Content Items in Each Genre?
   ![image](https://github.com/user-attachments/assets/7425e4ec-6531-431b-a9a1-78e6784099ae)

### 4. Which country produces the most movies and TV shows on Netflix?  
   ![image](https://github.com/user-attachments/assets/1a419a89-aa1c-4726-9900-c5f786b0ed4f)
   
### 5. What are the most popular ratings on Netflix?  
   ![image](https://github.com/user-attachments/assets/703ae01a-1fb7-42b1-a06e-501141c9bcff)

### 6. Which Months have the Most Content Releases?  
   ![image](https://github.com/user-attachments/assets/20340a24-da22-490d-9913-5e0f62ebd05d)

### 7. Which Days have the Most Content Releases?  
   ![image](https://github.com/user-attachments/assets/f965c4d0-5618-4a48-8efc-0944c14b86bb)

   
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
