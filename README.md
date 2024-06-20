# Exploring Road Traffic Accident Data and Text Analytics

This project involves the analysis of road traffic accident data and text mining of tweets related to traffic incidents. The analysis includes data exploration, predictive modeling, and sentiment analysis. The findings and recommendations aim to improve road safety.

## Table of Contents

1. [Data Exploration](#data-exploration)
   - 1.1 [Explanatory Data Analysis](#explanatory-data-analysis)
   - 1.2 [Summary Statistics](#summary-statistics)
   - 1.3 [Visualization](#visualization)
   - 1.4 [Data Cleaning](#data-cleaning)
   - 1.5 [Data Balancing](#data-balancing)
2. [Predicting Accident Severity](#predicting-accident-severity)
   - 2.1 [Explanation of the Scenario](#explanation-of-the-scenario)
   - 2.2 [Predictive Models and Use Cases](#predictive-models-and-use-cases)
     - 2.2.1 [Random Forest Algorithm](#random-forest-algorithm)
     - 2.2.2 [Neural Network](#neural-network)
   - 2.3 [Comparative Analysis](#comparative-analysis)
   - 2.4 [Interpretation of Results](#interpretation-of-results)
   - 2.5 [Importance of Features](#importance-of-features)
   - 2.6 [Conclusion](#conclusion)
   - 2.7 [Recommendations](#recommendations)
3. [Text Mining for Tweets](#text-mining-for-tweets)
   - 3.1 [Exploration of Dataset](#exploration-of-dataset)
   - 3.2 [Text Preprocessing](#text-preprocessing)
   - 3.3 [Explanatory Analysis](#explanatory-analysis)
   - 3.4 [Sentiment Analysis](#sentiment-analysis)
   - 3.5 [Summarization of Sentiment Analysis](#summarization-of-sentiment-analysis)
4. [Managerial Report](#managerial-report)
5. [Appendix](#appendix)
6. [References](#references)

## Data Exploration

### Explanatory Data Analysis

The Road Accident 2022 Surrey dataset was analyzed to understand the central tendency and dispersion of key variables. The dataset contains 2806 records and 35 variables, with accident severity as the target variable.

### Summary Statistics

Summary statistics were generated to provide insights into the data, focusing on variables such as speed limit, day of the week, light conditions, weather conditions, road surface conditions, and road type.

### Visualization

Visualizations were created to identify outliers and understand the distribution of variables.

### Data Cleaning

Data cleaning involved removing outliers and handling missing values to ensure the accuracy of the analysis.

### Data Balancing

The data was balanced to ensure equal representation of accident severity categories.

## Predicting Accident Severity

### Explanation of the Scenario

Various variables were analyzed to predict accident severity, including road surface, road type, weather conditions, day of the week, and light conditions.

### Predictive Models and Use Cases

#### Random Forest Algorithm

A robust and accurate model that uses bagging and feature prioritization to handle non-linear relationships and interactions between features.

#### Neural Network

A deep learning model that captures complex patterns and relationships in the data.

### Comparative Analysis

A comparison between the Random Forest and Neural Network models was conducted to determine the best-performing model.

### Interpretation of Results

The Random Forest model had a higher accuracy and lower misclassification rate compared to the Neural Network model.

### Importance of Features

The importance score of each variable was analyzed to understand which features contributed most to predicting accident severity.

### Conclusion

The Random Forest model was found to be the better-performing model based on accuracy and misclassification rate.

### Recommendations

Based on the findings, recommendations were made to improve road safety, such as implementing targeted safety measures and speed management strategies.

## Text Mining for Tweets

### Exploration of Dataset

The Tweets_2022 dataset was analyzed to extract insights from the text data.

### Text Preprocessing

Text preprocessing involved removing punctuation, stop words, and other irrelevant information to streamline the analysis.

### Explanatory Analysis

Information extraction and document categorization were performed using natural language processing techniques.

### Sentiment Analysis

Sentiment analysis was conducted to determine the sentiment expressed in the tweets, categorized as positive, negative, or neutral.

### Summarization of Sentiment Analysis

The sentiment analysis revealed that the majority of tweets expressed negative sentiment.

## Managerial Report

A comprehensive analysis and strategic recommendations for road safety were presented based on the findings from the data exploration, predictive modeling, and sentiment analysis.

## Appendix

Includes model pipelines, graphs, importance scores, ROC curves, and codes for data balancing and sentiment scoring.

## References

1. Ziegler, A. and König, I.R., 2014. Mining data with random forests: current options for real‐world applications. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery, 4(1), pp.55-63.
2. Verikas, A., Gelzinis, A. and Bacauskiene, M., 2011. Mining data with random forests: A survey and results of new tests. Pattern recognition, 44(2), pp.330-349.
3. Wang, L. and Sui, T.Z., 2007, September. Application of data mining technology based on neural network in the engineering. In 2007 International Conference on Wireless Communications, Networking and Mobile Computing (pp. 5544-5547). IEEE.
4. Ni, X., 2008. Research of data mining based on neural networks. World Academy of Science, Engineering and Technology, 39(1), pp.381-384.
5. Cogburn, D. and Hine, M., 2017. Introduction to text mining in big data analytics Minitrack.
6. Nisbet, R., Elder, J. and Miner, G.D., 2009. Handbook of statistical analysis and data mining applications. Academic press.

