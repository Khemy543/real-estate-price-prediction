# Real Estate Property Classification and Price Prediction using Machine Learning

## Abstract
In the dynamic real estate market, accurately classifying properties and predicting prices is crucial. Leveraging machine learning (ML) algorithms such as Random Forests, Neural Networks, and Decision Trees, this study explores practical applications to address these challenges. The models are designed to optimize real estate decision-making by analyzing factors like location, amenities, and economic indicators. This report provides a comprehensive overview of the performance and potential of these models in enhancing real estate strategies.

## Introduction
The real estate industry is transforming with the adoption of artificial intelligence (AI) and ML technologies, revolutionizing property classification and price prediction. By analyzing extensive datasets of historical property sales, ML algorithms offer valuable insights for decision-making and investment optimization. This study focuses on developing robust classification and prediction models to aid stakeholders in navigating market complexities and improving efficiency and profitability in property transactions.

## Objective
This study aims to explore the use of ML algorithms for classifying properties into low, medium, and high classes and predicting property prices. By utilizing historical sales data, the goal is to develop accurate models that provide real estate professionals with tools to enhance investment strategies and optimize market outcomes.

## Dataset
The study uses two datasets: "Bangalore House Prices" from Kaggle and a "House Prices" dataset for property classification. The Bangalore dataset includes 9 columns and 13321 rows, covering features like size, location, and amenities. The "House Prices" dataset comprises 13 columns and 546 rows, providing a detailed view of property characteristics.

## Methodology
The research methodology includes five primary modules: dataset cleaning, removing outliers, data visualization, modeling, and price predictions. 

### Data Cleaning
Unnecessary columns were removed, and missing values were addressed. The dataset was standardized and enriched with relevant information for analysis.

### Removing Outliers
Outliers were identified and removed using a minimum threshold of 300 sqft per bedroom and the mean and standard deviation for price per square foot.

### Data Visualization
Histograms and box plots were used to visualize the distribution of property prices and other features, aiding in understanding trends and anomalies.

### Modeling
Three regression models (Decision Tree Regressor, Random Forest Regressor, Neural Network Regressor) and three classifier models (Decision Tree Classifier, Random Forest Classifier, Neural Network Classifier) were implemented. The models were evaluated based on their performance metrics.

## Results
The Neural Network Regressor demonstrated the best performance for the Bangalore dataset, while the Random Forest Classifier performed best for the House Prices dataset. Detailed performance metrics and visualizations (e.g., loss curves, confusion matrices) were provided to illustrate model effectiveness.

## Performance Evaluation
The top-performing model achieved a correlation score of 0.979552, indicating strong predictive accuracy. This performance surpassed that of reference models, showcasing the superior forecasting ability of the developed models.

## Conclusion and Future Work
The study successfully developed ML models for real estate classification and price prediction, providing a foundation for future enhancements. Future work could involve incorporating additional features, experimenting with advanced algorithms, and integrating external data sources. Deploying these models in real-world applications could further empower stakeholders with data-driven decision-making tools.
