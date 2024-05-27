# AutoML Project

Welcome to the AutoML Project! This project automates the process of Exploratory Data Analysis (EDA) and Machine Learning (ML) modeling. Simply upload your data, and the application will guide you through the process.

## Features

- **Upload Data:** Upload your dataset in CSV format.
- **Perform EDA:** Automatically generate a comprehensive EDA report.
- **Perform Modeling:** Automatically build and compare ML models to find the best one.
- **Download:** Download the best model for future use.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    `git clone https://github.com/your-username/automl-project.git`
    `cd automl-project`

2. **Install the required packages:**

    You can use `pip` to install the required packages. Make sure you have Python installed.

    `pip install -r requirements.txt`

    Ensure the `requirements.txt` includes the necessary libraries:

    ```
    streamlit
    pandas
    ydata_profiling
    streamlit_pandas_profiling
    pycaret
    ```

3. **Run the Streamlit app:**

   `streamlit run app.py`

## Usage

1. **Upload Your Data:**

    - Navigate to the "Upload your data" section.
    - Upload your CSV file.
    - The dataset will be displayed for your review.

2. **Perform EDA:**

    - Navigate to the "Perform EDA" section.
    - A comprehensive EDA report will be generated and displayed.

3. **Perform Modeling:**

    - Navigate to the "Perform modeling" section.
    - Select the target column for your ML model.
    - Click the "Run Modelling" button to start the ML experiment.
    - The best model and comparison results will be displayed.

4. **Download:**

    - Navigate to the "Download" section.
    - Click the download button to save the best model to your local machine.

## Example

Here is a brief example of how to use the application:

1. Upload your dataset by navigating to "Upload your data".
2. Perform EDA by selecting "Perform EDA".
3. Choose your target column and perform modeling in the "Perform modeling" section.
4. Download the best model in the "Download" section.

## Contributing

Contributions are welcome! Please create a pull request with a detailed description of the changes.


Enjoy using the AutoML Project!

