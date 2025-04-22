 Internet Usage Clustering
This project clusters users based on their daily internet usage patterns, including hours spent online, number of site categories visited, and sessions per day. The aim is to uncover behavioral patterns that can help with user profiling, personalization, or network optimization.

📌 Project Structure
bash
Copy
Edit
internet-usage-clustering/
│
├── internet_usage.csv            # Dataset with user internet activity
├── clustering_code.ipynb         # Jupyter notebook or Colab code
├── Screenshot.png                # Cluster visualization output
└── README.md                     # Project documentation (this file)
📖 Introduction
The dataset contains user activity logs based on:

Daily Usage Hours: Time spent online each day.

Site Categories Visited: Number of distinct types of websites accessed.

Sessions per Day: Number of separate browsing sessions initiated daily.

Using these features, KMeans clustering is applied to group users with similar usage behavior. The clusters are visualized using PCA for better interpretation.

🧠 Methodology
Data Preprocessing:

Load CSV dataset using pandas

Normalize features using StandardScaler

Clustering:

Apply KMeans clustering from scikit-learn

Append cluster labels to original dataset

Dimensionality Reduction & Visualization:

Reduce data to 2D using PCA

Plot user clusters using matplotlib

🧾 How to Run
Clone this repo or download the files.

Ensure Python is installed with the following packages:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib
Run the script in Jupyter Notebook or any Python IDE.

📷 Output
The output is a 2D plot visualizing clustered users, helping identify patterns in internet usage.


📚 References & Credits
Pandas for data handling: https://pandas.pydata.org

Scikit-learn for clustering and PCA: https://scikit-learn.org

Matplotlib for plotting: https://matplotlib.org

Dataset: Manually generated for academic purposes

Developed as part of a course or personal learning project on unsupervised learning and data analysis

