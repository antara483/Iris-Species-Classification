🌸 Iris Species Classification using K-Nearest Neighbors (KNN)

This project classifies iris flowers into three species — Setosa, Versicolor, and Virginica — using the K-Nearest Neighbors (KNN) algorithm.
The project also includes data preprocessing, model evaluation, and a visualization of KNN decision boundaries.

📘 Dataset

The Iris dataset is one of the most famous datasets in machine learning, containing 150 samples of iris flowers with 4 features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Each sample belongs to one of three species:

Iris setosa

Iris versicolor

Iris virginica

⚙️ Project Workflow

Loaded the Iris dataset using sklearn.datasets

Explored and cleaned the dataset (removed duplicates)

Standardized features using StandardScaler

Trained a KNN model (n_neighbors=5)

Evaluated performance using:

Accuracy score

Confusion matrix

Classification report

Visualized:

Decision boundaries

K-value vs Accuracy curve

Understanding the bias-variance tradeoff using K vs Accuracy plot

