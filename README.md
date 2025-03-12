# Customer Segmentation Using K-Means Clustering

📌 Overview
This project demonstrates Customer Segmentation using K-Means Clustering, a popular unsupervised machine learning algorithm. The segmentation is based on three key attributes:

✔️ Age
✔️ Annual Income (in k$)
✔️ Spending Score (1-100)

By analyzing these factors, the model categorizes customers into distinct groups, helping businesses understand their audience and optimize marketing strategies.

🔍 Dataset
    The dataset consists of customer information with the following five columns:
      ○  Age: Average age of customers in each cluster
      ○  Annual Income: Customers’ yearly income in thousands of dollars
      ○ Spending Score: Score assigned based on customer spending behavior

📊 Clustering Results
The K-Means algorithm identifies five distinct customer segments:

Cluster	Avg. Age	Avg. Annual Income (k$)	Avg. Spending Score	No. of Customers
0	45.55	55.21	49.13	53
1	32.67	87.52	81.55	33
2	41.18	82.96	18.71	28
3	23.91	29.65	71.57	23
4	46.08	26.23	12.23	13
Each segment has distinct characteristics, helping businesses tailor personalized offers, marketing campaigns, and product recommendations.

🛠 Technologies & Libraries Used:
    This project is implemented using the following technologies and libraries:
    ○ Programming Language: Python
    ○ Development Environment: Jupyter Notebook
    ○ Libraries Used:
      ▹ NumPy – For numerical computations
      ▹ Pandas – For data manipulation and analysis
      ▹ Matplotlib – For data visualization
      ▹ Seaborn – For statistical data visualization
      ▹ mpl_toolkits.mplot3d (Axes3D) – For 3D data visualization
      ▹ Warnings Module – To suppress unnecessary warnings

🚀 How to Run the Project
  1. Clone the repository:
      git clone https://github.com/your-username/Customer-Segmentation-KMeans.git
     
      cd Customer-Segmentation-KMeans
  3. Install dependencies:
    pip install -r requirements.txt

  4. Run the Jupyter Notebook:
    jupyter notebook Customer_Segmentation_Using_K-Means_Clustering.ipynb

📈 Applications:
    ○ Identifying high-value customers for premium offers
    ○ Recognizing low-spending customers to improve retention strategies
    ○ Customizing marketing campaigns based on customer spending habits
    ○ Enhancing customer experience through personalized services
