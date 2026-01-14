🏥 Healthcare Cost Prediction using Machine Learning 💰

A regression-based machine learning model built with TensorFlow 2.x and Keras to predict individual healthcare insurance expenses.

This project was completed as part of the freeCodeCamp Machine Learning with Python certification.

📌 Project Overview

The objective of this project is to predict healthcare insurance costs based on demographic and lifestyle features such as age, BMI, smoking habits, and region.
The model generalizes well on unseen data and achieves a Mean Absolute Error (MAE) well below the required threshold, successfully passing the freeCodeCamp challenge.

🧠 Model Highlights

Regression-based prediction of healthcare expenses

Neural network built with TensorFlow & Keras

Categorical data encoding (binary + one-hot)

Feature normalization using Keras preprocessing layers

Optimized to achieve MAE < 3500 on test data

🛠 Tech Stack

Python

TensorFlow / Keras

Pandas

NumPy

Matplotlib

Google Colab

📂 Dataset

The dataset is provided by freeCodeCamp and includes:

Age

Sex

Body Mass Index (BMI)

Number of children

Smoker status

Region

Insurance expenses (target variable)

The dataset is automatically downloaded and loaded within the Colab notebook.

⚙️ Data Preprocessing

Converted categorical variables (sex, smoker) into numeric format

Applied one-hot encoding for the region column

Split data into 80% training and 20% testing sets

Normalized numerical features for stable model training

🏗 Model Architecture

Input normalization layer

Two fully connected Dense layers with ReLU activation

Output layer with a single neuron for regression

Optimizer: Adam

Loss function: Mean Absolute Error (MAE)

🚀 How to Run the Project

Open the notebook in Google Colab

Run all cells from top to bottom

The notebook will:

Train the regression model

Evaluate performance on unseen test data

Plot predicted vs actual healthcare costs

📈 Results

Testing Mean Absolute Error: ~2082

Consistently predicts healthcare costs within an acceptable error range

Fully meets all freeCodeCamp project requirements

Example output:

Testing set Mean Abs Error: 2081.97 expenses  
You passed the challenge. Great job!

🎓 Certification

This project is part of the
freeCodeCamp – Machine Learning with Python Certification

📎 Notebook

You can run the project directly in Google Colab:

🔗 https://colab.research.google.com/drive/1SG4VQ0fDCSeh33uELgc8ZkOdRriYk6tE?usp=sharing

✨ Author

Built with iteration, debugging, and steady improvement.
If you’re reviewing this repository — thanks for stopping by and happy learning! 🚀
