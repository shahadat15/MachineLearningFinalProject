# MachineLearningFinalProject


The main o objective this project is to develop a prediction model utilizing a
combination of supervised and unsupervised learning algorithms for the
categorization of the traffic states (i.e., congestion level). The developed model is
able to predict traffic congestion ahead of time for a specific time horizon. Traffic
sensor data such as speed, volume, and occupancy are used to develop the prediction
model. A k-means algorithm is used first to produce the clusters for traffic state
identification. These clusters are then used as labels to train multiple classifiers that
allows the traffic state identification for a given set of features. Finally, the
classification models are evaluated under different metrics to determine which
algorithm performs better in terms of accuracy for real-time prediction.
