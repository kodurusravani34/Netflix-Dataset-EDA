# Netflix Movies & TV Shows — Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies & TV Shows dataset to understand content distribution, growth trends, genres, countries, and audience ratings.  
The analysis was done using Python, Pandas, Matplotlib, and Seaborn in Jupyter Notebook.

---

## Dataset Description
Key columns used in this analysis:

- type — Movie or TV Show  
- title — Title name  
- director — Director name  
- cast — Lead actors  
- country — Country of origin  
- date_added — Date added on Netflix  
- release_year — Year of original release  
- rating — Audience maturity rating  
- duration — Runtime or number of seasons  
- listed_in — Genres  
- description — Short summary  

---

## Data Cleaning Performed
- Removed duplicate rows
- Replaced missing values in director, cast, rating, country with "Unknown"
- Converted date_added to datetime format
- Extracted year_added from date_added
- Converted duration into numeric values for analysis

---

## Exploratory Data Analysis Performed

### 1. Movies vs TV Shows
Count comparison between Movies and TV Shows  
Insight: Netflix contains more Movies than TV Shows.

---

### 2. Titles Added Per Year
Bar chart showing number of titles added yearly  
Insight: Content volume increased significantly after 2015.

---

### 3. Country-wise Content Contribution
Extracted and counted top 10 contributing countries  
Insight: United States and India are the largest content contributors.

---

### 4. Genre Distribution
Expanded and counted top 10 genres  
Insight: Drama and International Movies are the most common categories.

---

### 5. Rating Distribution
Count of maturity ratings  
Insight: Majority of titles are TV-14 and TV-MA, indicating teen/adult audience focus.

---

### 6. Movie Duration Analysis
Converted runtime to numeric format  
Insight: Most movies are between 90–120 minutes.

---

### 7. TV Show Seasons Analysis
Converted seasons to numeric  
Insight: Most TV shows have 1–2 seasons.

---

## Key Findings
- Netflix catalog is dominated by Movies.
- Content additions increased rapidly after 2015.
- USA and India contribute the highest number of titles.
- Drama is the most frequent genre.
- Most content targets teen and adult viewers.
- TV shows are often limited to 1–2 seasons.
- Most movies fall in the 90–120 minute range.

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
