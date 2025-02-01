# Predicting Hospital Readmissions for Diabetic Patients

## Project Overview
This project focuses on predicting the likelihood of readmission for patients diagnosed with diabetes within 30 days of initial hospital discharge. Using historical data from 130 U.S. hospitals and clinics from 1999-2008, we aim to develop a machine learning model to help healthcare providers reduce readmission rates, which is a key indicator of quality of care and incurs significant costs.

## Repository Contents
- `Diabetic_Patients_Readmission_code.ipynb`: Jupyter notebook containing the exploratory data analysis, preprocessing, model training, and evaluation.
- `data/`: Directory containing the dataset `diabetic_data.csv` and the ID mappings `IDs_mapping.csv`.
- `requirements.txt`: List of packages required to run the notebook.
- `README.md`: This file, explaining the project and repository structure.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You need to have Python installed on your machine (preferably Python 3.8 or newer). Additionally, you will need several Python packages which are listed in `requirements.txt`.

### Installing
To install the required Python packages, run the following command in your terminal:


### Running the Notebook
To run the Jupyter notebook:
1. Open your terminal.
2. Navigate to the project directory.
3. Run Jupyter Notebook or Jupyter Lab


4. Or open `Diabetic_Patients_Readmission_code.ipynb` from the Jupyter interface.

## Built With
- [Python](https://www.python.org/) - The programming language used.
- [Pandas](https://pandas.pydata.org/) - Library for data manipulation and analysis.
- [Scikit-Learn](https://scikit-learn.org/stable/) - Library for machine learning and predictive data analysis.
- [Matplotlib](https://matplotlib.org/) - Library for creating static, interactive, and animated visualizations in Python.

## Results

### Model Performance
The project explored various machine learning algorithms to predict the likelihood of readmission within 30 days among diabetic patients. Models such as Logistic Regression, Random Forest, and Gradient Boosting were evaluated based on their accuracy and AUC scores. The best-performing model was the Gradient Boosting Classifier, which achieved an accuracy of approximately 85% and an AUC score of 0.75 on the test set. These metrics indicate a strong model performance, especially in distinguishing between patients who were and were not readmitted.

### Key Insights
- **Feature Importance:** The analysis revealed that features such as the number of inpatient visits in the previous year, the number of medications changed during the stay, and the length of hospital stay were among the most predictive of readmission. This insight can assist healthcare providers in focusing their efforts on these areas to potentially reduce readmission rates.
- **Model Limitations:** Despite robust performance, the model's predictive power could be limited by the inherent biases and variability in the dataset, such as imbalanced classes and potential underreporting of certain clinical conditions.
- **Future Work:** To enhance the model’s accuracy, future work could explore more sophisticated ensemble techniques and deep learning models. Additionally, incorporating more granular data, such as detailed lab results and patient notes, could improve predictive capabilities.

## Conclusion
This project demonstrates the potential of machine learning in transforming healthcare operations by predicting patient outcomes. By accurately identifying patients at risk of readmission, healthcare providers can allocate resources more effectively, improving patient care and reducing unnecessary costs. Continued research and integration of more comprehensive data can further enhance the predictive accuracy and utility of these models in clinical settings.

## Author
- **Sakshi Jadhav** - [Sakshi-N-Jadhav](https://github.com/Sakshi-N-Jadhav)
