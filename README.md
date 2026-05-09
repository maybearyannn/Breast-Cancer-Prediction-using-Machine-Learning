# Breast-Cancer-Prediction-using-Machine-Learning
A machine learning project to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on cell nucleus features extracted from breast tissue images.

# 📌 Project Objective

The goal of this project is to leverage machine learning techniques to assist in the early detection and classification of breast tumors, aiding in timely diagnosis and treatment decisions. The model analyzes features derived from digitized images of fine needle aspirates (FNA) of breast masses.

# 📂 Dataset & Features

I have used the Wisconsin Breast Cancer Dataset (WBCD), which includes:

Diagnosis:

M = Malignant
B = Benign
Features (10 real-valued features for each cell nucleus):

Radius: Mean distance from center to points on the perimeter
Texture: Standard deviation of gray-scale values
Perimeter
Smoothness
Compactness: (area/perimeter - 1.0)
Concavity
Concave points
Symmetry
Fractal dimension
# 🧠 Machine Learning Pipeline

# 1. Data Collection & Preprocessing

Handled missing values and outliers
Normalized numerical features
Encoded categorical values
Applied dimensionality reduction using PCA
# 2. Feature Engineering

Selected important biological and clinical features
Collaborated with medical domain knowledge for insights
# 3. Model Selection & Training

Used binary classification algorithms like:
Logistic Regression
Support Vector Machine (SVM)
Decision Tree
Random Forest
Neural Networks
Tuned hyperparameters and used cross-validation
# 4. Evaluation Metrics

Accuracy
Precision
Recall (Sensitivity)
F1-Score
AUC-ROC
Confusion Matrix analysis
# 5. Model Deployment (Planned)

The model will be packaged into a deployable format for healthcare integration
Planned GUI/web interface for ease of access by radiologists and clinicians
# 📊 Results (Cross-Validation)

Employed k-Fold Cross Validation (k=5,10)
Achieved strong performance across all metrics
Compared against baseline models and validated externally for robustness
# ⚠️ Limitations

Potential data imbalance and demographic bias
Interpretability concerns with complex models
Limited sample size from the dataset
Need for real-world clinical validation
Ethical considerations (privacy, fairness, trust)



Hope you find it useful!

Aryan Prakash 
Yesaryan15@gmail.com
