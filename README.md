# Netflix Data Analytics Project

## Project Overview
This project focuses on analyzing a Netflix dataset to extract meaningful insights about content distribution, trends, and viewing patterns. The analysis was performed using Python in Google Colab.

The objective of this project is to understand how Netflix content is distributed across categories such as type, country, genre, and release year, and to identify key trends over time.

---

## Objectives
- Perform data cleaning and preprocessing
- Analyze content distribution (Movies vs TV Shows)
- Identify top countries producing Netflix content
- Study trends in content release and addition over time
- Discover popular genres and ratings
- Generate insights using data visualization

---

## Dataset
- Source: Kaggle (Netflix Dataset)
- Format: CSV file
- Contains the following attributes:
  - Title
  - Type (Movie/TV Show)
  - Country
  - Release Year
  - Rating
  - Duration
  - Genre (listed_in)
  - Date Added

---

## Tools and Technologies Used
- Python
- Pandas (data manipulation and analysis)
- Matplotlib (data visualization)
- Seaborn (statistical visualization)
- Google Colab (development environment)

---

## Data Preprocessing
- Handled missing values by filling them with 'Unknown'
- Converted `date_added` into datetime format
- Extracted `year_added` from the `date_added` column
- Cleaned and structured the dataset
- Selected relevant columns for analysis

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

### 1. Content Type Distribution
Comparison of Movies and TV Shows available on Netflix.

### 2. Country-wise Analysis
Identification of top countries producing Netflix content.

### 3. Year-wise Trend Analysis
Study of content growth over the years.

### 4. Genre Analysis
Identification of the most popular genres.

### 5. Rating Distribution
Analysis of content ratings such as TV-MA, PG, etc.

---

## Key Insights
- Netflix has more Movies than TV Shows
- The United States produces the majority of content
- Content production increased significantly after 2015
- Drama and International genres are the most common
- Most content is rated TV-MA

---

## Project Structure
