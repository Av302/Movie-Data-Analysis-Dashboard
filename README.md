# Movie-Data-Analysis-Dashboard


This project demonstrates a comprehensive analysis of movie data.
##
- **Data Manipulation:** Pandas for data cleaning, transformation, and analysis

- **Data Visualization:** Matplotlib and Seaborn for creating insightful plots and charts

- **Database Integration:** SQLAlchemy for connecting to and querying a PostgreSQL database

- **API Integration:** Requests library for fetching movie data from the OMDB API

- **Statistical Analysis:** Correlation analysis and descriptive statistics

- **Natural Language Processing (NLP):** Basic text analysis for movie titles

- **Version Control:** Git for code management and collaboration


## About the Project
This project analyzes movie data from 2021 to 2023, focusing on various aspects such as ratings, view counts, and title word frequencies. The analysis includes:

- Data collection from the OMDB API
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Statistical analysis of movie ratings and view counts
- Trend analysis across years
- Word frequency analysis of movie titles

### Key Visualizations
- Distribution of movie ratings
- Scatter plot of view count vs rating
- Top 10 most viewed movies
- Average rating trends by year
- Year-over-year comparison of average rating and view count
- Box plots of ratings and view counts across years
- Word frequency analysis in movie titles

<div id="notebook-dashboard"></div>

<script>
  fetch('movie_analysis_dashboard.html')
    .then(response => response.text())
    .then(data => {
      document.getElementById('notebook-dashboard').innerHTML = data;
    });
</script>

The project demonstrates the ability to handle real-world data, generate meaningful insights, and present findings through clear and informative visualizations.

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Atharvack/movie-data-analysis-dashboard.git
   ```

2. **Run the Jupyter notebooks to see the analysis and generate visualizations.**

Note: You'll need to:

Set up your own PostgreSQL database
Obtain an OMDB API key to fully replicate the data collection process

## Jupyter Notebooks

<div id="notebook-content"></div>

<script>
  fetch('main.html')
    .then(response => response.text())
    .then(data => {
      document.getElementById('notebook-content').innerHTML = data;
    });
</script>