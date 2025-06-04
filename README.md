# 📊 Netflix Data Analysis & Visualization

This project performs exploratory data analysis (EDA) on a Netflix dataset using Python, Pandas, and Seaborn. It focuses on data cleaning, feature extraction, and generating meaningful visual insights about Netflix's content library.

---

## 📁 Dataset

The dataset used is [`netflix_titles.csv`](https://www.kaggle.com/datasets/shivamb/netflix-shows), which contains information on over 8,800 Netflix titles including movies and TV shows.

---

## 🔧 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📌 Key Highlights

### 1. Data Cleaning
- Handled null values in critical fields such as `cast`, `country`, `director`, and `date_added`.
- Dropped incomplete records (e.g., missing `duration` or `release_year`).
- Converted `date_added` to proper datetime format.

### 2. Feature Engineering
- Extracted `duration_int` and `duration_unit` from the `duration` column.
- Extracted the year from `date_added` for time-based analysis.

### 3. Exploratory Data Analysis
- Counted and visualized content type distribution (Movies vs TV Shows).
- Identified top countries contributing to Netflix content.
- Explored most frequent genres using `listed_in` column.
- Tracked how many titles were added each year.

### 4. Data Visualization
- Bar plots, count plots, and line plots to illustrate key insights.
- Clear visual representation of top genres, countries, and temporal trends.

---

## 📷 Sample Visualizations

| Movies vs TV Shows | Top 10 Genres |
|--------------------|----------------|
|  | ![genre plot](#) |



---

## 🚀 How to Run

1. Clone this repo or download the `.ipynb` file.
2. Open in Google Colab or Jupyter Notebook.
3. Make sure the dataset `netflix_titles.csv` is available in the same directory.
4. Run all cells to reproduce the analysis and visualizations.

---

## 📌 Project Outcome

- Practiced real-world data cleaning and manipulation.
- Built visual storytelling using charts.
- Gained foundational EDA skills using Pandas and Seaborn.

---

## 📬 Contact

Made by **M.S.S Nithin**  
📧 mummidinithin9999@gmail.com  
🎓 B.Tech CSE (AI & ML), SRM KTR

---


