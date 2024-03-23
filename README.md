# Product_Substitute_Prediction
This project aims to predict whether a pair of products can be considered substitutes for each other. The dataset contains information about various product features, and the goal is to develop a machine learning model that can accurately classify pairs of products as substitutes or not substitutes. The model can be helpful for businesses in understanding customer preferences and behavior, particularly in scenarios such as product stocking and inventory management.

Dataset:
The dataset used for this project contains information about product features such as package quantity, dimensions, weight, etc., along with labels indicating whether each pair of products is considered substitutes or not.

Features:

Item package quantity
Item height
Item width
Item length
Item weight
Package height
Package width
Package length
Package weight
Target Variable:

Label: Indicates whether a pair of products is considered substitutes (binary classification)
Workflow:

Data Preprocessing:
Handle missing values
Encode categorical features
Scale numerical features if necessary
Exploratory Data Analysis:
Visualize distributions of features
Explore correlations between features
Feature Selection:
Select the most relevant features using techniques like SelectKBest
Model Building:
Train various classification models (e.g., K-Nearest Neighbors, Random Forest, Gradient Boosting)
Tune hyperparameters using techniques like grid search or randomized search
Model Evaluation:
Evaluate models using appropriate metrics (e.g., accuracy, precision, recall, F1-score)
Model Deployment:
Deploy the best-performing model for making predictions on new data
Tools and Libraries Used:

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Files Included:

data.csv: The dataset containing product features and labels
main.ipynb: Jupyter Notebook containing the main code for data preprocessing, model building, and evaluation
requirements.txt: File listing all the required Python libraries and their versions
README.md: Markdown file providing an overview of the project, instructions for running the code, and other relevant information
Instructions for Running the Code:

Clone the repository to your local machine.
Install the required Python libraries listed in requirements.txt.
Open main.ipynb in Jupyter Notebook or any other compatible environment.
Follow the instructions and execute the code cells sequentially to preprocess the data, build and evaluate the model.
Interpret the results and make any necessary modifications to the code as needed.
