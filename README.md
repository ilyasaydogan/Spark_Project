# Project Overview

The entire project is implemented using PySpark. The project follows these steps:

1. **Data Collection and Processing:**
   - Data from three different sources is transformed into DataFrame format using PySpark functions such as `map`, `flatMap`, `reduceByKey`, `union`, `groupBy`, and `aggregate`.

2. **Data Merging:**
   - The transformed DataFrames are merged into a single dataset.

3. **Feature Engineering:**
   - Feature engineering is performed on the consolidated dataset to optimize and prepare it for modeling.

4. **Modeling:**
   - **Linear Regression** and **Random Forest** models are used for forecasting. These models analyze the dataset to extract meaningful insights and predict sales.

## Technologies Used

- **PySpark:** Used for data processing, merging, and feature engineering.
- **Machine Learning Models:** Linear Regression and Random Forest are employed for forecasting and analysis.
