# Customer Segmentation using Unsupervised Learning (PCA + KMeans)

## 📌 Problem Statement
This project focuses on developing a **customer segmentation model** to identify distinct groups of customers based on their purchasing behavior. The primary goal is to help businesses **personalize marketing strategies**, improve **customer retention**, and **increase sales** by understanding their customer base better.

---

## 📊 Dataset
- **Source:** Customer transaction dataset containing demographics, purchase history, and frequency of visits.  
- **Features:** Age, gender, purchase amount, number of visits, and other behavioral indicators.  
- **Target:** No predefined labels (unsupervised learning problem).  

---

## ⚙️ Data Preprocessing
- Handled **missing values** and ensured **data consistency**.  
- **Encoded categorical variables** into numerical form.  
- Standardized features using **StandardScaler** to normalize ranges.  
- Performed **Exploratory Data Analysis (EDA)** to detect patterns, trends, and outliers.  

---

## 🔍 Dimensionality Reduction with PCA
- Applied **Principal Component Analysis (PCA)** to reduce data dimensionality.  
- Retained key components explaining **95% of the variance**.  
- Improved visualization of high-dimensional data for better interpretation.  

**Theory – PCA:**  
Principal Component Analysis is a statistical method used to transform high-dimensional data into a smaller set of uncorrelated variables called *principal components*, which capture most of the variance in the data. This helps in reducing noise, speeding up computations, and making data visualization easier.

---

## 🤖 Clustering
- Used **KMeans clustering** to group customers based on purchasing patterns.  
- Determined the optimal number of clusters using:
  - **Elbow Method**
  - **Silhouette Score**  
- Assigned each customer to a specific segment for targeted analysis.  

**Theory – KMeans:**  
KMeans is an iterative clustering algorithm that partitions data into **K** clusters. It works by:
1. Choosing K initial centroids.
2. Assigning each data point to the nearest centroid.
3. Recomputing centroids as the mean of assigned points.
4. Repeating until assignments stabilize.

---

## 📈 Visualization & Insights
- Visualized clusters using **Matplotlib** and **Seaborn**.  
- Identified unique customer segments such as:
  - High-value frequent buyers
  - Price-sensitive occasional shoppers
  - New customers with growth potential  
- Provided actionable insights to guide marketing campaigns.  

---

## 📊 Model Evaluation
- Evaluated segmentation quality using **Silhouette Score**.
- Compared different cluster counts for optimal grouping.  

---

## 💡 Business Impact
- Enabled **targeted marketing campaigns** for each customer group.  
- Improved **customer engagement** by offering personalized promotions.  
- Helped optimize **product recommendations** and pricing strategies.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `ml-2 proj.ipynb` and execute the cells.

---

## 📚 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn)
- **Matplotlib**, **Seaborn** for visualization
- **Jupyter Notebook** for development
