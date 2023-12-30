Fake News Detection System
Overview
This project implements a Fake News Detection System using machine learning techniques in Python. The system is designed to classify news articles as either clickbait or non-clickbait based on the content. It includes the preprocessing of a dataset, training machine learning models, and a manual testing feature.

Prerequisites
Before running the code, make sure you have the following installed:
- Python (>=3.6)
- Jupyter Notebook
- Required Python libraries (pandas, numpy, scikit-learn, statsmodels)

Install the necessary libraries: 
pip install pandas numpy scikit-learn statsmodels

Project Structure
main.ipynb: Jupyter Notebook containing the project code.
fake.csv and true.csv: Datasets containing fake and true news articles.
manual_testing.csv: Dataset for manual testing.

Usage
Open and run the Jupyter Notebook main.ipynb using Jupyter Notebook.
Follow the code cells for data loading, preprocessing, model training, and testing.
The trained models include Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest classifiers.

Manual Testing
To manually test the system:
Input a news article when prompted in the last code cell of the notebook.
The system will predict whether the input news is likely to be clickbait or non-clickbait using the trained models.
Results
The notebook displays evaluation metrics such as accuracy, precision, recall, and log loss for each machine learning model. The Random Forest model achieved high accuracy, indicating effective fake news detection.

Contributors
Kezia Rijadi
Calista Aurelia

under the mentorship of Stefanus Setiawan.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project was inspired by the need for reliable fake news detection for Indonesian news outlets.
Special thanks to the mentor for this project for their guidance.
