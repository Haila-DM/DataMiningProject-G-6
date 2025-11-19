<img width="129" height="77" alt="image" src="https://github.com/user-attachments/assets/d3c184b4-025c-4b66-b60c-95bd7eb981ce" />

# DEBRE TABOR UNIVERSTY
# GAFAT INSTITUTE OF TECHNOLOGY
# DEPARTMENT OF COMPUTER SCIENCE

# Data-Mining-Project-Group-6
Data mining project for group-6 on title of Exploratory Data Analysis (EDA) of Netflix Movies and TV Shows.

# 🎬 Netflix Movies and TV Shows - Exploratory Data Analysis
# Netflix Content Analysis & Classification

## 📊 Project Overview
This project performs Exploratory Data Analysis (EDA) and builds machine learning models to analyze Netflix's content catalog, classify content types (Movies vs TV Shows), and predict content duration.

## 🎯 Objectives
- Analyze trends in Netflix content addition over time
- Study ratings distribution and common genres
- Build classification models to predict content type (Movie vs TV Show)
- Develop regression models to predict content duration

## 📁 Dataset
- **Source**: `netflix_titles.csv`
- **Records**: 8,807 titles
- **Features**: 12 columns including type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

## 🛠️ Technical Implementation

### Data Preprocessing & Feature Engineering
- Handled missing values in director, cast, country, rating
- Created new features:
  - `added_year`, `added_month` from date_added
  - `title_length` from title text length
  - `cast_count` from number of cast members
  - `is_movie` binary target variable
  - `duration_int` and `duration_type` from duration field

### Machine Learning Models

#### Classification Models (Movie vs TV Show Prediction)
- **Logistic Regression**: 99.89% Accuracy
- **Random Forest Classifier**: 100% Accuracy

#### Regression Models (Duration Prediction)
- **Linear Regression**: R² Score = 0.094
- **Random Forest Regressor**: R² Score = 0.387

## 📈 Key Visualizations
The project includes several insightful visualizations:
- Count of Movies vs TV Shows
- Top 10 countries producing Netflix content  
- Distribution of content ratings

## 🚀 Key Results

### Classification Performance
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 99.89% | 1.00 | 1.00 | 1.00 |
| Random Forest | 100% | 1.00 | 1.00 | 1.00 |

### Regression Performance
| Model | MAE | MSE | R² Score |
|-------|-----|-----|----------|
| Linear Regression | 0.820 | 0.910 | 0.094 |
| Random Forest | 0.599 | 0.616 | 0.387 |

## 💡 Insights
1. **Excellent Classification**: Models can perfectly distinguish between Movies and TV Shows
2. **Feature Effectiveness**: Engineered features like duration patterns are highly predictive
3. **Regression Challenge**: Predicting exact duration is more difficult than classification
4. **Content Patterns**: Clear differentiation between movie and TV show characteristics

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

- ## 👨‍💻 Authors
| Name        | ID_NO  |
|--------------|--------|
| Haile Demewoz   | 4022  |
| Meckyias Adefris | 1388  |
| Mekuria  Belete  | 1431  |
| Tigist Getnet  | 1394  |
| Mekilit Tadess   | 1104  |
| Kalkidan Cheru  | 1514  |

                             Submission date 23/03/2018 E.C.
