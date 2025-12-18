# FYS-STK4155-Project3

## Group members: 
Viktor Bilstad

## Project description
The main objective for this project is to use machine learning methods to analyse a dataset. The dataset in question is a table consisting of 4898 unique white wines and their features. Of these, 11 is physiochemical, while 1 is a quality score. Neural networks and XGBoost were used for classification and reggression tasks. These methods were compared to each other and also to literature. A SHAP analysis was also performed on the XGBoost predictions. This allowed for better understanding of each feature. What makes a wine get a good score? What features have a high impact and what features does not matter as much? These are some of thequestions answered in the project.

## Structure
The coding folder consist of two main files:

In "Regression_Wine" a regression analysis by XGBoost and then by FeedForward Neural Network (FFNN) is performed. All plots related to regression is made from that file.

In "Classification_Wine" a classification analysis by XGBoost and FFNN is performed. Both binary and multi-class analysis is conducted. Also, the code for SHAP analysis is contained here. By changing parameters, all figures stemming from XGBoos classification and SHAP can be made from this file. 

How to run the code:
1. Set up a python virtual environment

2. Install packages:

3. pip install -r requirements.txt

4. Run .ipynb files described above.
