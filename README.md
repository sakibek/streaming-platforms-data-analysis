
---

# Netflix Recommender System

## Description
This project develops a recommender system for Netflix content by leveraging audience and critic scores from IMDb, Rotten Tomatoes, and Metacritic. The analysis identifies key trends in genres, languages, and ratings, applying clustering techniques to create personalized recommendations. The project provides actionable insights for improving content engagement and user satisfaction.

## Technical Details
- **Data Characteristics**:
  - Dataset contains information on 9,425 titles, including IMDb scores, Rotten Tomatoes ratings, and Metacritic reviews.
  - Additional features include genres, languages, and runtime, allowing for multi-dimensional analysis.
  - Data cleaning included handling missing values, outlier detection, and feature engineering.

- **Models and Techniques Used**:
  1. **Feature Engineering**:
     - Computed weighted IMDb scores for each title based on audience and critic reviews.
     - Encoded categorical variables (e.g., genres, languages) for analysis.
  2. **Clustering with K-Means**:
     - Grouped content into clusters based on numerical features, identifying patterns in audience preferences.
  3. **Exploratory Data Analysis (EDA)**:
     - Visualized trends in ratings, genres, and runtime distributions.

- **Tools and Libraries**:
  - Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, and `seaborn`.

## Results
- **Performance**:
  - Identified distinct clusters of content based on audience and critic preferences.
  - Enhanced recommendation accuracy by combining clustering insights with weighted IMDb scores.
- **Insights**:
  - Popular genres such as Drama and Action had higher audience ratings.
  - Titles with balanced critic and audience ratings showed higher retention rates.

## Use Cases
1. **Content Recommendations**:
   - Use clustering insights to recommend content tailored to user preferences.
2. **Genre and Audience Analysis**:
   - Identify underperforming genres and target specific demographics.
3. **Data-Driven Decision Making**:
   - Enhance marketing strategies based on audience preferences and engagement data.

## Files
- **Netflix_Data.csv**: Dataset containing movie and series details with ratings and reviews.
- **Recommender_Models.ipynb**: Jupyter Notebook implementing clustering and recommendation algorithms.
- **EDA_Report.pdf**: Presentation summarizing findings and recommendations.

## Data Source
The dataset is publicly available on Kaggle: [Netflix Dataset](https://www.kaggle.com/datasets/ashishgup/netflix-rotten-tomatoes-metacritic-imdb?resource=download).

## Contact
For further details or collaboration, connect with me on [LinkedIn](https://www.linkedin.com/in/sakibek).

---
