# 🎬 Netflix Movie Data Analysis

## 📌 Overview
Analyzed a dataset of 9800+ movies to help companies 
like Netflix make informed business decisions using 
data-driven insights.

## ❓ Business Questions Answered
1. What is the most frequent genre of movies?
2. Which genre has the highest votes?
3. Which movie has the highest popularity & what is its genre?
4. Which movie has the lowest popularity & what is its genre?
5. Which year had the most movies released?
6. Which genre has the highest average vote count?
7. Which genre has the highest average popularity score?

## 📊 Key Findings
- 🎭 **Drama** is the most frequent genre (14% of all movies)
- 🏆 **Spider-Man: No Way Home** has the highest popularity score
  with genres Action, Adventure & Science Fiction
- 📉 **The United States vs. Billie Holiday** has the lowest 
  popularity with genres Music, Drama & History
- 📅 **2020** had the highest number of movie releases
- ⭐ **Drama** genre dominates in fan votes
- 🔥 **Action** genre has the highest average popularity score

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data cleaning & manipulation |
| Numpy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical charts |
| Jupyter Notebook | Development environment |

## 📁 Project Structure
```
netflix-movie-analysis/
│
├── data/
│   └── mymoviedb.csv
├── Movie analysis.ipynb
└── README.md
```

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/Codewithkhushi-arch/netflix-movie-analysis.git
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

3. Open Jupyter Notebook
```bash
jupyter notebook
```

4. Run `netflix_movie_analysis.ipynb` top to bottom

## 📈 Visualizations Include
- Genre distribution bar chart
- Votes distribution chart
- Average vote count by genre
- Top 10 most popular movies bar chart
- Movies released per year histogram
- Average popularity by genre
- Correlation heatmap (Popularity vs Vote Count)

## 🧹 Data Cleaning Steps
- Converted Release_Date to year format
- Dropped irrelevant columns (Overview, Original_Language, Poster_Url)
- Categorized Vote_Average into 4 groups (not_popular, below_avg, average, popular)
- Split multi-genre rows and exploded into single genre per row
- Handled missing values and duplicates

## 📚 Dataset
TMDB Movie Dataset — 9800+ movies with information
on genre, popularity, vote count and release date.

## 👩‍💻 Author
**Khushi** — Aspiring Data Scientist
- GitHub: [@Codewithkhushi-arch](https://github.com/Codewithkhushi-arch)
