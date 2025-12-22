# YouTube-Watch-History-Analysis-User-Behavior-Insights-Using-Data-Analytics-Machine-Learning

A **privacy-aware, end-to-end data analytics and machine learning project** that analyzes personal YouTube watch history data to uncover viewing patterns, behavioral trends, and user personas using **exploratory data analysis, feature engineering, and unsupervised learning**.

> **Privacy Note**  
> Due to the sensitive nature of personal watch history data, raw datasets, trained models, and Power BI `.pbix` files are intentionally **not included**.  
> This repository focuses on **methodology, code, visualizations, and insights**, reflecting real-world industry practices where user data confidentiality is critical.

---

## Project Motivation

Modern content platforms generate large volumes of behavioral data, but extracting **meaningful insights** requires structured analysis and responsible data handling.

This project simulates a **real-world analytics workflow** by:
- Working with private, user-level interaction data  
- Deriving insights without exposing sensitive information  
- Presenting findings through both **code-driven analysis** and an **interactive BI dashboard**

The dataset spans **2023 to 2025**, enabling both **temporal trend analysis** and **behavioral segmentation**.

---

## Project Objectives

- Clean and preprocess YouTube watch history logs  
- Perform **exploratory data analysis (EDA)** to understand viewing behavior  
- Engineer behavioral features (time-based, frequency-based, activity patterns)  
- Segment viewing behavior using **K-Means clustering**  
- Validate clusters using **Elbow Method** and **Silhouette Score**  
- Translate analytical results into **business-style insights** using a dashboard  

---

## End-to-End Workflow

1. **Data Ingestion & Cleaning**  
   - Parsed YouTube watch history export  
   - Removed noise, handled missing values, standardized timestamps  

2. **Exploratory Data Analysis (EDA)**  
   - Viewing activity by day of week  
   - Time-of-day consumption patterns  
   - Channel-wise engagement distribution  
   - Long-term usage trends (2023–2025)

3. **Feature Engineering**  
   - Temporal features (hour, day, weekday/weekend)  
   - Watch frequency metrics  
   - Aggregated behavioral signals for clustering  

4. **Unsupervised Learning (Clustering)**  
   - Applied **K-Means clustering** for viewer persona identification  
   - Used Elbow Method and Silhouette Score to select optimal `k`  
   - Interpreted clusters as meaningful behavioral personas  

5. **Insight Communication**  
   - Converted analytical findings into a **Power BI dashboard**  
   - Focused on clarity, storytelling, and decision-oriented insights  

---

## Machine Learning Approach

### Model Used
- **K-Means Clustering** (Unsupervised Learning)

### Why K-Means?
- Effective for behavioral segmentation problems  
- Scales well for large interaction datasets  
- Produces interpretable clusters for analysis  

### Model Validation
- **Elbow Method** to observe inertia reduction  
- **Silhouette Score** to assess cluster separation and cohesion

<img width="1112" height="483" alt="image" src="https://github.com/user-attachments/assets/3cbdda53-83ce-40a5-a36a-667ff11f16fa" />

<img width="1074" height="715" alt="image" src="https://github.com/user-attachments/assets/5b3a6662-3414-4095-9571-863d6561b4c1" />

Both techniques were used together to ensure the clustering choice was **data-driven and justified**.

---

## Dashboard Overview

The Power BI dashboard summarizes key behavioral insights derived from the analysis.

<img width="1206" height="679" alt="YouTube Dashboard" src="https://github.com/user-attachments/assets/31611a57-a5fe-482a-bf26-b193f22d9c63" />

---

## Project Structure

```text
youtube-watch-analysis/
│
├── notebooks/
│   └── youtube_analysis.ipynb   # Complete EDA + ML pipeline
│
├── data/
│   ├── raw/        # Personal YouTube exports (not shared)
│   └── processed/  # Derived datasets (not shared)
│
├── models/         # Reserved for trained models (not uploaded)
│         
│
├── requirements.txt
└── README.md
````

---

## Data Privacy & Ethical Considerations

* The dataset contains **personal user behavior data**
* To maintain privacy:

  * Raw datasets are not uploaded
  * Trained model files are not shared
  * Only code, visualizations, and documented insights are published

This mirrors industry-standard data governance practices.

---

## Tech Stack

* **Python**
* **Pandas** – Data manipulation
* **Matplotlib** – Visualization
* **Scikit-learn** – Clustering & evaluation
* **Jupyter Notebook** – Analysis environment
* **Power BI** – Insight visualization

---

## How to Use This Repository

Even without the dataset, you can:

1. Review the notebook to understand the **complete analytical workflow**
2. Replace the data-loading section with your own YouTube watch history export
3. Re-run the analysis end-to-end
4. Adapt the clustering logic to other user behavior datasets

---

## Key Learnings

* Real-world data is often private, noisy, and sensitive
* Feature engineering is critical in unsupervised learning
* Cluster validation is essential before interpretation
* Presenting insights responsibly is as important as model accuracy

---

## Future Enhancements

* Time-series forecasting of viewing behavior
* Comparison with alternative clustering techniques (DBSCAN, Hierarchical)
* Category-level and topic-level content analysis
* Public demo using synthetic or anonymized data

---

## Author

**Shireen Kachroo**
Data Science & ML Enthusiast

---

⭐ If you find this project insightful, feel free to explore the notebook and adapt the approach to your own data.


