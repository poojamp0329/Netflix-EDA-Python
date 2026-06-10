## README.md

### Project Overview

This project performs an advanced Exploratory Data Analysis on the Netflix Movies and TV Shows dataset from Kaggle. It explores catalog composition, time trends, countries, genres, ratings, durations, directors, cast members, engineered business features, and strategic recommendations.

### Tools Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

### Dataset Information

Dataset file: `netflix_titles.csv`

Columns include `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, and `description`.

### Key Findings

The notebook generates data-driven findings after the dataset is loaded and cleaned, including catalog size, dominant content type, top countries, top genres, rating patterns, duration trends, content growth over time, maturity segments, metadata quality, and genre-country opportunities.

### Advanced Analysis Included

- Feature engineering for content age, release era, maturity segment, international titles, genre count, cast count, director count, and metadata coverage.
- Statistical observations including median, IQR, outlier thresholds, and content-age distributions.
- Trend analysis for annual additions, year-over-year growth, content mix, and average content age.
- Portfolio segmentation by maturity segment, release era, quarter added, country, genre, and content type.
- Executive summary and business recommendations for catalog strategy, acquisition, localization, and metadata quality.

### Project Structure

```text
.
|-- Netflix_EDA.ipynb
|-- README.md
|-- requirements.txt
|-- data/
|   `-- netflix_titles.csv
`-- images/
    |-- movie_vs_tvshow.png
    |-- top_genres.png
    |-- top_countries.png
    |-- content_growth.png
    `-- ratings_distribution.png
```

