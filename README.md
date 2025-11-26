# 🛍️ Customer Segmentation in Retail Business

## 📘 Overview
Customer segmentation in the retail business is vital for improving customer engagement and profitability.  
This project analyzes transactional data from **1/12/2010 to 9/12/2011** to identify different customer groups based on purchasing behavior.  
Segmentation helps businesses personalize marketing strategies, retain customers, and optimize revenue.

<img width="356" height="507" alt="image" src="https://github.com/user-attachments/assets/84528606-f622-466c-9574-6045e67ccc3e" />


---

## 🎯 Objectives
- Analyze historical customer transactions to understand spending patterns.  
- Segment customers using analytical and machine learning techniques.  
- Derive actionable insights to guide targeted marketing and promotions.

---

## 🗂️ Project Files
- Online_Retail.csv -> CSV file containing more than 5 lacs transactions between 1st December 2010 and 9th December 2011 for a UK-based online retailer
- Jupyter notebook -> Jupyter file containg clean and commented code
- Report 1: Applications of Data Science in E-Commerce -> Report on how data science can be useful in E-Commerce market
- Report 2: Final Report -> Insights of the analysis and recommendations for the company

---


## 🧠 Steps Included
1. Importing and understanding the dataset  
2. Data cleaning and preprocessing  
3. Exploratory data analysis (EDA)  
4. Feature engineering for customer behavior  
5. Applying clustering algorithms for segmentation  
6. Visualizing and interpreting results

---

## 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - warnings (for suppressing runtime warnings)

---

## 📊 Dataset Information
**Dataset:** Online Retail Dataset  
**Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)  

- Contains all 541,909 transactions between **1st December 2010** and **9th December 2011** for a UK-based online retailer.  
- Each row represents a unique product purchase by a customer.  
- Key columns:  
  - `InvoiceNo` – Invoice number  
  - `StockCode` – Product code  
  - `Description` – Product name  
  - `Quantity` – Number of products purchased  
  - `InvoiceDate` – Date of purchase  
  - `UnitPrice` – Price per unit  
  - `CustomerID` – Unique ID per customer  
  - `Country` – Customer location  

---

## 🧩 Methodology

### 1. Data Cleaning
- Removed missing customer IDs and invalid transactions.  
- Filtered out canceled orders.  
- Handled outliers in `Quantity` and `UnitPrice`.

### 2. Exploratory Data Analysis
- Analyzed customer purchasing frequency and total revenue.  
- Identified top-performing products and countries.

### 3. Feature Engineering
- Created **RFM (Recency, Frequency, Monetary)** metrics.  
- Normalized RFM values for clustering.

  <img width="1400" height="738" alt="image" src="https://github.com/user-attachments/assets/6193011f-65f9-460d-9e39-e21b4f2e732f" />


### 4. Clustering
- Applied **K-Means** clustering to segment customers.  
- Determined the optimal number of clusters using the **Elbow Method**.

  <img width="492" height="341" alt="image" src="https://github.com/user-attachments/assets/e9389df9-a0a7-4b9c-914f-2b07440a1826" />


### 5. Visualization
- Plotted customer segments to interpret behaviors.  
- Compared average RFM scores across segments.

---

## 🧾 Results and Insights
- The K-Means algorithm grouped customers into 4 segments:
  - **Cluster 0:** High-spending loyal customers  
  - **Cluster 1:** Medium-frequency, average spenders  
  - **Cluster 2:** Low-value one-time buyers  
  - **Cluster 3:** Inactive or lost customers  
- The **Elbow Method** suggested 4 as the optimal number of clusters.
- Average Recency, Frequency, and Monetary scores were highest for Cluster 0.

---

## 📊 Visualizations
Elbow curve for optimal K value

<img width="472" height="468" alt="image" src="https://github.com/user-attachments/assets/5133d054-9693-45b8-adb6-ebf1bf1fae9b" />

Segments Plot

<img width="472" height="463" alt="image" src="https://github.com/user-attachments/assets/593423d0-dd95-4083-92fc-4be86b7d6fcf" />

--

## 💡 Future Improvements
- Implement advanced clustering methods (DBSCAN, hierarchical).  
- Integrate real-time customer segmentation.  
- Build a dashboard for live customer tracking.

---

## 🤝 Contributing
Contributions are welcome!  
To contribute:
1. Fork this repository  
2. Create a new branch (`feature-branch-name`)  
3. Commit your changes  
4. Open a Pull Request

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail) for providing the dataset.  
- Open-source contributors for Python libraries used in this project.

---
