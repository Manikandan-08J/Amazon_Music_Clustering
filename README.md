# 🎵 Amazon Music Clustering

## 📌 Project Overview

This project applies **Unsupervised Machine Learning (K-Means Clustering)** to group songs based on their audio features such as energy, danceability, tempo, and acousticness.

The goal is to automatically organize songs into meaningful clusters without predefined labels, enabling better music discovery and recommendation.

---

## 🎯 Objective

* Group songs into meaningful clusters
* Identify patterns in audio features
* Support recommendation systems and playlist generation

---

## 🧠 Domain

**Music Analytics | Unsupervised Machine Learning**

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📊 Dataset

* File: `single_genre_artists.csv`

### Features Used:

* danceability
* energy
* loudness
* speechiness
* acousticness
* instrumentalness
* liveness
* valence
* tempo
* duration_ms

### Removed Columns:

* track_id
* track_name
* artist_name

---

## 🔍 Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Removed duplicates
* Cleaned dataset

### 2. Feature Selection

Selected only relevant audio features for clustering

### 3. Feature Scaling

Used **StandardScaler** to normalize data

### 4. Clustering

* Applied **K-Means Algorithm**
* Determined optimal clusters using:

  * Elbow Method
  * Silhouette Score

👉 **Optimal Clusters: 5**

---

## 📉 Dimensionality Reduction

* Used **PCA (Principal Component Analysis)**
* Reduced data to 2D for visualization

---

## 📊 Evaluation Metrics

* Silhouette Score
* Davies-Bouldin Index
* Inertia

---

## 📈 Results

* Successfully grouped songs into **5 distinct clusters**
* Each cluster represents a unique music pattern (energy, mood, tempo)

---

## 🎧 Cluster Insights

| Cluster   | Description         |
| --------- | ------------------- |
| Cluster 0 | Party / High Energy |
| Cluster 1 | Acoustic / Calm     |
| Cluster 2 | Instrumental        |
| Cluster 3 | Energetic / Fast    |
| Cluster 4 | Balanced / Mixed    |

---

## 💼 Business Use Cases

* 🎧 Personalized Playlist Generation
* 🔍 Music Recommendation Systems
* 🎤 Artist Competitor Analysis
* 📊 Market Segmentation

---

## 📦 Output

Final dataset with cluster labels:

```
amazon_music_clustered.csv
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
Amazon-Music-Clustering/
│
├── data/
├── notebooks/
├── output/
├── images/
├── requirements.txt
├── README.md
└── report.pdf
```

---

## 🔮 Future Improvements

* DBSCAN / Hierarchical Clustering
* Real-time recommendation system
* Integration with user listening data

---

## 👨‍💻 Author

**Manikandan Jayakumar**
