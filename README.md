# Customer Segmentation using Clustering

## 📌 Project Overview

Customer segmentation is the practice of dividing a company's customers into groups that reflect similarity among customers in each group. This project uses **K-Means clustering** to segment customers based on features such as age, annual income, and spending score.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn (StandardScaler, KMeans, PCA)

## 📁 Dataset

**File:** `customer_data.csv`

Expected Columns:

* `CustomerID`: Unique ID for each customer
* `Age`: Age of the customer
* `Annual Income (k$)`: Income of the customer in thousand dollars
* `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## 🔄 Workflow

1. **Data Preprocessing:**

   * Load and inspect the data
   * Standardize features using `StandardScaler`

2. **Optimal Cluster Selection:**

   * Use the Elbow Method to find the optimal number of clusters

3. **Clustering with K-Means:**

   * Cluster the data into customer segments
   * Add cluster labels to the original dataset

4. **Dimensionality Reduction:**

   * Apply PCA for 2D visualization

5. **Visualization:**

   * Scatter plot of the customer segments using PCA components

6. **Export Results:**

   * Save the segmented data to `results/segmented_customers.csv`
   * Save plots to `results/elbow_plot.png` and `results/customer_segments.png`

## 📊 Outputs

* `results/segmented_customers.csv`: Contains customer data with assigned cluster labels
* `results/elbow_plot.png`: Elbow curve for determining optimal clusters
* `results/customer_segments.png`: Scatter plot of clusters in 2D space

## 💡 Insights

You can analyze the resulting clusters to:

* Tailor marketing strategies for each group
* Improve customer satisfaction
* Boost sales through targeted promotions

## 📌 How to Run

1. Ensure you have Python and required libraries installed (`pip install -r requirements.txt` if you have one).
2. Place `customer_data.csv` in the working directory.
3. Run the Python script.
4. Check the `results` folder for outputs.

---
