# Email Classification Project

This project implements a machine learning model for email classification using Python. The system is designed to automatically classify emails into different categories using natural language processing and machine learning techniques.

## Project Overview

The project uses a dataset of emails (`emails.csv`) containing various features extracted from email content. The classification model is implemented using scikit-learn and includes:

- Data preprocessing and feature analysis
- Implementation of multiple classification algorithms:
  - Multinomial Naive Bayes
  - Support Vector Machine (SVM)
- Model evaluation and performance metrics

## Dataset

The dataset includes:
- 5,172 email samples
- 3,002 features (including word frequencies and metadata)
- Binary classification (0 or 1)

## Requirements

The project requires Python 3.x and several data science libraries. See `requirements.txt` for detailed dependencies.

## Usage

1. Ensure all dependencies are installed:
```bash
pip install -r requirements.txt
```

2. Open and run the Jupyter notebook:
```bash
jupyter notebook Email_Classification.ipynb
```

## Technologies Used

- Python 3.x
- Pandas for data manipulation
- Scikit-learn for machine learning
- Seaborn and Matplotlib for visualization
- Jupyter Notebook for interactive development

## Results

The project implements and compares different classification algorithms, providing accuracy metrics and classification reports for model evaluation.

## License

This project is open source and available under the MIT License.