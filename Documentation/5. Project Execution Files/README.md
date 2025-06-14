# 🍽️ Restaurant Recommendation System

![Banner](https://img.shields.io/badge/AI%20Restaurant%20Recommender-Powered%20by%20ML-blueviolet?style=for-the-badge)

## ![Banner](<https://github.com/MilakeSuraj/Tic_Tac_Toe_Game/blob/main/Beige%20Modern%20Elegant%20Personal%20LinkedIn%20Banner%20(1).png?raw=true>)

## Project Overview

**_A full-stack AI-powered web application that recommends restaurants based on user preferences, budget, dietary needs, and location. Combines collaborative and content-based filtering for smart, personalized suggestions._**

---

## Home Screen

![Home Screen](https://raw.githubusercontent.com/MilakeSuraj/Restaurant-recommendation-System/main/Screenshots/homeScreen.gif)

## Recommendation Screen

![Recommendation Screen](https://raw.githubusercontent.com/MilakeSuraj/Restaurant-recommendation-System/main/Screenshots/RecommendationScreen.gif)

## Result Screen

![Result Screen](https://raw.githubusercontent.com/MilakeSuraj/Restaurant-recommendation-System/main/Screenshots/resultScreen.gif)

---

## Features

- **Hybrid Recommendation Engine:** Combines collaborative filtering (SVD) and content-based filtering for accurate, relevant results.
- **Personalized Suggestions:** Takes into account user preferences, budget, cuisine, and location.
- **Dynamic Adaptation:** Learns from user input and adapts recommendations.
- **Modern Web UI:** Clean, user-friendly interface built with Flask, HTML, and CSS.
- **Data Visualization:** Interactive charts and plots for insights into restaurant data.
- **Cold-Start Solution:** Hybrid approach helps recommend even for new users or restaurants.

---

## Technologies Used

- **Backend:** Python 3.10, Flask
- **Machine Learning:** scikit-learn, Surprise (SVD), NLTK
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Frontend:** HTML, CSS, JavaScript, Jinja2 (Flask templating)
- **Other:** Google Colab (for model development), CSV dataset

---

## Project Structure

```
Restaurant-Recommendation-System/
│
├── Flask/
│   ├── app1.py                     # Flask backend
│   ├── Final_Development_Phase.ipynb  # Flask dev notebook
│   ├── requirements.txt            # Python dependencies
│   ├── restaurant1.csv             # Processed restaurant dataset
│   ├── static/                     # Static assets (images, CSS)
│   └── templates/                  # HTML templates
│
├── Model/
│   └── Final_Development_Phase.ipynb  # Model training & evaluation notebook
│
├── Documentation...                # Additional docs/screenshots
└── README.md                       # Project overview (this file)
```

---

---

## Model Architecture

- **Content-Based Filtering:** Matches restaurant attributes (cuisine, cost, rating) to user preferences.
- **Collaborative Filtering (SVD):** Learns from user ratings to suggest restaurants similar users enjoyed.
- **Hybrid Approach:** Merges both strategies for robust, personalized recommendations.

---

## Dataset

- **Source:** [Zomato Bangalore Restaurants Dataset by Himanshu Poddar (Kaggle)](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)

---

## Conclusion

**_This project demonstrates how machine learning can enhance dining decisions by providing tailored restaurant recommendations. The hybrid model ensures both personalization and discovery, making it a powerful tool for users exploring new or familiar areas._**

---
