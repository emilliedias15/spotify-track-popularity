## 🎵 Spotify Track Popularity Prediction 🎵

Predicting the popularity of songs based on audio features using Machine Learning.

### Objective

This project aims to predict whether a song will be **popular** based on audio and metadata from Spotify, provided through a Kaggle dataset. Popularity was transformed into a binary classification target to apply machine learning techniques.

### Dataset

The dataset was sourced from [Kaggle - Spotify Dataset](https://www.kaggle.com/datasets) and includes information about thousands of tracks, such as
- Track name, artist, album, and genre
- Popularity score (0 to 100)
- Audio features like danceability, energy, tempo, instrumentalness, acousticness, etc.

### Techniques Applied

- **Exploratory Data Analysis (EDA)**
- **Target variable binarization (`popularity`)**
- **Training and comparing classification models:** Logistic Regression and Random Forest
- **Cross-validation with StratifiedKFold**
- **Evaluation using F1-Score**
- **Feature importance visualization**

### Key Results

- The **Random Forest** model outperformed others with an **F1-Score ≈ 0.49**
- The most important feature was `instrumentalness`, suggesting that the presence or absence of vocals strongly influences a song’s popularity

### Tools & Technologies

Python (Pandas, Scikit-learn, Matplotlib, Seaborn), Jupyter Notebook, Git/GitHub
