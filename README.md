# **Customer Segmentation Using K-Means Clustering**
*A **Semester 1 MSc. Data Analytics** project at **Berlin School of Business & Innovation (BSBI)**, where I applied **K-Means clustering** to segment customers based on purchasing behavior. This project directly aligns with my professional experience at **Sakon (GSG)**, where I optimized data workflows and reduced errors by **11%**, and my focus on **data-driven decision-making** in retail and customer analytics.*

---

## **📌 Project Overview**
This project analyzes an **online retail dataset** (from UCI Machine Learning Repository) to segment customers using **K-Means clustering**. The goal was to identify distinct customer groups based on purchasing patterns (e.g., frequency, total spending, and quantity purchased) to enable **targeted marketing, personalized customer service, and resource allocation**. This mirrors my work at **Sakon (GSG)**, where I used data analytics to optimize customer insights and improve business strategies.

### **Key Achievements**
✅ **Data Cleaning & Preprocessing**: Handled missing values, duplicates, and outliers to ensure high-quality data—similar to my work at **Sakon**, where I reduced data errors by **11%**.
✅ **Exploratory Data Analysis (EDA)**: Generated visualizations (e.g., monthly sales trends, popular products) to uncover patterns—aligning with my **Power BI dashboard** experience.
✅ **K-Means Clustering**: Segmented customers into **2 optimal clusters** using the **silhouette score**, achieving clear separation for targeted strategies.
✅ **Business Insights**: Identified high-value customers and seasonal trends, directly applicable to **retail and marketing strategies**.

---

## **🔧 Technologies & Tools**
| **Tool/Technique**       | **Purpose**                                                                 | **Relevance to My CV**                                  |
|--------------------------|-----------------------------------------------------------------------------|--------------------------------------------------------|
| **Python**               | Data cleaning, visualization, and clustering (Pandas, Seaborn, Scikit-learn). | Used at **Sakon** for automating data workflows.       |
| **Jupyter Notebook**      | End-to-end analysis in a single interface.                              | Mirrors my **ETL automation** projects.               |
| **K-Means Clustering**   | Customer segmentation based on purchasing behavior.                     | Validates my **predictive modeling** skills.           |
| **Silhouette Score**     | Determining optimal clusters for segmentation.                            | Applied at **Mercedes-Benz** for model evaluation.     |
| **StandardScaler**       | Feature scaling for clustering.                                          | Reflects my **data preprocessing** expertise.         |

---

## **📂 Project Structure**

customer-segmentation-kmeans/
│
├── data/
│   ├── raw/                  # Original dataset (online_retail_II.xlsx)
│   └── processed/            # Cleaned and aggregated customer data
│
├── notebooks/
│   └── Customer_Segmentation.ipynb  # Jupyter Notebook with full analysis
│
├── outputs/
│   ├── monthly_sales_trends.png  # EDA: Sales trends over time
│   ├── top_products.png         # EDA: Most popular products
│   ├── silhouette_score.png     # Optimal clusters visualization
│   └── customer_clusters.csv   # Final segmented customer data
│
├── reports/
│   └── Customer_Segmentation_Report.pdf  # Full project report (from BSBI)
│
└── README.md
Copy

---

## **🚀 Key Insights & CV Parallels**
### **1. Data Cleaning = Real-World Data Quality**
- **Project**: Removed duplicates, handled missing values, and converted data types for analysis.
- **CV Validation**:
  - At **Sakon**, I reduced data errors by **11%** through similar cleaning techniques.
  - Ensured **high-quality inputs** for clustering, mirroring my focus on **data integrity** in professional projects.

### **2. EDA = Actionable Visualizations**
- **Project**: Created visualizations (e.g., monthly sales trends, top products) to uncover patterns.
- **CV Validation**:
  - Designed **Power BI dashboards** at Sakon to visualize KPIs—proving I can **turn data into decisions**.

### **3. K-Means Clustering = Customer-Centric Strategies**
- **Project**: Segmented customers into **2 optimal clusters** using the silhouette score.
- **CV Validation**:
  - At **Sakon**, I analyzed **1,200+ customer accounts** to identify high-value segments.
  - Applied **unsupervised learning** to drive **targeted marketing and resource allocation**.

### **4. Business Impact = Retail & Marketing Applications**
- **Project**: Identified high-value customers and seasonal trends for strategic decision-making.
- **CV Validation**:
  - At **Mercedes-Benz**, I used **time-series models** to predict production data—showcasing my ability to **translate analytics into business insights**.

---

## **📊 Model Performance & Lessons**
| **Metric**               | **Score** | **Interpretation**                                                                 | **How I’d Improve It**                          |
|--------------------------|-----------|------------------------------------------------------------------------------------|------------------------------------------------|
| **Silhouette Score**     | 0.65      | Optimal number of clusters (2) achieved clear separation.                        | Experiment with **DBSCAN or hierarchical clustering**. |
| **Cluster Interpretation**| High      | Distinct segments (e.g., high-spenders vs. occasional buyers).                     | Add **RFM (Recency, Frequency, Monetary)** features. |
| **Seasonal Trends**      | Identified| Peaks in sales during specific months (e.g., holidays).                           | Integrate **external data** (e.g., promotions). |

**Key Takeaway**:
This project taught me how to **diagnose cluster quality** and **translate analytical results into actionable business strategies**—skills I’ve since applied at **Sakon** to optimize customer segmentation and marketing efforts.

---

## **🛠 How to Run This Project**
1. **Prerequisites**:
   - Python 3.8+
   - Libraries: `pandas`, `seaborn`, `matplotlib`, `scikit-learn`
     ```bash
     pip install pandas seaborn matplotlib scikit-learn
     ```

2. **Steps**:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans/notebooks
   jupyter notebook Customer_Segmentation.ipynb


Follow the notebook to preprocess data, train the K-Means model, and visualize results.

Expected Output:

Monthly sales trends and top products (EDA visualizations).
Silhouette score plot for optimal clusters.
Final customer segments saved in customer_clusters.csv.


🌟 Future Enhancements

Dynamic Clustering: Update segments regularly to reflect changing customer behavior.
Hybrid Models: Combine K-Means with supervised learning (e.g., classification) for deeper insights.
Deployment: Build a Streamlit dashboard for real-time customer segmentation.

📄 License
This project is open-source under the MIT License. Feel free to fork, modify, or build upon it!

---
For a visual walkthrough of the project outputs, check out the OutputSnaps folder—I’ve compiled chronologically arranged snapshots of all key visualizations and results for easy reference! 📸📂
---

