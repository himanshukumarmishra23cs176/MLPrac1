Iris Dataset Classification using k-NN

Implemented a k-Nearest Neighbors (k-NN) classifier on the Iris dataset to classify iris species (setosa, versicolor, virginica) based on four features:

Sepal length
Sepal width
Petal length
Petal width

Key Tasks Completed:
1. Load and explore the Iris dataset
2. Visualize features using pairplots, heatmaps representing correlation values and box plots.
3. Train and test a KNN classifier
4. Connect distance-based learning to vector space
5. Relate classification results to class probabilities
6. Split data into training/testing
7. Train a K-Nearest Neighbors (KNN) model
8. Test with different k values (1, 3, 5, 7)

Key Results
k	Avg. CV Accuracy	Precision	Recall	F1-Score
1	0.96	0.96	0.96	0.96
3	0.966	0.967	0.966	0.966
5	0.966	0.967	0.966	0.966
7	0.953	0.953	0.953	0.953
Best Model: k=3 or k=5 (96.7% accuracy)

Libraries Used: scikit-learn, pandas, matplotlib, seaborn

Data Split: 70% training, 30% testing (stratified)

Distance Metric: Euclidean (L2)

Evaluation: 5-fold CV + test set metrics

Key Learnings
1. Load and explore the Iris dataset
2. Visualize features using pairplots
3. Train and test a KNN classifier
4. Connect distance-based learning to vector space
5. Relate classification results to class probabilities

