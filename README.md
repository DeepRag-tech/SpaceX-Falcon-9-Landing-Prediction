🚀 SpaceX Falcon 9 First Stage Landing Prediction

Introduction:

  This repository contains the full data science capstone project, which aims to predict the success of a SpaceX Falcon 9 first-stage landing. The reusability of the first stage is a key factor in reducing launch costs from over $165 million to approximately $62 million. By building a model to predict landing success, we can better determine the true cost of a launch, providing valuable information for competitive analysis and risk assessment.
This project follows a complete data science workflow, from data collection and wrangling to exploratory data analysis, interactive visualization, and predictive modeling.

The project includes end-to-end data science workflow:


✅ REST API data collection

✅ Web scraping from Wikipedia

✅ Data wrangling and feature engineering

✅ Exploratory Data Analysis (EDA) with SQL and visualization tools

✅ Interactive mapping with Folium

✅ Dashboard development using Plotly Dash

✅ Machine learning classification with model tuning and evaluation



🛠️ Technologies & Methodologies Used:

Data Collection: REST APIs (requests), Web Scraping (BeautifulSoup)

Data Analysis & Wrangling: pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Database: SQL, SQLite

Interactive Analytics: Folium (Geospatial Mapping), Plotly Dash (Web Dashboard)

Machine Learning: scikit-learn

Preprocessing: StandardScaler, OneHotEncoder

Models: Logistic Regression, Support Vector Machine (SVM), Decision Tree, K-Nearest Neighbors (KNN)

Tuning & Evaluation: GridSearchCV



Summary of Results & Key Findings:

Exploratory Analysis: EDA revealed strong correlations between landing success and several key features. The success rate demonstrably improves with higher flight numbers (experience), and is highly dependent on the target orbit (GTO being the most challenging) and the payload mass.

Predictive Model Performance: After hyperparameter tuning and evaluation on unseen test data, three models (Logistic Regression, SVM, and KNN) achieved an identical top-tier accuracy of 83.33%. The Logistic Regression model was highlighted for its excellent balance of performance and interpretability. Its confusion matrix revealed a perfect recall for successful landings, though with a slight tendency for false positives.


Interactive Dashboard:

This project includes a fully interactive web dashboard built with Plotly Dash.
Features:

Select a specific launch site from a dropdown menu to see its performance.

Filter launch data by a specific payload mass range using a slider.

All charts update dynamically based on user selections.


How to Run the Dashboard:

Ensure you have all the required packages installed: pip install pandas dash plotly

Download the spacex_dash_app.py script and the spacex_launch_dash.csv dataset into the same directory.

Open a terminal, navigate to that directory, and run the command:

Generated bash

python spacex_dash_app.py

Use code with caution.
Bash

Open your web browser and navigate to the URL provided in the terminal (usually http://127.0.0.1:8050/).
