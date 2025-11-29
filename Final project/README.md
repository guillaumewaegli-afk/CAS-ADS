## Abstract

Sports watches today collect extensive data from training sessions, enabling athletes to monitor performance and even receive predictive race times. However, a lot of existing predictors are limited to standard distances and fail to account for other factors like elevation or individual variability. This project aims to address these shortcomings by developing a mini-application capable of estimating personalized race times using past activity data combined with specific race parameters. The solution leverages supervised machine learning techniques, employing regression models such as Linear Regression, Random Forest, TensorFlow, and XGBoost to capture relationships between distance, speed, elevation, and other recorded variables.
The initial dataset consists of over 170 sessions recorded by a Garmin Descent watch, with more than 100 characteristics per run. Data preprocessing and analysis will be performed in Python using libraries such as Pandas, NumPy, and scikit-learn, followed by model training and validation. A graphical interface will allow users to input race details and visualize predictions alongside personalized statistics. In a second phase, the project will explore extending predictions to datasets from multiple athletes, raising challenges of generalizability and data consent.

## Goal of the project

The main objective of this work will be to create a mini application that, based on training data as well as the parameters of an upcoming race, can estimate a potential run time.
