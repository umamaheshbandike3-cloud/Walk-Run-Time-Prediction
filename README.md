Walk vs Run Classification using Machine Learning & Deep Learning

This project focuses on building a predictive system to classify human physical activity as Walking or Running using motion sensor data. The model leverages accelerometer and gyroscope readings to understand body movement patterns and accurately detect activity type.

📌 Project Objective

To develop a reliable classification model that can determine whether a person is walking or running based on wearable sensor data. This has applications in fitness tracking, health monitoring, sports analytics, and activity recognition systems.

📊 Dataset Description

The dataset contains time-series sensor data collected from motion devices, including:

Accelerometer readings (movement and force)

Gyroscope readings (rotation and orientation)

Data captured from different body positions during walking and running activities

These signals are used as input features for training machine learning and deep learning models.

🛠️ Tech Stack

Programming Language: Python

Libraries:

Pandas, NumPy (Data Processing)

Matplotlib, Seaborn (Visualization)

Scikit-learn (Machine Learning Models)

TensorFlow / Keras (LSTM Model)

🔍 Project Workflow

Data Understanding & Cleaning

Checked missing values and data consistency

Performed basic statistical analysis

Exploratory Data Analysis (EDA)

Visualized sensor patterns for walking vs running

Analyzed feature distributions and correlations

Feature Engineering

Processed accelerometer and gyroscope signals

Scaled and prepared features for modeling

Model Building

Trained multiple Machine Learning models

Built a Deep Learning LSTM model for time-series sequence learning

Model Evaluation

Evaluated using:

Accuracy

Confusion Matrix

Classification Metrics (Precision, Recall, F1-score)

🤖 Models Used

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Decision Tree

Random Forest

XGBoost

LSTM (Long Short-Term Memory) – Deep Learning model for sequence data

📈 Results

The models were compared based on classification performance, and the best-performing model was selected for accurate activity prediction. The deep learning LSTM model effectively captured time-based motion patterns, improving activity recognition performance.

🚀 How to Run the Project

Clone the repository

git clone https://github.com/your-username/your-repo-name.git


Install required libraries

pip install -r requirements.txt


Open the Jupyter Notebook

jupyter notebook


Run WalkRun Project.ipynb step by step

🌟 Future Improvements

Deploy the model as a real-time activity detection app

Use advanced deep learning architectures (GRU, CNN-LSTM)

Integrate with wearable or mobile sensor data streams

👨‍💻 Author

Mahesh
Machine Learning & Data Science Enthusiast
