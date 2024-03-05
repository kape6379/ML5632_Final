# Unsupervised Machine Learning Final: Clustering Heart Disease Patient Data

This project will focus on data pertaining to heart disease in patients. This data is from the "V.A. Medical Center in Long Beach, CA" that I sourced through kaggle. The goal is to use unsupervised machine learning methods (clustering: hierarchical, kmeans, etc.) in order to see if we can see similarities among symptoms experienced by patients. 

There is a need for utilizing these kinds of methods in the medical world to potentially automate or assist doctors in effectively making diagnoses to patients. "Doctors and clinical experts can diagnose potential much earlier since ML algorithms provide real-time data and analysis. ML in healthcare allows professionals to automate many administrative duties to provide better patient care" [Need for ML in Healthcare](https://www.sciencedirect.com/science/article/pii/S2666603022000069).  

## Hierarchical Clustering

As a part of my exploratory analysis I will be applying hierarchical clustering on our processed data. The idea is that if we can identify clear clusters then it will show that symptoms clients face can be categorized and thus used to medically inform treatment options.

I am using hierarchical clustering due to the fact that there is a lot of room for me to choose and play around with different distance measures or linkage criteria. If I can show that subgroups can be identified in this data, then I will have considered it successful! In order to visualize if I've correclty identified subgroups, I will use PCA to reduce the dimensionality and thus plot our clusters. 

## Kmeans Clustering

 I will then compare our hierarchical model to a kmeans model in order to determine if there is a clustering method better suited for this issue. 

Being able to clearly distinguish similarities between symptoms of patients can lead to life-saving care. I aim to see if clustering is a good real world approach for hospitals to provide information to medical professionals to make informed decisions. Especially as we've seen unprecedented times and overwhelmed healthcare institutions this would be a crucial implementation to modernize the healthcare system.
