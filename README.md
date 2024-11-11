# Insights-Unlocked-Understanding-Social-Media-Post-Popularity
This repository contains a project focused on implementing the key stages of the data science methodology, with a primary emphasis on understanding and processing data to derive insights. Below is an overview of the **data-related steps** implemented in the project.

---

## Data Collection

### Source of Data
- The dataset used for this project was sourced from **Kaggle** and includes comprehensive metrics on social media engagement.
- Key metrics include:
  - **Likes**
  - **Comments**
  - **Shares**
  - **Impressions**
  - **Reach**
  - **Audience demographics**

### Justification
- This dataset was chosen for its richness in features relevant to the study of post popularity on social media platforms.
- It enables analysis of demographic trends, engagement patterns, and the impact of post types across diverse social media platforms.

---

## Data Cleaning

### Steps Performed
1. **Handling Missing Values**
   - Missing values in the `Sentiment` column were imputed using the **KNN imputer**.
   
2. **Removing Duplicates**
   - Duplicated entries were identified and removed to ensure data integrity.

3. **Correcting Data Types**
   - Data inconsistencies were resolved, and columns were cast to appropriate data types.

4. **Creating a Popularity Score**
   - A normalized `Popularity Score` was calculated using the metrics: `Likes`, `Comments`, and `Shares`.
   - These original columns were subsequently dropped to streamline the dataset.

5. **Encoding Categorical Variables**
   - Variables such as `Platform`, `Post Type`, and `Audience Gender` were encoded into dummy variables for analysis.

6. **Standardizing Data**
   - Features such as `Post Timestamp`, `Popularity Score`, `Audience Age`, and `Reach` were normalized to ensure comparability.

7. **Mapping Sentiment**
   - Sentiment analysis results were transformed into numerical values for integration with other features.

---

## Dataset Overview

### Before Cleaning
- The initial dataset contained:
  - Missing values.
  - Duplicate entries.
  - Inconsistent data types.

### After Cleaning
- The dataset was cleaned and preprocessed, resulting in:
  - Consistent and normalized data.
  - Simplified columns for analysis.
  - Enhanced readiness for exploratory and predictive tasks.

---

## Summary

This structured data cleaning process ensured the dataset's suitability for robust analysis and modeling. By addressing inconsistencies and standardizing features, the project lays a strong foundation for subsequent stages of the data science methodology.

Feel free to explore the dataset and insights derived in this project for your own analyses or further research!

---

## License

This project is for academic purposes. Please contact the authors for permission if you wish to use or reproduce parts of this work.

---

## Acknowledgments

Special thanks to the course instructors and Kaggle for providing the data and guidance for this project.
