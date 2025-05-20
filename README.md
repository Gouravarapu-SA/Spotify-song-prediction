# 🎧 Spotify Song Popularity Prediction

Ever wondered what makes a song go viral on Spotify? This project dives into a dataset of popular tracks to uncover the patterns behind musical success and builds predictive models to estimate a song's popularity based on various features.

---

## 📊 Dataset

The project uses the **`Popular_Spotify_Songs.csv`** file, containing data on **953** popular songs, with features including:

- 🎵 **Track Name**  
- 🎤 **Artist(s) Name**  
- 📅 **Release Year, Month, and Day**  
- 📈 **Popularity Metrics**: Streams, playlist appearances, chart positions  
- 🎼 **Audio Features**: BPM, key, mode, danceability, energy, and more

---

## 🔍 Exploratory Data Analysis (EDA)

We start by exploring and visualizing the dataset to identify patterns and insights:

- ⏳ Distribution of song releases over the years  
- 🧑‍🎤 Artists with the most songs in the dataset  
- 💥 Top-performing songs based on streams and playlist appearances  
- 📊 Correlations between audio features and popularity

Visualizations are created using libraries like `seaborn`, `matplotlib`, and `plotly` to bring the data to life.

---

## 🤖 Modeling

The main goal is to **predict the popularity** of songs using machine learning.  
We experiment with multiple modeling approaches to predict key popularity metrics such as:

- 🔢 **Streams**
- 🎯 **Playlist appearances**

### 🛠️ Modeling Steps

- Feature selection and preprocessing  
- Regression models and evaluation (e.g., R², RMSE)  
- Model comparison and hyperparameter tuning  

---

## 🛠️ How to Use

### 🔧 Requirements

Install the required Python packages:

```bash
pip install numpy pandas seaborn matplotlib plotly wordcloud


## Future Work

Some potential areas for future work on this project include:

- Incorporating additional data sources, like audio features or chart performance, to improve the predictive model
- Exploring more advanced modeling techniques, like deep learning
- Deploying the model as a web application or API to make predictions on new songs


