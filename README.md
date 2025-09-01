# 🎶 Song Popularity Prediction  

## 🧠 Problem Statement  
Music streaming platforms like **Spotify** and **Apple Music** host millions of tracks, but only a small percentage become viral or popular.  

This project aims to:  
- Analyze **what drives song popularity**  
- Build a **predictive tool** that estimates a song’s success (in terms of streams) using **audio features** and **platform-level metadata**  

---

## ⚙️ Tech Stack  
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, joblib, streamlit  
- **Deployment**: Streamlit web app (local or cloud)  

---

## 📊 Exploratory Data Analysis (EDA)  
- Distribution & seasonality of stream counts  
- Role of playlists & platform visibility  
- Correlation heatmaps & feature vs. streams trends  
- Audio traits impact: danceability, energy, valence, etc.  

---

## 🏗️ Modeling Approach  
Tried multiple regression models **before & after log transformation**:  
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

**Best Model**: Random Forest Regressor (after log transformation)  
- R² ≈ **0.79**  
- Trained with and without cross-validation  

---

## 📈 Feature Importance  
- Playlist presence (Spotify, Apple) → **highest predictive power**  
- Audio features like energy & danceability → **moderate importance**  
- Platform strategy & visibility → **strong influence**  

---

## 💼 Business Implications  
- **A&R Teams** → Scout high-potential songs  
- **Marketing Teams** → Plan release schedules effectively  
- **Streaming Platforms** → Understand playlist impact on visibility  
- **Artists/Labels** → Align audio traits with playlist compatibility  

---

