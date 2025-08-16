# 🎬 Netflix Data Analysis with Clustering

## 📌 Project Overview
This project analyzes a cleaned Netflix dataset and applies clustering techniques to group similar content.  
The analysis helps identify content patterns such as genres, release years, and content type distribution.  

## 📂 Dataset
**File:** `Netflix_cleaned_with_clusters.csv`  

The dataset includes the following key columns (after cleaning and clustering):
- `show_id` : Unique identifier for each title  
- `title` : Name of the show/movie  
- `type` : Content type (Movie/TV Show)  
- `director` : Director of the content  
- `cast` : Main actors  
- `country` : Country of origin  
- `date_added` : Date content was added to Netflix  
- `release_year` : Year of release  
- `rating` : Content rating (e.g., PG, TV-MA)  
- `duration` : Duration in minutes (for movies) or number of seasons (for TV shows)  
- `listed_in` : Genre categories  
- `cluster` : Cluster label assigned based on content similarity  

## ⚙️ Steps Performed
1. **Data Cleaning**
   - Removed duplicates and missing values  
   - Standardized column formats (date, rating, duration)  
   - Converted categorical values into usable formats  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of movies vs TV shows  
   - Country-wise content availability  
   - Genre popularity  
   - Trends over release years  

3. **Clustering**
   - Applied clustering algorithm (e.g., K-Means)  
   - Grouped content into meaningful segments  
   - Visualized cluster patterns  

## 📊 Key Insights
- **Movies dominate** Netflix’s catalog compared to TV shows.  
- **United States and India** contribute the highest number of titles.  
- The **2015–2020 period** saw the largest spike in content additions.  
- Clusters revealed **genre-based groupings**, such as family shows, crime thrillers, and international dramas.  

## 🚀 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter Notebook / Google Colab  

## 📌 How to Use
1. Clone the repository or download the dataset  
2. Open the Jupyter Notebook or Colab file  
3. Run the analysis scripts step by step  
4. Explore the visualizations and insights  

## 📝 Author
**Tejas Singh**  
(Feel free to connect on LinkedIn/GitHub)  
