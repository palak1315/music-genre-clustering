#  Music Genre Clustering & Recommendation System

#  Introduction
In an era where music streaming platforms offer millions of tracks, users often struggle to discover songs that match their taste. Music Recommendation Systems help solve this problem by automatically suggesting songs that align with a user’s preferences.
This project focuses on building a **content-based music recommendation system** using unsupervised machine learning. It clusters songs based on metadata such as **genre** and **popularity**, and recommends similar songs to a given track. The goal is to help users explore and enjoy music within their favorite genres more effectively.

## 🛠️ Technologies and Tools Used
- **Python**: Main programming language used for building the project  
- **Jupyter Notebook**: Interactive development environment for coding and analysis  
- **Pandas**: For reading, cleaning, and analyzing the dataset  
- **NumPy**: For numerical operations and array handling  
- **Scikit-learn (sklearn)**: Used for K-Means clustering and feature scaling  
- **Matplotlib & Seaborn**: For creating visualizations to understand clusters and song distributions 

### 📄 Main Features in the Dataset
- `id`: Unique identifier of the song on Spotify  
- `name`: Name/title of the song  
- `genre`: Genre of the song (used for clustering)  
- `artists`: Artists who performed the song  
- `album`: The album to which the song belongs  
- `popularity`: A score (0–100) indicating how popular the song is on Spotify  
- `duration_ms`: Duration of the song in milliseconds  
- `explicit`: Boolean indicating whether the song has explicit content
   
# Project Steps
1. **Data Cleaning**: Removed missing and duplicate values, retained relevant columns  
2. **Feature Engineering**: Normalized popularity and duration  
3. **Clustering**: Applied K-Means to group songs into clusters based on popularity and genre  
4. **Visualization**: Used scatter plots and cluster visualizations to interpret results  
5. **Recommendation**: For a given song, suggested other songs from the same cluster





