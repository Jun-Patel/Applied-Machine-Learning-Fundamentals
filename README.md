# Applied-Machine-Learning-Fundamentals
A complete guide to my learning and exploration of common ML concepts + libraries + methods. The idea is to work through the fundamentals and then experiment with various libraries, model-tuning, variable optimization, etc to fully explore ML concepts. Some of this was taken from undegraduate Machine Learning Courses during my studies.

## What this repository contains

There are two groups of notebooks in this portfolio:

1. **Nine ML fundamentals notebooks** created as a structured study-and-portfolio series.
2. **Five larger example notebooks** that show applied projects in recommendation systems, trading strategy comparison, and wine-quality modeling.

---

## Part I — ML Fundamentals Series

### 1. `01_linear_regression_california_housing.ipynb`
**Topic:** Linear Regression  
**Problem:** Predict median house value using the California Housing dataset.  
**What it shows:** End-to-end regression workflow, correlation analysis, residual analysis, coefficient interpretation, and a selected-feature retraining experiment.

### 2. `02_logistic_regression_breast_cancer.ipynb`
**Topic:** Logistic Regression  
**Problem:** Classify tumors as malignant or benign.  
**What it shows:** Binary classification workflow, class-balance inspection, feature scaling, multiple classification metrics, confusion matrix analysis, and retraining with selected features.

### 3. `03_feature_engineering_preprocessing.ipynb`
**Topic:** Feature Engineering and Preprocessing  
**Problem:** Build a mixed-type regression pipeline on housing data.  
**What it shows:** Missing-value handling, numeric/categorical preprocessing, sklearn pipelines, leakage prevention, and feature-set refinement.

### 4. `04_model_evaluation_cross_validation.ipynb`
**Topic:** Model Evaluation and Cross-Validation  
**Problem:** Compare several wine classifiers fairly.  
**What it shows:** Holdout evaluation, cross-validation, model comparison discipline, and feature-subset reranking.

### 5. `05_tree_models_random_forests.ipynb`
**Topic:** Tree Models and Ensembles  
**Problem:** Compare a decision tree with a random forest.  
**What it shows:** Tree interpretability, ensemble stability, train/test gap analysis, feature importance, and reduced-feature retraining.

### 6. `06_unsupervised_clustering_kmeans.ipynb`
**Topic:** Unsupervised Learning  
**Problem:** Cluster Iris observations with K-Means and DBSCAN.  
**What it shows:** Feature scaling for clustering, silhouette score interpretation, PCA-based visualization, and heuristic feature-subset refinement.

### 7. `07_pca_dimensionality_reduction.ipynb`
**Topic:** Dimensionality Reduction with PCA  
**Problem:** Compress the digits dataset and analyze explained variance.  
**What it shows:** Standardization, principal components, 2D visualization, variance retention, and PCA behavior under a smaller original feature set.

### 8. `08_text_classification_tfidf.ipynb`
**Topic:** NLP / Text Classification  
**Problem:** Classify two newsgroup categories using TF-IDF and logistic regression.  
**What it shows:** Sparse feature engineering for text, classification evaluation, and a vectorizer-refinement experiment that behaves like text feature selection.

### 9. `09_cnn_image_classification_mnist.ipynb`
**Topic:** Deep Learning / CNNs  
**Problem:** Classify MNIST digits with a small convolutional neural network.  
**What it shows:** PyTorch image pipeline, batching, model definition, training loop, evaluation loop, and a light refinement step.

---

## Part II — Additional Applied Project Notebooks

### 10. `Recommendation_System_Project.ipynb`
**Topic:** Recommendation Systems  
**Summary:** A book recommendation project that uses collaborative filtering approaches with the Surprise library. The notebook focuses on user–item ratings, recommendation logic, and evaluating recommender-system methods on rating data.

### 11. `Stock_Trading_Strategy_Comparison_Buy_and_Hold_vs_SMA_Crossover_with_AAPL.ipynb`
**Topic:** Quant / Trading Strategy Comparison  
**Summary:** A strategy-comparison notebook that contrasts a passive buy-and-hold approach with a simple moving-average crossover strategy on AAPL stock data. The project includes historical market data collection, strategy logic, and performance comparison.

### 12. `Red_Wine_Quality_Prediction_A_Comparative_Study_of_ML_Classification_Models.ipynb`
**Topic:** Classification Model Comparison  
**Summary:** A red-wine quality project that compares multiple classification models on physicochemical wine features. The notebook emphasizes data exploration, modeling, and comparative evaluation across classifiers.

### 13. `White_Wine_Quality_Prediction_Application_of_ML_Model_Hypertuning.ipynb`
**Topic:** Regression / Model Tuning  
**Summary:** A white-wine quality project built around regression modeling and hyperparameter tuning. The notebook includes data loading, exploratory analysis, model training, and tuning-oriented comparison.

### 14. `Investigating_KMeans_Clustering.ipynb`
**Topic:** Unsupervised Learning / Clustering  
**Summary:** An exploratory analysis of K-Means clustering used to identify natural groupings within a dataset. The notebook walks through data preparation, cluster training, visualization, and evaluation of cluster structure using techniques such as the elbow method and cluster interpretation.

---

## Design philosophy of this portfolio

The notebooks in this repository are intentionally written in a **clear, explicit style**:
- every major code cell is framed by markdown
- each notebook includes introduction, goal, concepts, and final analysis
- model refinement is included where appropriate
- the emphasis is on both **learning** and **professional presentation**

---

## Skills demonstrated across the repository

- supervised learning
- regression and classification
- preprocessing pipelines
- model comparison and cross-validation
- tree ensembles
- clustering and dimensionality reduction
- text vectorization and NLP baselines
- deep learning with PyTorch
- recommendation systems
- basic quantitative strategy analysis
