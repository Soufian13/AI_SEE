# Project Scope: AI_SEE what you like - Book predictions based on Sentiment Analysis

## 1. Project Overview

The project **"AI_SEE what you like"** aims to enhance the book recommendation process by developing a model that leverages sentiment analysis of user reviews instead of relying solely on traditional star ratings. This approach is designed to provide more personalized and accurate book recommendations by understanding and interpreting the sentiments expressed in text reviews. The project was part of our participation in the Artifical Intelligence track of Techlabs Düsseldorf's Digital Shaper program in the summer term 2024.

## 2. Objectives

- **Improve Recommendation Accuracy:** Utilize sentiment analysis to generate more accurate book recommendations tailored to individual user preferences.
- **Leverage Sentiment Analysis:** Implement advanced sentiment analysis using a modified BERT language model  to understand user opinions beyond star ratings (bert-base-multilingual-uncased-sentiment model from NLPTown provided on HuggingFace). This modified BERT model (we call it “HuggingFace BERT”) is an open-source tool that has been specifically developed for the purpose of sentiment analysis. 
- **Outperform Traditional Systems:** Achieve a recommendation model with better performance metrics compared to traditional star rating-based systems.

## 3. Deliverables

- **Sentiment Analysis Model:** Develop and fine-tune a sentiment analysis model using the HuggingFace BERT framework to classify text reviews into various sentiment categories.
- **Recommendation Model:** Create a recommendation system using XGBRegressor that predicts user preferences based on sentiment analysis results.
- **Data Processing Pipeline:** Build a pipeline for preprocessing and transforming data, including handling text reviews and encoding categorical features.
- **Recommendation Output:** Generate personalized book recommendations for users, excluding books they have already rated.
- **Final Report:** Document the methodology, implementation details, performance metrics, and results in a comprehensive final report.

## 4. Scope of Work

- **Data Collection and Preparation:**
  - Obtain and preprocess a dataset containing Amazon book reviews, including star ratings, written reviews, and metadata.
  - Perform data cleaning and transformation to prepare the dataset for sentiment analysis and model training.

- **Sentiment Analysis:**
  - Implement sentiment analysis using the HuggingFace BERT model to categorize reviews into sentiment levels.
  - Handle challenges related to long reviews and ensure data security and integrity during processing.

- **Model Development and Evaluation:**
  - Train and evaluate various machine learning models (XGBRegressor, LightGBM, CatBoost) to identify the best-performing model for book recommendations.
  - Fine-tune the selected model using hyperparameter optimization techniques.

- **Recommendation System Implementation:**
  - Develop a system that utilizes the trained model to provide personalized book recommendations based on user review sentiments.
  - Ensure the system can handle new user IDs and generate recommendations for all users in the dataset.

- **Deployment and Testing:**
  - Test the recommendation system to validate its performance and accuracy.
  - Deploy the system and generate recommendations for all users, excluding books they have already rated.

## 6. Timeline

- **Week 1-2:** Finding and defining project scope, starting project management, model research, data collection and preprocessing.
- **Week 3-4:** Sentiment analysis.
- **Week 5-6:** Development of the recommendation model and integration with sentiment analysis. For that further data processing, cleaning, merging of data sets.
- **Week 7:** Training, Testing and validation of the recommendation system.
- **Week 8:** Documentation, reporting, and final project delivery.

## 7. Resources Required

- **Technical:** Access to Python libraries (Pandas, scikit-learn, HuggingFace BERT, XGBoost,...), computational resources (Google Colab or similar), and storage for datasets and models.


