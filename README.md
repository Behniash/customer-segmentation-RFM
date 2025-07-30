#  Customer Segmentation using RFM and K-Means Clustering

This project performs **customer segmentation** based on the **RFM (Recency, Frequency, Monetary)** model and applies **K-Means clustering** to group customers into meaningful segments. The analysis provides insights to identify **VIP, loyal, at-risk, and low-value customers**, which can help in designing effective marketing strategies.

---

##  Project Structure
| File | Description |
|------|------------|
| `rfm_segmentation.ipynb` | Main Jupyter Notebook containing data analysis, RFM calculation, clustering, and visualizations |
| `sales_data.csv` | Sample dataset containing sales transactions |
| `README.md` | Project description and documentation |

---

## Project Workflow
1 **Data Preprocessing** – Cleaning data, handling dates, and calculating sales & profit.  
2 **Exploratory Data Analysis (EDA)** – Understanding sales trends, top products, and category-wise performance.  
3 **RFM Calculation** – Computing Recency, Frequency, and Monetary values for each customer.  
4 **Scoring & Segmentation** – Assigning RFM scores and clustering customers using K-Means.  
5 **Cluster Evaluation** – Using the Elbow Method and Silhouette Score to determine optimal clusters.  
6 **Visualization** – Plotting customer clusters in 2D and 3D for better understanding.  
7 **Insights & Strategy** – Providing actionable marketing recommendations for each cluster.

---

##  Tech Stack
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Machine Learning**: scikit-learn (KMeans, clustering metrics)  
- **Visualization**: Matplotlib, Seaborn, 3D plots  

---

##  Results & Insights
- Customers are segmented into **5 clusters** based on RFM scores.
- Insights help to:
  - Identify **VIP customers** for loyalty rewards
  - Detect **at-risk customers** for re-engagement campaigns
  - Target **low-value customers** with promotions to increase sales

---

##  How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/إBehniash/customer-segmentation-RFM.git
2. Open the notebook:
    ```bash
    jupyter notebook rfm_segmentation.ipynb
3.Run the notebook step by step to reproduce the analysis.

Author:
behniashayeste@gmail.com




