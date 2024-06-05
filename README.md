## Box Office Revenue Prediction
This project aims to predict the box office revenue of movies using machine learning techniques.
The main focus is on utilizing the Random Forest algorithm to build a predictive model based on various features extracted from movie data.

This 'README' serves as an overall summary of the project and findings. 

## Goals of the Project
  1. ### Exploratory Data Analysis (EDA):
     - Understand the structure and relationships within the data.
     - Visualize key variables to identify trends and patterns.
      
  2. ### Feature Engineering:
     - Create new features from existing data to improve model performance.
     - Extract meaningful information such as main genre, production company, release dates, and more.
    
  3. ### Data Cleaning and Preparation:

Handle missing values through imputation and transformation.
Log-transform skewed variables to normalize distributions.
Machine Learning:

Implement the Random Forest algorithm to predict box office revenue.
Evaluate model performance using metrics like Mean Squared Error (MSE) and R-squared.
Prediction:

Use the trained model to predict revenues on a test dataset.
Save and document the predictions for further analysis.
Methodology
Data Collection:

Combine training and test datasets for consistent preprocessing.
Use various R packages for data manipulation and visualization.
Feature Engineering:

Extract and create features such as collection status, main genre, production company details, language, release dates, tagline presence, homepage presence, and cast & crew gender.
Generate new variables indicating the number of genres, production companies, production countries, spoken languages, and keywords.
Handling Missing Values:

Visualize missing data and apply suitable imputation techniques.
Use mean, mode, and predictive modeling to fill in gaps.
Model Training:

Split data into training and testing sets.
Train a Random Forest model with specified parameters.
Evaluate variable importance to understand feature contributions.
Prediction and Output:

Predict box office revenue for the test set.
Reverse log transformations and save the predictions to a CSV file.
Results
The Random Forest model showed that features like popularity, budget, production company, and genre significantly impact box office revenue. The final model provided a robust framework for predicting movie revenues, with a clear process for handling data preprocessing, feature engineering, and model evaluation.

Tools and Libraries Used
R
Tidyverse
Plotly
ggthemes
Viridis
Corrplot
GridExtra
VIM
Lubridate
RandomForest
Conclusion
This project demonstrates a comprehensive approach to predicting box office revenue using machine learning in R. By carefully analyzing and engineering features, handling missing data, and utilizing a powerful algorithm like Random Forest, we achieved a meaningful and interpretable model.

For more details, please refer to the full documentation and code in this repository.
