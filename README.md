# Predicting Mental Health Disorders Using Smart Watch Data
This project aims to predict mental health disorders by analyzing data collected from smart watches, including heart rate, sleep patterns, and activity levels. The goal is to develop machine learning models that can help identify individuals at risk of mental health issues based on their physiological data.

## Data
We use two primary datasets for this project:
- Smartwatch Data: Contains data on heart rate, activity levels, and sleep patterns. [Kaggle](https://www.kaggle.com/shubhendra19/smartwatch-data)
- Mental Health and Smart Watch Data: Combines mental health survey data with smart watch data. [Kaggle](https://www.kaggle.com/surajjha101/mental-health-and-smart-watch-data)

## Project Structure
The project is organized as follows:

mental-health-smartwatch/
├── data/                   # Data files
│   ├── smartwatch_data.csv
│   ├── mental_health_data.csv
├── notebooks/              # Jupyter notebooks
│   ├── data_analysis.ipynb
│   ├── model_training.ipynb
├── src/                    # Python scripts
│   ├── data_preparation.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   ├── model_evaluation.py
├── README.md               # Project documentation
├── requirements.txt        # Required packages

## Installation
To run this project, you need to have Python installed. You can install the required packages using the following command:
```bash
pip install -r requirements.txt

Usage

 1. Data Preparation:
 • Ensure the data files are placed in the data/ directory.
 • Use the data_preparation.py script to clean and preprocess the data.

python src/data_preparation.py


 2. Feature Engineering:
 • Generate new features from the cleaned data using the feature_engineering.py script.

python src/feature_engineering.py


 3. Model Training:
 • Train the machine learning models using the model_training.py script.

python src/model_training.py


 4. Model Evaluation:
 • Evaluate the trained models using the model_evaluation.py script.

python src/model_evaluation.py



Goals

 • Develop a machine learning model to predict mental health disorders.
 • Use physiological data from smart watches to improve mental health diagnostics.

Contributors

Feel free to contribute to this project by creating issues, suggesting improvements, or submitting pull requests.

License

This project is licensed under the MIT License - see the LICENSE file for details.
