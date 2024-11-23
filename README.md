# Income Prediction Using K-Nearest Neighbors Algorithm
This project aims to predict whether an individual earns above or below a specific income threshold using demographic, educational, and work-related features. The K-Nearest Neighbors (KNN) algorithm was employed to classify income groups based on their proximity to similar instances in the feature space.

# Dataset Features:
* age: The individual's age.
* JobType: The type of employment or job (e.g., government, private).
* EdType: The level of education attained (e.g., high school, bachelor’s degree).
* maritalstatus: The marital status of the individual (e.g., married, single).
* occupation: The specific occupation or job role.
* relationship: Family or household relationship status (e.g., spouse, child).
* race: Ethnicity of the individual.
* gender: Gender of the individual (e.g., male, female).
* capitalgain: Income derived from capital gains.
* capitalloss: Loss of income from capital-related activities.
* hoursperweek: The number of hours worked per week.
* nativecountry: The individual’s native country.
* SalStat: The income classification (e.g., ≤50K, >50K).
# Objective:
To classify individuals into income categories (≤50K or >50K) using the KNN algorithm and analyze the impact of various demographic and work-related features on income levels.

Steps:
# Data Preprocessing:

Handled missing values and cleaned categorical features (JobType, nativecountry).
Normalized numerical features like age, hoursperweek, and capitalgain to ensure all features contributed equally to the distance metric.
# Feature Engineering:

Encoded categorical variables such as JobType, occupation, and gender using one-hot encoding.
Combined capitalgain and capitalloss into a single feature for better representation.
# Model Training with KNN:

Implemented the K-Nearest Neighbors algorithm with a range of k-values.
Used distance metrics such as Euclidean and Manhattan distances to identify the best fit.
Split the dataset into training and testing sets, ensuring a balanced distribution of income categories.
# Hyperparameter Tuning:

Optimized the number of neighbors (k) using grid search and cross-validation.
Assessed performance with varying distance metrics.

# Evaluation:

Measured model performance using accuracy.
Plotted a confusion matrix and ROC curve to evaluate classification effectiveness.
