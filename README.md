# 🧠 Clustering Analysis of Diabetes Risk and Progression in Pima Indian Females

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-Python-3776AB?style=for-the-badge&logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/Tech-Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Clustering-KMeans%20&%20Hierarchical-1abc9c?style=for-the-badge" alt="Clustering" />
  <img src="https://img.shields.io/badge/Data%20Scaling-MinMaxScaler-009688?style=for-the-badge" alt="MinMaxScaler" />
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-ff69b4?style=for-the-badge&logo=plotly" alt="Visualization" />
  <img src="https://img.shields.io/badge/Dataset-Pima%20Indian%20Diabetes-blueviolet?style=for-the-badge" alt="Pima Indian Diabetes Dataset" />
  <img src="https://img.shields.io/badge/Field-Healthcare%20Analytics-orange?style=for-the-badge" alt="Healthcare Analytics" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Completed Project" />
</p>


---

## 📖 Project Overview

This project conducts a clustering analysis on the **Pima Indian Diabetes dataset**, aiming to identify subgroups at different diabetes risk stages.  
Using **K-Means** and **Hierarchical Clustering**, the study uncovers patterns across medical indicators like **Glucose**, **BMI**, and **Insulin**, offering insights into early detection and personalized interventions.

✅ **Dataset:** 770 diagnostic records of Pima Indian females (21+ years) from the National Institute of Diabetes and Digestive and Kidney Diseases.

---

## 🛠️ Techniques Used

- **Data Cleaning and Imputation:** Replace invalid zero values; median imputation.
- **Normalization:** MinMaxScaler applied to bring features into [0, 1] range.
- **Exploratory Data Analysis:**  
  - Correlation heatmaps  
  - Pair plots (e.g., BMI vs Glucose)
- **Clustering:**
  - K-Means (using Elbow Method for k=3)
  - Hierarchical Clustering (Ward linkage, dendrogram analysis)

---

## ✨ Key Visualizations

| Visualization | Description |
|:--------------|:------------|
| ![Heatmap](heatmap1.png) | Correlation heatmap showing relationships between health features. |
| ![Pair Plot](pairplot.png) | Pair-wise feature comparison highlighting clustering tendencies. |
| ![K-Means Clusters](kmeans1.png) | Scatter plot (By stages) colored by K-Means risk groups. |
| ![K-Means Clusters](kmeans2.png) | Scatter plot (By risks) colored by K-Means risk groups. |
| ![Radar Chart](radar.png) | Comparison of feature averages across Low, Medium, and High risk clusters. |
| ![Agglomerative Clusters](agglomerativ-clustering.png) |Agglomerative Clustering to showcase Risk Groups |

*(📸 Replace `Images/xxx.png` with your actual screenshots if you have different paths!)*

---

## 🚀 Methodology

### 📂 Data Loading and Preprocessing
- Loaded dataset with `pandas`.
- Invalid zero entries replaced with `NaN` and imputed.
- Features scaled using **MinMaxScaler**.

### 📊 Exploratory Data Analysis
- Generated **pair plots** and **correlation heatmaps** to discover relationships.
- Identified clusters through visual trends.

### 🧩 Clustering

**K-Means Clustering:**
- Optimal `k=3` determined by Elbow Method.
- Grouped data into:
  - Cluster 0: **Low Risk**
  - Cluster 1: **Medium Risk**
  - Cluster 2: **High Risk**

**Hierarchical Clustering:**
- Applied Ward's method.
- Dendrogram cut at three clusters for comparison.

---

## 📈 Results

| Metric        | Cluster 0 (Low Risk) | Cluster 1 (Medium Risk) | Cluster 2 (High Risk) |
|:--------------|:---------------------|:------------------------|:---------------------|
| **Glucose**   | Low                  | Medium                  | High                 |
| **BMI**       | Low                  | Elevated                | High                 |
| **Insulin**   | Low                  | Moderate                | High                 |

- 🔥 **K-Means** efficiently segmented groups based on Glucose, BMI, and Insulin.
- 🧠 **Hierarchical Clustering** provided detailed data structure insights through dendrograms.
- 🏆 Both methods validated the existence of **Low**, **Medium**, and **High risk** groups.

---

## 🧠 Discussion

- **K-Means** was computationally efficient but required pre-specifying `k`.
- **Hierarchical Clustering** offered deeper insights without needing `k`, but was computationally heavier.
- Combining both methods provided **robust** and **validated** subgroup classifications.

---

## ✅ Conclusion

Clustering techniques provided actionable insights into the risk profiles of Pima Indian females for diabetes progression.  
This project demonstrates how machine learning can support **early diagnosis**, **risk stratification**, and **personalized care strategies** in healthcare.

---

## 🔮 Future Improvements

- Apply **Gaussian Mixture Models** for soft clustering.
- Incorporate **feature selection techniques** to optimize model performance.
- Expand dataset to multi-ethnic groups for broader generalization.

---

## 📚 References

- [Pima Indian Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?resource=download)
- [Hopkins Medicine - Diabetes Resources](https://www.hopkinsmedicine.org/health/conditions-and-diseases/diabetes)
- [Google Colab Notebook - Project Code](https://colab.research.google.com/drive/1-PwyX52YvBU0PxkjpPSL9_7tXkOFlcZu?usp=sharing)

---

## 📬 Contact

- **Hetu Patel**
- 📫 [hetu.patel@torontomu.ca](mailto:hetu.patel@torontomu.ca)
- 🌐 [Portfolio Website](https://hetuvpatel.github.io/hetu-patel-portfolio/)
- 💻 [GitHub Profile](https://github.com/Patel-Hetu)

---

> _"Empowering healthcare through machine learning, one cluster at a time."_ 🧠🚀
