# YouTube-Watch-History-Analysis-User-Behavior-Insights-Using-Data-Analytics-Machine-Learning

A privacy‑aware, end‑to‑end data analysis and machine learning project that explores personal YouTube watch history to uncover viewing patterns and segment content consumption behavior using unsupervised learning (K‑Means clustering).

> **Note on Privacy**: This project intentionally does **not** include raw datasets or trained model files. The analysis is demonstrated through code, methodology, visualizations, and documented insights while fully preserving personal data privacy.

---

## Project Overview

Modern content platforms generate massive amounts of user interaction data. This project focuses on analyzing **YouTube Watch History data** to:

* Understand personal viewing behavior
* Extract meaningful features from raw watch logs
* Identify natural groupings in viewing patterns using clustering
* Apply proper model selection techniques (Elbow & Silhouette)

The project reflects **real‑world data handling**, where sensitive user data cannot always be shared publicly.

---

## Objectives

* Parse and preprocess YouTube watch history data
* Perform exploratory data analysis (EDA)
* Engineer meaningful features for clustering
* Apply **K‑Means clustering** for viewer segmentation
* Determine the optimal number of clusters using:
  * Elbow Method
  * Silhouette Score Analysis
* Visualize and interpret clustering results

---

## Machine Learning Approach

### Model Used

* **K‑Means Clustering** (Unsupervised Learning)

### Why K‑Means?

* Efficient for large datasets
* Easy to interpret cluster behavior
* Widely used for customer/viewer segmentation problems

### Model Selection Techniques

* **Elbow Method**: To analyze inertia reduction with increasing clusters
* **Silhouette Score**: To evaluate cluster cohesion and separation

Both techniques were used together to ensure a **well‑justified choice of `k`**, rather than an arbitrary selection.

---

## Key Visualizations


---

## Project Structure

```text
youtube-watch-analysis/
│
├── data/
│   ├── raw/                # Original YouTube export files (NOT uploaded)
│   └── processed/          # Cleaned/derived data (ignored for privacy)
│
├── notebooks/
│   └── youtube_analysis.ipynb   # Main analysis & ML notebook
│
├── models/                 # Reserved for trained models (not uploaded)
│
├── app/                    # Future dashboard / Streamlit app (planned)
│
├── src/                    # Helper scripts
│
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## Data Privacy & Ethical Considerations

* The dataset contains **personal watch history**, which is sensitive user data
* To prevent privacy breaches:
  * ❌ Raw data files are **not uploaded**
  * ❌ Trained model files (`.pkl`) are **not shared**
  * ✅ Only code, methodology, and results are published

This mirrors industry practices, where data confidentiality is critical.

---

## Tech Stack

* **Python**
* **Pandas, NumPy** – Data manipulation
* **Matplotlib, Seaborn** – Visualization
* **Scikit‑learn** – Clustering & evaluation
* **Jupyter Notebook** – Analysis environment

---

## How to Use This Repository

Although the raw data is not included, you can:

1. Review the notebook to understand the **full analysis pipeline**
2. Replace the data loading section with your own YouTube watch history export
3. Re‑run the notebook end‑to‑end
4. Adapt the clustering logic to other behavioral datasets

---

##  Key Learnings

* Real‑world data is often messy and sensitive
* Feature engineering plays a crucial role in unsupervised learning
* Cluster validation is essential before drawing conclusions
* Privacy‑preserving project presentation is a valuable professional skill

---

## Future Enhancements

* Time‑series analysis of viewing habits
* Comparison with alternative clustering methods (DBSCAN, Hierarchical)
* Content category‑based behavioral insights

---

## Author

**Shireen Kachroo**
B.Tech Computer Science Engineering
Focused on Data Analysis, Machine Learning, and Privacy‑Aware Systems

---

⭐ *If you find this project insightful, feel free to explore the notebook and adapt it for your own data.*
