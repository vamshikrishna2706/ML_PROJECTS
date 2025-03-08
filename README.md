#  Customer Segmentation using K-Means Clustering  

##  Overview  
Customer segmentation is an essential technique in marketing that helps businesses identify different groups of customers based on their behavior. This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers based on their shopping patterns.

##  Dataset  
- **Dataset Name**: Mall Customers Dataset  
- **Columns Used**: Customer ID, Gender, Age, Annual Income (k$), Spending Score (1-100)  
- **Source**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)  

##  Tech Stack  
- **Python** (Google Colab)  
- **Pandas, NumPy** (Data Processing)  
- **Matplotlib, Seaborn** (Visualization)  
- **Scikit-learn** (Machine Learning)  

##  Project Workflow  
1. **Data Preprocessing**: Cleaned and prepared the dataset.  
2. **Exploratory Data Analysis (EDA)**: Used **Seaborn & Matplotlib** to visualize customer distributions.  
3. **Finding the Optimal Clusters**:  
   - Used **Elbow Method** to find the best `k` value.  
   - Evaluated using **Silhouette Score** (achieved **0.55**).  
4. **Applying K-Means Clustering**: Grouped customers into meaningful segments.  
5. **Result Visualization**: Used **2D & 3D PCA plots** to display the clustered data.  

##  Key Results  
- The **best number of clusters (k)** was found using the **Elbow Method**.  
- Achieved a **Silhouette Score of 0.5539**, indicating a well-defined clustering structure.  
- Identified **3-5 customer groups** based on income and spending behavior.  

##  Visualizations  
Here are some key visualizations from the project:  

- **Elbow Method to Find Optimal K**  
![Elbow Method](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Elbow_Method.png/640px-Elbow_Method.png)  

- **Cluster Visualization**  
![Cluster Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Kmeans-pca.png/640px-Kmeans-pca.png)  

##  How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/vamshikrishna2706/ML_PROJECTS.git
