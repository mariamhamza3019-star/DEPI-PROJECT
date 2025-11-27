

# 💪 Personalized Fitness Recommendation System

## 🔗 Important Links

| Resource | Link |
|----------|------|
| Live Demo (Hugging Face Spaces) | [Demo Link](https://huggingface.co/spaces/hanyawael/depi_project) |
| Peresntation| [Our Presentation](https://www.canva.com/design/DAG550YPHXI/AaSBNqaGmYkbLuTwPcvdYw/edit?utm_content=DAG550YPHXI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) |

---

## 📋 Project Overview

A machine learning-based platform that recommends personalized fitness workouts based on user body metrics and exercise preferences.  

| Feature | Description |
|---------|-------------|
| ML Pipeline | Data preprocessing, feature engineering, SMOTE resampling, and model training |
| Recommendation Engine | Suggests exercises based on user profile and similarity matrix |
| Personalization | Adjusts workouts according to user goals, experience, and injuries |
| GetFeedback Loop | Continuously collects user feedback to improve recommendations over time |

---

## 🌟 Key Features

| Feature | Description |
|---------|-------------|
| Machine Learning Pipeline | Handles preprocessing, feature engineering, and model training |
| Recommendation Engine | Generates personalized workouts using cosine similarity |
| User Personalization | Considers goals, experience level, equipment availability, and injuries |
| GetFeedback Loop | Users can provide feedback on recommended exercises; the system updates its suggestions accordingly |

---

## 📊 Dataset Details

| Attribute | Details |
|-----------|--------|
| Users | 8,000 |
| Exercises | 1,324 |
| Preprocessing Steps | Outlier detection, SMOTE resampling, normalization, categorical encoding |

---




**Data Flow:** User metrics → Feature Engineering → ML Model → Similarity Matrix → Personalized Recommendations → **GetFeedback Loop** → Model Update

---

## 📈 Model Performance

| Metric                       | Value                                                                                                        |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Supervised Learning Accuracy | 97%                                                                                                          |
| Similarity Matrix            | 1,324 × 1,324 validated                                                                                      |
| Top Features                 | Age, Weight, Muscle Mass, Fat Percentage, Max Heart Rate, Equipment, Experience, Goal, Avg Workout Intensity |
| Feedback Integration         | Recommendations improve over time using collected user feedback                                              |

---


## 🔬 Data Flow & Feature Engineering

| Step                     | Description                                                              |
| ------------------------ | ------------------------------------------------------------------------ |
| Input Features           | Age, Weight, Height, Gender, Heart Rate, Experience, Equipment, Injuries |
| Engineered Features      | BMI, Muscle-to-Fat Ratio, Exercise Intensity, etc.                       |
| Similarity Computation   | Cosine similarity on feature matrix                                      |
| Imbalanced Data Handling | SMOTE resampling                                                         |
| Outlier Detection        | Applied before model training                                            |
| Feedback Loop            | Updates recommendations dynamically based on user input                  |

---

## ⚕️ Injury Safety System

| Injury Type | Safety Handling                      |
| ----------- | ------------------------------------ |
| Shoulder    | Filter exercises targeting shoulders |
| Knee        | Filter exercises targeting knees     |
| Back        | Filter exercises targeting back      |
| Ankle       | Filter exercises targeting ankles    |
| Wrist       | Filter exercises targeting wrists    |
| Elbow       | Filter exercises targeting elbows    |
| Hip         | Filter exercises targeting hips      |

---

## 🏋️ Exercise Algorithm

| Component             | Description                                                                |
| --------------------- | -------------------------------------------------------------------------- |
| Recommendation Method | Personalized recommendations using 1,324 × 1,324 cosine similarity matrix  |
| User Matching         | Matches users to exercises with similar profiles and goals                 |
| Feedback Integration  | Cosine similarity scores updated using user feedback to refine suggestions |

---

## ✅ Technical Documentation

| Feature             | Description                                         |
| ------------------- | --------------------------------------------------- |
| Accuracy            | 97% supervised learning                             |
| Similarity Matrix   | 1,324 × 1,324 validated                             |
| Engineered Features | 9 key features explained                            |
| Class Balance       | SMOTE resampling applied                            |
| Outlier Detection   | Methodology documented                              |
| Injury Filtering    | 7 injury types filtered                             |
| GetFeedback Loop    | Continuous feedback improves recommendation quality |


