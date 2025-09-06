# 🍽️ Eatery Rating Prediction

This machine learning project predicts customer ratings for eateries based on restaurant metadata and textual reviews. It combines structured data with natural language processing to build robust regression models.

## 📁 Dataset Overview

- `train.csv`: Training data with features and target (`rating`)
- `test.csv`: Test data without target
- `sample_submission.csv`: Format for submitting predictions

### 🔍 Features

| Column         | Description                                 |
|----------------|---------------------------------------------|
| `id`           | Unique identifier                           |
| `store_name`   | Name of the eatery                          |
| `category`     | Type of restaurant                          |
| `store_address`| Address of the restaurant                   |
| `latitude`     | Geolocation (latitude)                      |
| `longitude`    | Geolocation (longitude)                     |
| `rating_count` | Number of ratings received                  |
| `review_time`  | Time since review was posted                |
| `review`       | Textual review from customer                |
| `rating`       | Target variable (customer rating)           |

---

## 🧠 Problem Statement

Predict the `rating` given by a customer based on structured features and review text. This is a **regression** task.

---

## ✅ Workflow Checklist

1. Identify data types of all columns  
2. Present descriptive statistics for numerical features  
3. Handle missing values  
4. Remove duplicates  
5. Detect and treat outliers  
6. Visualize key patterns (at least 3 plots with insights)  
7. Scale numerical features and encode categorical ones  
8. Build at least 7 regression models  
9. Perform hyperparameter tuning on 3 models  
10. Compare model performances using metrics like MAE, RMSE, R²


