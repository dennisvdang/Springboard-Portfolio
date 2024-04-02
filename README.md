# Springboard Data Science Portfolio

| **Table of Contents** |
| --- |
| **Case Studies** |
| &nbsp;&nbsp;&nbsp;&nbsp;[Clustering (Customer Segmentation Case Study)](#clustering-customer-segmentation-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[App Store Case Study](#app-store-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Cosine Similarity](#cosine-similarity) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Decision Tree (Coffee Case Study)](#decision-tree-coffee-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Euclidean and Manhattan Distance](#euclidean-and-manhattan-distance) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Frequentist Inference](#frequentist-inference) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Gradient Boosting](#gradient-boosting) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Logistic Regression (Wine Quality Case Study)](#logistic-regression-wine-quality-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Linear Regression (Heart Disease Case Study)](#linear-regression-heart-disease-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[London Housing Case Study](#london-housing-case-study) |
| &nbsp;&nbsp;&nbsp;&nbsp;[Random Forest (Covid Case Study)](#random-forest-covid-case-study) |
| **Mini Projects** |
| &nbsp;&nbsp;&nbsp;&nbsp;[API Mini Project](#api-mini-project) |
| &nbsp;&nbsp;&nbsp;&nbsp;[SQL Mini Project](#sql-mini-project) |

## Case Studies

### Clustering (Customer Segmentation Case Study)

- **Objective:** Segment customers based on their purchasing behavior and response to marketing campaign offers, and provide insights into the characteristics of each customer segment to enable targeted marketing strategies.
- **Methodology:** 

- Cleaned and transformed data to create a matrix of customer responses to different offers.

- Determined the optimal number of clusters using the Elbow, Silhouette, and Gap statistic methods.
- Visualized the customer segments using Principal Component Analysis (PCA).
- Analyzed the distribution of key features across the identified clusters and revealed the characteristics of each customer segment.
- Libraries: `Pandas`, `Scikit-learn`, `Matplotlib`, `Seaborn`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Clustering%20(Wine%20Customers%20Case%20Study)/Clustering%20Case%20Study%20-%20Customer%20Segmentation%20with%20K-Means%20-%20Tier%203.ipynb)

### App Store Case Study
- Investigated if Apple Store apps received better reviews than Google Play apps.
- Followed the Data Science Pipeline: Sourcing, Cleaning, Modeling, Evaluating.
- Conducted a Permutation test for hypothesis testing.
- Concluded that platform impacts ratings, recommending Google Play.
- Libraries: `NumPy`, `Matplotlib`, `SciPy`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/App%20Store%20Case%20Study/Springboard%20Apps%20project%20-%20Tier%203%20-%20Complete.ipynb)

### Cosine Similarity
- Used cosine similarity to compare numeric data and text datasets.
- Calculated similarity measures for sentences/paragraphs.
- Libraries: `NumPy`, `Pandas`, `Matplotlib`, `Scipy`, `Scikit-learn`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Cosine%20Similarity/Cosine_Similarity_Case_Study.ipynb)

### Decision Tree (Coffee Case Study)
- Explored decision tree modeling to predict customer purchases of a new specialty coffee product.
- Analyzed decision paths and feature importance to understand key drivers of customer purchasing behavior.
- Evaluated model performance using accuracy, balanced accuracy, precision, and recall metrics.
- Compared the performance of a single decision tree model to a Random Forest ensemble model.
- Concluded that the single decision tree provided better predictive performance than the more complex Random Forest model, highlighting the importance of tailoring the model to the specific dataset.
- Libraries: `Pandas`, `Scikit-learn`, `Matplotlib`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Decision%20Tree%20(Coffee%20Case%20Study)/Springboard%20Decision%20Tree%20Specialty%20Coffee%20Case%20Study%20-%20Tier%203.ipynb)

### Euclidean and Manhattan Distance
- Demonstrated the calculation and comparison of Euclidean and Manhattan distances.
- Visualized the distribution of distances through histograms.
- Highlighted the application of these distance measures in data science, foundational for algorithms like PCA.
- Libraries: `Pandas`, `NumPy`, `Matplotlib`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Euclidean%20and%20Manhattan%20Distance/Euclidean_and_Manhattan_Distances_Case_Study.ipynb)

### Frequentist Inference
- Applied Frequentist inference to real-world data, addressing practical business questions for a hospital, emphasizing statistical concepts like z-statistic, t-statistic, Central Limit Theorem, and confidence intervals.
- Explored the Central Limit Theorem and its implications.
- Estimated population mean and standard deviation from a sample.
- Calculated confidence intervals.
- Libraries: `Pandas`, `NumPy`, `Matplotlib`
- [Link to Case Study (Part 1)](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Frequentist%20Inference/Frequentist%20Inference%20Case%20Study%20-%20Part%20A%20(3).ipynb)
- [Link to Case Study (Part 2)](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Frequentist%20Inference/Frequentist%20Inference%20Case%20Study%20-%20Part%20B%20(2).ipynb)

### Gradient Boosting
- Explored the concept of gradient boosting using decision trees as base predictors.
- Demonstrated the process of fitting a series of decision trees on residual errors.
- Evaluated model performance with multiple learning rates and calculated the ROC curve.
- Libraries: `Pandas`, `Scikit-learn`, `Matplotlib`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Gradient%20Boosting/Gradient%20Boosting%20Case%20Study.ipynb)

### Linear Regression (Wine Quality Case Study)
- Conducted a comprehensive regression analysis to predict alcohol levels in wine.
- Performed both univariate and multivariate analysis to iterate towards an accurate model.
- Utilized exploratory data analysis (EDA) to visualize correlations and inform model selection.
- Developed multiple linear regression models, iterating to improve accuracy and reduce redundancy.
- Evaluated models based on R-squared, AIC, and BIC metrics.
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Statsmodels`, `Scikit-learn`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Linear%20Regression%20(Wine%20Quality%20Case%20Study)/Springboard%20Regression%20Case%20Study%20-%20the%20Red%20Wine%20Dataset%20-%20Tier%203.ipynb)

### Logistic Regression (Heart Disease Case Study)
- Introduced Logistic Regression as a fundamental algorithm for classification problems.
- Demonstrated the process of building a logistic regression model to predict the presence of heart disease using patient health data.
- Covered key concepts including classification, model evaluation, and the distinction between discriminative and generative classifiers.
- Utilized libraries such as scikit-learn for model building and matplotlib for data visualization.
- Explored model tuning and evaluation using accuracy, precision, recall, and ROC curves to assess model performance.
- Libraries: `Pandas`, `Scikit-learn`, `Matplotlib`, `NumPy`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Logistic%20Regression%20(Heart%20Disease%20Case%20Study)/Logistic%20Regression%20Advanced%20Case%20Study.ipynb)

### London Housing Case Study
- Investigated trends in London's housing market.
- Analyzed price movements and factors influencing housing prices.
- Utilized time series analysis for forecasting future prices.
- Conducted exploratory data analysis (EDA) to understand the impact of the 2008 financial crisis on London's housing market.
- Applied statistical tests to explore the relationship between pre-crisis prices and crisis recovery time.
- Employed Random Forest predictions to forecast 2024 property values based on borough, season, and other features.
- Demonstrated the use of polynomial fitting and ordinary least squares regression to model the relationship between housing prices and recovery times post-crisis.
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scipy`, `Statsmodels`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/London%20Housing%20Case%20Study/Unit%204%20Challenge%20-%20Tier%203.ipynb)

### Random Forest (Covid Case Study)
- Applied Random Forest algorithm to predict COVID-19 infection rates.
- Feature importance analysis to identify key predictors of infection rates.
- Evaluated model performance with cross-validation.
- Demonstrated Random Forest's ability to handle highly correlated features and its efficiency in feature importance investigation.
- Highlighted Random Forest as a preferred choice for decision trees, especially in multiclass classifications.
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`
- [Link to Case Study](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Case%20Studies/Random%20Forest%20(Covid%20Case%20Study)/RandomForest_casestudy_covid19.ipynb)

## Projects

### API Mini Project
- Developed a Python application to interact with a public API.
- Implemented data retrieval, processing, and visualization functionalities.
- Focused on equities data from the Frankfurt Stock Exchange (FSE), specifically analyzing the stock prices of Carl Zeiss Meditec (ticker AFX_X) for the year 2017.
- Utilized the `requests` package for API calls and handled data in native Python data structures, with an emphasis on dictionaries.
- Calculated various statistics from the stock data, including the highest and lowest opening prices, the largest change in one day, the largest change between any two days, average daily trading volume, and median trading volume for 2017.
- Libraries: `os`, `dotenv`, `requests`, `pandas`, `json`
- [Link to Project](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Projects/API%20Mini%20Project/api_data_wrangling_mini_project.ipynb)

### SQL Mini Project
- Performed data extraction and manipulation using SQL queries.
- Analyzed data from a relational database to answer business questions.
- Tasks included identifying facilities with total revenue less than 1000, producing a report of members and their recommenders, finding facilities with their usage by members (excluding guests), and analyzing facility usage by month.
- Utilized SQLite for database management and pandas for data manipulation and presentation.
- Tools: `SQL`, `SQLite`, `Pandas`
- [Link to Project](https://github.com/dennisvdang/Springboard-Portfolio/blob/main/Projects/SQL%20Mini%20Project/SQLite%20notebook.ipynb)
