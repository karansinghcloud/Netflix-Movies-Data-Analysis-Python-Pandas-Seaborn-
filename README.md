This project analyzes a dataset of Netflix movies to understand trends in genres, ratings, popularity, and yearly releases.
The dataset was cleaned, transformed, and visualized using Python.

📌 1. Project Overview

This project performs exploratory data analysis (EDA) on a Netflix movies dataset.
The goal is to identify trends in:

Movie genres

Audience ratings

Popularity

Release year patterns

Top & bottom performing movies

📌 2. Problem Statement

Netflix has thousands of movie titles.
To improve recommendation systems and content planning, it is important to know:

Which genres are most common?

Which movies are the most popular?

Which year produced the highest number of movies?

How are movie ratings distributed?

What trends exist in popularity and votes?

This project answers all of these through data cleaning and analysis.

📌 3. Dataset Information
Column	Description
Release_Date	Year of movie release
Title	Movie name
Popularity	Popularity score
Vote_Count	Total votes
Vote_Average	Audience rating
Original_Language	Language code
Genre	Movie genres (comma separated)
Poster_Url	Poster image link

Dataset Name: mymoviedb.csv

Source: Provided dataset

License: Educational Use

📌 4. Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📌 5. Installation
git clone https://github.com/<your-username>/Netflix-Movies-Analysis.git
cd Netflix-Movies-Analysis
pip install -r requirements.txt

📌 6. How to Run
▶ Run Jupyter Notebook
jupyter notebook notebooks/netflix_movies_analysis.ipynb

▶ OR Run Python Scripts
python src/data_cleaning.py
python src/eda.py

📌 7. Data Cleaning Summary

The dataset was cleaned using the following steps:

✔ Converted release date into year
✔ Removed unnecessary columns
✔ Categorized ratings into groups:

popular

average

below_avg

not_popular
✔ Split genre column and exploded it
✔ Converted genre to categorical type
✔ Removed rows containing missing values
✔ Final cleaned dataset = 25,552 rows

📌 8. Key Insights (EDA Results)
⭐ Most Common Genre

Drama — most frequently appearing genre.

⭐ Highest Popularity Movie

Spider-Man: No Way Home (Action, Adventure, Sci-Fi)

⭐ Lowest Popularity Movie

The United States vs. Billie Holiday

⭐ Year with Most Releases

2020 — highest number of movies released.

⭐ Rating Category Distribution

Most movies fall under popular rating category.

📌 9. Visualizations

The following charts were created:

Genre distribution

Rating category distribution

Top popular movies

Lowest popular movies

Yearly release trends

Popularity vs vote count

Popularity outliers

All charts are saved under:

outputs/charts/

📌 10. Project Structure
Netflix-Movies-Analysis/
│
├── data/
│   └── mymoviedb.csv
├── notebooks/
│   └── netflix_movies_analysis.ipynb
├── src/
│   ├── data_cleaning.py
│   ├── eda.py
│   └── visualize.py
├── outputs/
│   └── charts/
├── requirements.txt
├── .gitignore
└── README.md

📌 11. Contact

Author: Karan Singh
Email: urwillrana345@gmail.com

GitHub: https://github.com/
<your-username>
