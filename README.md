# California-Housing-Prices

Description:
The provided Python code is a data analysis and machine learning project focused on housing data. The code reads housing data from a CSV file, performs data preprocessing, exploratory data analysis (EDA), feature engineering, and trains machine learning models. Here is a summary of the key components and functionalities of the code:

Imports: The code imports essential libraries, including Pandas for data manipulation, NumPy for numerical operations, Matplotlib for data visualization, Seaborn for enhanced visualization, and scikit-learn for machine learning.

Data Loading and Cleaning: The code reads housing data from a CSV file, and it handles missing values by dropping rows with missing data.

Data Splitting: It splits the data into features (independent variables) and the target variable, and further divides it into training and testing datasets using train-test splitting.

Exploratory Data Analysis (EDA): The code generates histograms and correlation heatmaps to explore the distribution of data and relationships between variables. Logarithmic transformations are applied to specific features.

Categorical Data Handling: It converts categorical data using one-hot encoding, creating binary columns for different categories.

Feature Engineering: The code creates new features, such as "bedroom_ratio" and "household_rooms."

Data Scaling: The features are standardized using StandardScaler to prepare them for machine learning models.

Model Training: Linear regression and random forest regression models are trained using the training data.

Model Evaluation: The code evaluates the models on the testing dataset, providing the R-squared score (coefficient of determination) for model performance.

Hyperparameter Tuning: A grid search is performed to find the best hyperparameters for the random forest regression model.

Best Model Evaluation: The best-performing random forest regression model is evaluated on the testing data.
