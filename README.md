# Clustering

-- The main goal of this project is to cluster the students based on their performance and identify the low performing students and train them to perform better.
-- The dataset is a real time dataset of the students in our college.

The steps performed in this project are:
 
1.	KMeans clustering(hard) by considering only 3 exams(features) and identify the better number of clusters  and cluster quality using the metric Davies Bouldin Index.

2.	Check if the clustering quality is improved by taking 4 exams and also with 5 exams as features.

3.	Fuzzy C- Means (soft) clustering by considering only 3 exams( features) and identify the better number of clusters  and cluster quality using the metric Davies Bouldin Index.

4.	Check if the clustering quality is improved by adding one more exam as a feature.

5.	Selecting the best number of features and best number of clusters

6.	Hardening the Fuzzy clustering and compare it with the K-Means clustering (with the best clusters and features selected in step 5)
