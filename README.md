# 📈Data_Analysis_PROJECTS:
**New Era** is a `comprehensive exploratory` data analysis project that investigates trends and patterns in the entertainment and other industry using `major datasets`: video game sales and Netflix content data. The project aims to provide actionable insights through `data cleaning, visualizations, and statistical analysis, uncovering sales trends, content popularity, and market dynamics`.

---

## PROJECT_1(Video Game Sales Analysis):

### Overview
This project analyzes and visualizes video game sales data from various regions including North America, Europe, Japan, and the rest of the world. The dataset contains information on top-selling video games, their release years, genres, publishers, and global sales figures. The goal of this analysis is to uncover trends, insights, and patterns in the video game market.

### Features
- `Data cleaning` and preprocessing of video game sales dataset
- `Exploratory data analysis (EDA)` to identify key trends and patterns
- `Visualization of sales` distribution across different `regions and genres`
- Insights into top publishers and best performing games by year
- Use of Python libraries such as `Pandas, NumPy, Matplotlib, and Seaborn` for analysis and visualization

### Technologies Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Dataset:
The dataset consists of 1035+ video games with the following columns:
- Game: Name of the video game
- Year: Release year
- Genre: Game genre (Action, Shooter, Sports, etc.)
- Publisher: Publishing company
- Sales in different regions: North America, Europe, Japan, Rest of World, Global (in millions)
 
---

- ## PROJECT_2(Netflix Visualizations, Recommendation & EDA):

Welcome to the **Netflix Data Analysis and Recommendation System** project!  
This project dives deep into a dataset of Netflix content using **Exploratory Data Analysis (EDA)**, **Data Visualization**, and builds a **Content-Based Recommendation System**. The notebook uncovers content trends, viewer preferences, and provides personalized recommendations.


### Overview:

In this project, we:

- Cleaned and transformed the raw `Netflix dataset`.
- Performed deep `exploratory data analysis` to uncover patterns and insights.
- Built `visualizations` to illustrate key findings.
- Developed a content-based movie and TV show recommender using `textual similarity`.

> The goal is to understand Netflix's content distribution and help users discover shows or movies similar to their preferences.


### 📊 Key Features:

#### ✅ 1. Data Cleaning & Transformation
- Handled missing values (`director`, `cast`, `country`, etc.)
- Extracted and normalized multi-valued columns such as `listed_in`, `cast`, `country`
- Converted `date_added` to datetime and derived new features (year, month)
- Cleaned up `duration` column to separate numerical values and units

#### 📈 2. Exploratory Data Analysis (EDA)
- Visualized type distribution `(Movies vs TV Shows)`
- Analyzed content trends by release year and addition year
- Identified top contributing `countries`, `directors`, and `actors`
- Analyzed genre frequency using bar plots and WordClouds

#### 🤖 3. Content-Based Recommendation System
- Combined features: `title`, `cast`, `listed_in`, and `description`
- Used **TF-IDF Vectorization** and **Cosine Similarity** to recommend similar titles
- Custom function to get top N recommendations for any selected show/movie


### Technologies Used:

| Tool / Library | Role                          |
|----------------|-------------------------------|
| `Python 3.x`   | Programming Language          |
| `Pandas`       | Data Manipulation             |
| `NumPy`        | Numerical Computation         |
| `Matplotlib`   | Data Visualization            |
| `Seaborn`      | Advanced Plotting             |
| `WordCloud`    | Genre & Cast Visuals          |
| `Scikit-learn` | TF-IDF & Cosine Similarity    |

---




