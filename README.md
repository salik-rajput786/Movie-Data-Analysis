# 🎬 Movie Data Analysis

## 📌 Introduction
This project focuses on analyzing a dataset of movies with attributes such as release date, genre, popularity, vote counts, and ratings.  
The aim of this analysis is to clean, transform, and visualize the data to uncover meaningful trends in the movie industry.  

## 📂 Dataset
- **Source**: Movie dataset with **9,827 records** and **9 columns**.  
- **Key Columns**:
  - `Title` – Movie title  
  - `Release_Date` – Release date of the movie  
  - `Genre` – Movie genres (one or multiple)  
  - `Popularity` – Popularity score  
  - `Vote_Count` – Number of votes received  
  - `Vote_Average` – Average rating  
  - `Original_Language` – Language of the movie  

### Data Cleaning Steps
- Converted `Release_Date` into **year values**.  
- Dropped less useful columns like *Overview* and *Poster URL*.  
- Categorized `Vote_Average` into 4 groups: **Popular, Average, Below Average, Not Popular**.  
- Split multi-genre entries into single-genre rows.  
- Handled outliers in the **Popularity** column.  

## 🔍 Analysis
The analysis was carried out to answer key questions such as:
1. **Most frequent movie genre**  
2. **Highest rated movies (by vote average)**  
3. **Most and least popular movies**  
4. **Trend of movie releases over the years**  
5. **Distribution of ratings and popularity**  

## 📊 Visualizations
Some of the main charts created:
- **Genre Frequency Chart** → Shows that *Drama* is the most common genre (~14% of all movies).  
- **Vote Average Distribution** → Most movies fall under *Average* or *Popular* categories.  
- **Popularity Bar Charts** → Highlighted *Spider-Man: No Way Home* as the most popular movie.  
- **Yearly Release Trend** → Showed a steady increase in movie releases over time.  
- **Top-rated and Least-rated Movies** → Identified standout titles.  

## ✅ Results & Insights
- **Drama** is the most frequent genre, followed by *Comedy* and *Thriller*.  
- **Kung Fu Master Huo Yuanjia** scored a perfect **10/10 rating**, while most movies cluster in *Average* and *Popular*.  
- **Spider-Man: No Way Home** emerged as the most popular movie, while *Threads* and *The United States vs. Billie Holiday* ranked lowest.  
- Movies with high popularity also tend to have high **vote counts**, showing strong audience engagement.  
- The trend of releases shows a **steady growth**, reflecting the impact of streaming platforms and global distribution.  

## 🚀 Conclusion
This project highlights how data analysis can uncover trends in the film industry, from genre preferences to audience engagement. The insights can be useful for understanding **audience behavior, industry trends, and content strategy** in entertainment.  
