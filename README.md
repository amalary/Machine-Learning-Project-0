
# Predicting Olympic Medals Using Linear Regression

This project explores how machine learning can be applied to predict the number of medals a country might win in the Olympics. By leveraging historical Olympic data and using features such as the number of athletes, average age, and previous medal counts, the goal is to develop insights and create predictive models.

## Overview
The hypothesis is: **"We can predict how many medals a country can win in the Olympics."** This project utilizes a dataset with country-specific Olympic metrics and applies linear regression techniques to analyze and predict medal outcomes.

## Dataset
The dataset (`teams.csv`) contains information such as:
- `team`: Team abbreviation
- `country`: Country name
- `year`: Olympic year
- `athletes`: Number of athletes representing the country
- `age`: Average age of athletes
- `prev_medals`: Medals won in the previous Olympics
- `medals`: Medals won in the current Olympics

## Steps
1. **Data Cleaning and Preprocessing**: Columns such as `athletes`, `age`, and `prev_medals` were selected for analysis, focusing on numerical attributes.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between features and medal counts using scatter plots and histograms.
   - Examined distributions and outliers to identify significant predictors.
3. **Correlation Analysis**:
   - Found strong correlations between the number of athletes and medal count, as well as between previous medals and current medals.
4. **Modeling**:
   - Applied linear regression to assess how the features predict medal outcomes.
   - Evaluated prediction errors and model accuracy.

## Tools and Libraries
- Python
- Pandas for data manipulation
- Seaborn and Matplotlib for visualization
- Scikit-learn for regression modeling

## Results
The analysis highlighted:
- A strong positive relationship between the number of athletes and medal count.
- Historical performance (previous medals) is a significant predictor of current medals.

## How to Run
1. Clone the repository or download the notebook file.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Load the dataset (`teams.csv`) into the same directory as the notebook.
4. Run the Jupyter notebook to explore the analysis and model predictions.
