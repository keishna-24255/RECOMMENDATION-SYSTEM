# RECOMMENDATION-SYSTEM

COMPANY : CODTECH IT SOLUTIONS

NAME: P. SANSKRITHI KRISHNA

INTERN ID: CT04DR1831

DOMAIN: Machine Learning

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

# DESCRIPTION ABOUT MY PROJECT
A Recommendation System is an AI-based tool that suggests items to users based on their past behavior, preferences, or similarity to other users. This project focuses on designing and implementing an effective recommendation model that predicts what a user may like next. Recommendation systems are widely used in platforms like Netflix, Amazon, YouTube, and Spotify. The goal of this project is to build a functional system that provides personalized and accurate recommendations powered by machine learning techniques.

⭐ Project Overview

This project implements a complete Recommendation Engine, covering data preprocessing, similarity computation, model building, and final recommendations. Using user–item interactions from a dataset (such as ratings, purchases, clicks, or views), the system identifies patterns and predicts what the user will prefer. The project demonstrates how machine learning can enhance user experience and improve decision-making by offering relevant suggestions.

🔹 1. Dataset Preparation

The first step was collecting and preparing the dataset. We used user–item data that typically contains:
User IDs
Item IDs
User ratings or interactions
Additional metadata (category, tags, price, etc.)
The dataset was cleaned to remove missing values, duplicates, and inconsistent entries. It was then split into training and testing sets to evaluate model performance.

🔹 2. Data Preprocessing

To ensure accurate recommendations, several preprocessing steps were performed:
Converting raw data into user–item matrices
Normalizing ratings
Handling missing data (since not all users rate all items)
Encoding categorical data
Removing noise and rare interactions
These steps helped the model learn meaningful relationships between users and items.

🔹 3. Types of Recommendation Techniques Used

The project implemented two main techniques:
✔ Collaborative Filtering
This technique predicts user preferences by analyzing similarities:
User-based filtering: Recommends items liked by similar users
Item-based filtering: Suggests items similar to those the user has interacted with
Similarity was calculated using metrics such as:
Cosine Similarity
Pearson Correlation
Euclidean Distance
✔ Content-Based Filtering
This method recommends items based on features and descriptions.
For example:
If a user likes action movies → suggest other action movies
If a user buys phones → recommend phones with similar features
TF-IDF vectors, item attributes, and metadata were used to measure content similarity.

🔹 4. Model Building and Training

Using Python libraries such as Pandas, NumPy, Scikit-learn, we built a hybrid model combining both collaborative and content-based filtering. The model was trained to learn:
User patterns
Item profiles
Similarity scores
This training process enables the system to predict what the user will likely prefer next.

🔹 5. Model Evaluation

To measure how well the recommendation system performs, we evaluated using:                                                                                        
RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)
Precision & Recall
Top-K Recommendation Accuracy
These metrics show the accuracy and relevance of the recommended items.

#OUTPUT

<img width="463" height="626" alt="Image" src="https://github.com/user-attachments/assets/5dedd7f7-52d8-43a0-bd99-8092b6ec57dc" />

<img width="443" height="416" alt="Image" src="https://github.com/user-attachments/assets/42819a37-490a-4853-8807-fdf66e511d0b" />

