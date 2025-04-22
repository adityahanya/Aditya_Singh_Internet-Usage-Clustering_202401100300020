# Internet-Usage-Clustering
🌐 Internet Usage Clustering
This project uses unsupervised machine learning to cluster internet users based on their activity patterns, including daily usage hours, session frequency, and site categories visited. The goal is to group users into distinct behavioral segments for better understanding and analysis.

🔍 Problem Statement
With the increasing variety in how people use the internet, it's important to understand different usage behaviors. This project clusters users based on usage features to reveal patterns such as heavy users, casual browsers, or balanced users.

🎯 Objectives
Preprocess and standardize usage data.

Apply K-Means clustering to group similar users.

Visualize cluster separation using scatter plots.

Evaluate clustering using silhouette score and other metrics.

Interpret cluster centers to describe user types.

⚙️ Tools & Libraries
Python

pandas, NumPy – Data handling

scikit-learn – Clustering and evaluation

matplotlib, seaborn – Visualization

📁 Dataset Features
daily_usage_hours – Average time spent online daily

sessions_per_day – Number of internet sessions

site_categories_visited – Count of site category types accessed

📊 Approach
Standardize features using StandardScaler.

Apply KMeans with 3 clusters (adjustable via elbow method).

Visualize results using 2D scatter plots (daily usage vs. sessions).

Evaluate model using:

Silhouette Score

Calinski-Harabasz Index

Davies-Bouldin Score

Interpret cluster centers in original scale to define behavior types.

✅ Outcome
Users were successfully grouped into three meaningful clusters. Visualization confirmed clear separation, and evaluation scores validated the model’s performance. The project offers insights for profiling, targeted services, and network optimization.

