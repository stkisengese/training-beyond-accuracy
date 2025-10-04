# Training Beyond Accuracy

A practical, exercise-driven introduction to core machine learning concepts using scikit-learn. This repository covers regression, classification, model evaluation (R², MSE, accuracy, F1, AUC), handling imbalanced data, pipeline construction, and hyperparameter tuning with GridSearchCV—using real datasets (California Housing, Breast Cancer).

## Features

*   **Exercise 1: MSE and Accuracy**: Introduces fundamental metrics like Mean Squared Error (MSE) and accuracy using `scikit-learn`.
*   **Exercise 3: Regression**: Demonstrates a complete regression workflow, including:
    *   Training a `LinearRegression` model.
    *   Using a `Pipeline` for preprocessing (imputation and scaling).
    *   Evaluating the model with R², MSE, and MAE.
*   **Exercise 4: Classification**: Covers a full classification task with `LogisticRegression`, including:
    *   Calculating metrics like F1-score, precision, recall, and AUC.
    *   Plotting a confusion matrix and ROC curve.
*   **Exercise 5: Comparing ML Models**: Compares the performance of multiple regression models:
    *   `LinearRegression`
    *   `SVR`
    *   `DecisionTreeRegressor`
    *   `RandomForestRegressor`
    *   `GradientBoostingRegressor`
    *   Includes hyperparameter tuning with `GridSearchCV`.

## Usage

To run the exercises, you will need to have Jupyter Notebook or JupyterLab installed. 

1.  Clone the repository:
    ```bash
    git clone https://github.com/stkisengese/training-beyond-accuracy.git
    cd training-beyond-accuracy
    ```

2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3.  Launch Jupyter Notebook or JupyterLab and open the `.ipynb` files.
    ```bash
    jupyter notebook
    ```

## Dependencies

All required libraries are listed in the `requirements.txt` file.

## License

This project is licensed under the terms of the [MIT License](LICENSE).