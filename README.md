# LOAN-APPROVAL-PREDICTION-SYSTEM
LOAN APPROVAL PREDICTION USING MACHINE LEARNING


# LOAN-APPROVAL-PREDICTION
Machine Learning Project, Linear Regression 

```markdown
# Bank Loan Prediction with Linear Regression

## Project Overview

This project is a machine learning application designed to predict whether a bank loan will be approved for a given applicant. The application uses a Linear Regression model to make predictions based on various features provided by the user. The interactive interface is implemented using `ipywidgets` and is intended to run within a Jupyter notebook.

## Features

- **User Input:** Collects user data such as gender, education, marital status, employment status, property area, and more.
- **Model Prediction:** Uses a pre-trained Linear Regression model to predict loan approval.
- **Interactive Interface:** Utilizes `ipywidgets` to create an interactive and user-friendly experience.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/bank-loan-prediction.git
    cd bank-loan-prediction
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Ensure you have Jupyter installed:
    ```bash
    pip install jupyter
    ```

5. Install `ipywidgets` if not already installed:
    ```bash
    pip install ipywidgets
    ```

## Usage

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open the notebook file:
    ```markdown
    Bank_Loan_Prediction.ipynb
    ```

3. Run all cells in the notebook. Enter the required information in the provided widgets and click the "Submit" button to see the loan prediction result.

## Model Information

The project uses a Linear Regression model, which has been trained on a dataset containing various features related to loan applications. The model was trained using the following features:

- Gender
- Marital Status
- Dependents
- Education
- Employment Status
- Applicant's Monthly Income
- Co-Applicant's Monthly Income
- Loan Amount
- Loan Duration
- Credit Score
- Property Area

## Project Structure

- `model1.pkl`: Pre-trained Linear Regression model saved using pickle.
- `Bank_Loan_Prediction.ipynb`: Jupyter notebook containing the interactive loan prediction interface.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Description of changes"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request detailing your changes.

## Acknowledgements

- This project utilizes the Linear Regression model from `scikit-learn`.
- The interactive interface is built using `ipywidgets` and Jupyter Notebook.

### Steps to Complete the Project:

1. **Repository Structure**: Ensure your GitHub repository is structured as mentioned in the README.
2. **Model File**: Save your pre-trained Linear Regression model as `model1.pkl`.
3. **Notebook**: Ensure the `Bank_Loan_Prediction.ipynb` notebook contains the code provided for the interactive widget interface.
4. **Requirements File**: Create a `requirements.txt` file with the necessary dependencies.

