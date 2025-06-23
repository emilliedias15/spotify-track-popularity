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

### Key Results

- The **Random Forest** model outperformed others with an **F1-Score ≈ 0.26**
- The most important feature was `instrumentalness`, suggesting that the presence or absence of vocals strongly influences a song’s popularity
- Musical production features influence a track's hit potential more than just genre or artist alone

### Tools & Technologies

Python (Pandas, Scikit-learn, Matplotlib, Seaborn), Jupyter Notebook, Git/GitHub

---------------------------

## 🎵 Previsão de Popularidade de Músicas no Spotify 🎵

Utilização de Machine Learning para prever a popularidade de músicas baseada em variáveis disponibilizadas pelo app Spotify

### Objetivo
Este projeto tem como objetivo prever se uma música será popular com base em metadados e atributos sonoros fornecidos pelo Spotify por meio de um dataset disponível no Kaggle. A variável de popularidade foi transformada em uma variável binária para aplicação de modelos de classificação.

### Dataset
O dataset foi obtido do Kaggle - Spotify Dataset e inclui informações sobre milhares de faixas, como:

- Nome da música, artista, álbum e gênero
- Score de popularidade (de 0 a 100)
- Atributos de áudio como: dançabilidade, energia, tempo (BPM), instrumentalidade, acústica, entre outros

### Técnicas Aplicadas

- Análise Exploratória de Dados (EDA)
- Binarização da variável alvo (popularity)
- Treinamento e comparação de modelos de classificação: Regressão Logística e Random Forest
- Validação cruzada com StratifiedKFold
- Avaliação utilizando F1-Score

### Principais Resultados

- O modelo Random Forest apresentou o melhor desempenho, com F1-Score ≈ 0.26
- A variável mais relevante foi instrumentalness, sugerindo que a presença ou ausência de vocais influencia fortemente a popularidade de uma música
- Características de produção musical influenciam mais o potencial de uma faixa se tornar hit do que apenas o gênero ou artista.

### Tecnologias Utilizadas

Python (Pandas, Scikit-learn, Matplotlib, Seaborn), Jupyter Notebook, Git/GitHub

