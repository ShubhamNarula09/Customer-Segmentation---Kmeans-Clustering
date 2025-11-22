# Customer Personality Analysis – Grocery Retail Segmentation

## **Project Overview**

This project analyzes a grocery retailer’s customer dataset to uncover meaningful segments based on demographics, spending patterns, and engagement behavior. Using exploratory data analysis and clustering techniques, the project aims to group customers by their characteristics and behavior. These insights enable the retailer to develop targeted marketing strategies, tailor promotions to the right audiences, and improve topline growth.

---

## **Business Objective**

* Identify Customer Segments: Segment the retailer’s customer base based on demographics, purchasing patterns, and engagement behavior.
* Analyze Behavioral Insights: Explore spending habits and interaction patterns to understand different customer preferences.
* Enable Targeted Marketing: Use segmentation insights to design personalized promotions and marketing campaigns.

---

## **Dataset**

* **Source:** Kaggle – [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
* **Files included:**

  * `marketing_campaign.csv` – Main customer dataset with demographics, purchase behavior, and engagement metrics.
  * `customer_personality_segmentation_schema.csv` – Schema describing each column in the dataset.

---

## **Folder Structure**

```
customer-personality-analysis/
│
├── data/
│   ├── marketing_campaign.csv
│   ├── customer_personality_segmentation_schema.csv
│
├── notebooks/
│   ├── Customer_Personality_Analysis.ipynb
│
├── README.md
├── requirements.txt
```

---

## **Technical Stack**

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Techniques:**

  * Data Cleaning and Preprocessing
  * Feature Engineering
  * Exploratory Data Analysis
  * K-Means Clustering
  * Silhouette Analysis & Cluster Validation
  * Data Visualization (Heatmaps, Distribution Plots, Cluster Profiles)

---

## **Methodology**

1. **Data Preprocessing**

   * Handle missing values
   * Handling outliers.
   * Feature engineering: calculate age, total purchases, etc. 

2. **Exploratory Data Analysis (EDA)**

   * Univariate analysis of demographics and purchase behavior.
   * Correlation analysis between features.

3. **Clustering**

   * Scale features using `StandardScaler`.
   * Apply K-Means for cluster counts ranging from 2–5.
   * Evaluate clusters using silhouette scores and inertia (Elbow Method).

4. **Cluster Analysis**

   * Analyze cluster centers to understand demographic and behavioral patterns.
   * Generate business insights for each cluster.

---

## **Key Insights**

* **Cluster 1:** Low-value customers; minimal purchases despite frequent web visits; low marketing priority.
* **Cluster 2:** High-value customers; high spending across categories; primary target for promotions; focus on store & catalog channels.
* **Cluster 3:** Medium-value, deal-seeking segment; moderate spending; engage heavily online; secondary marketing focus with mid-priced products.

---

## **Results & Visualization**

* Cluster profile heatmaps showing spending and engagement across clusters.
* Silhouette plots validating cluster separation.
---

## **How to Run**

1. Clone the repository:

```bash
git clone https://github.com/ShubhamNarula09/Customer-Segmentation---Kmeans-Clustering.git
cd Customer-Segmentation---Kmeans-Clustering
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/Customer_Segmentation.ipynb
```

---

## **Future Enhancements**

* Explore hierarchical or DBSCAN clustering for alternative segmentation approaches.
* Explore nonlinear classification techniques to reduce misclassification caused by linear decision boundaries. Specifically, applying Gaussian (RBF) or polynomial kernels can map features into higher-dimensional space, capturing complex relationships and improving model accuracy
* Build an interactive dashboard for cluster exploration and business reporting.

---
