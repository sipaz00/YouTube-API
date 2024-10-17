# Youtube API

## 🔗 Overview
This analysis explores YouTube content trends across six countries—United States, Spain, France, Italy, Norway, and Canada—based on data gathered over seven consecutive days from both the Trending and Home Feed sections of YouTube’s API. By studying this data, the aim is to understand patterns in viewership, video categories, and the relationship between video duration and popularity.
By combining this data into a unified dataset, the project aims to explore variations in trending content, popular video categories, and regional preferences across these diverse countries. The analysis provides insights into cross-country differences in video consumption.

## 📚 Libraries
- **Requests**: to access API.
- **Pandas**: for data manipulation and analysis.
- **NumPy**: for numerical computations and arrays handling.
- **Matplotlib**: for creating static, interactive and animated visualizations.
- **Seaborn**: for statistical and data visualization.
- **SciPy**: calculation of correlation coefficient.

## 🔍 Approach
📶 **Data Collection:** 
 - Data gathered daily from Home Feed and Trending pages of YouTube's API for each couontry.

🚮 **Data Cleaning:**
 - Combinig Files: daily .csv files were concatenated into a unified dataset.
 - Column Cleanup: droped irrelevant columns with no potential for analysis.
 - Handling NaNs and Duplicates
 - Data Harmonization: format standarization and categories creation

🔬 **Exploratory Data Analysis (EDA):**
 - Groupping
 - Comparative Analysis
