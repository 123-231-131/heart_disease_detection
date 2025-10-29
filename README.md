# Heart Disease Detection

This repository contains a simple machine learning workflow for predicting the presence of heart disease from clinical measurements using logistic regression. The workflow is implemented in the `Untitled.ipynb` notebook and trains a baseline model on the included dataset.

## Dataset

The dataset is provided in `heart_data.csv`. It is a tabular collection of patient records with the following columns:

| Column      | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `age`       | Age of the patient in years.                                                |
| `sex`       | Sex of the patient (`1` = male, `0` = female).                              |
| `cp`        | Chest pain type (categorical values 0–3).                                  |
| `trestbps`  | Resting blood pressure (mm Hg).                                             |
| `chol`      | Serum cholesterol (mg/dl).                                                  |
| `fbs`       | Fasting blood sugar > 120 mg/dl (`1` = true, `0` = false).                  |
| `restecg`   | Resting electrocardiographic results (categorical).                         |
| `thalach`   | Maximum heart rate achieved.                                                |
| `exang`     | Exercise-induced angina (`1` = yes, `0` = no).                              |
| `oldpeak`   | ST depression induced by exercise relative to rest.                         |
| `slope`     | Slope of the peak exercise ST segment.                                      |
| `ca`        | Number of major vessels (0–4) colored by fluoroscopy.                    |
| `thal`      | Thalassemia status (categorical).                                           |
| `target`    | Presence of heart disease (`1` = disease, `0` = no disease).                |

The dataset originates from the UCI Heart Disease dataset and is widely used for classification practice. It is included here for convenience.

## Notebook Workflow

Open `Untitled.ipynb` with Jupyter Notebook or JupyterLab to reproduce the workflow:

1. Load the dataset with pandas.
2. Split the data into training and testing subsets using `train_test_split`.
3. Train a `LogisticRegression` classifier from scikit-learn.
4. Evaluate the model on the test set with `accuracy_score`.

You can adapt the notebook to explore additional preprocessing techniques, model types, or evaluation metrics.

## Environment Setup

To run the notebook, install the required Python packages (Python 3.9+ recommended):

```bash
pip install numpy pandas scikit-learn jupyter
```

Launch Jupyter after installing the dependencies:

```bash
jupyter notebook
```

Then open `Untitled.ipynb` to interact with the workflow.

## License

No explicit license has been provided for this project. Please consult the repository owner before using the code or data in other contexts.
