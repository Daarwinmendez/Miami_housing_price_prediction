# Miami Housing Price Prediction

This repository contains an analysis and data modeling project using the **Miami Housing Dataset** available on Kaggle. The goal is to predict property sale prices in Miami based on various features like land area, proximity to the ocean, structure age, and more.

## Contents

- **Data Exploration**: A thorough analysis of the dataset's features, including missing values identification and variable distribution analysis.
- **Data Preprocessing**: Standardization of features using `StandardScaler` to enhance the performance of Machine Learning models.
- **Modeling**: Comparison of several regression models including `LinearRegression`, `Ridge`, `Lasso`, and `ElasticNet`. Performance is evaluated using metrics such as `R2 score` and `Mean Absolute Error`.
- **Visualization**: Scatter plots comparing actual vs. predicted sale prices, along with visualizing the distribution of prediction errors.
- **Hyperparameter Tuning**: Use of `GridSearchCV` to optimize the hyperparameters of the `Ridge` model for improved prediction accuracy.
- **Results**: Analysis of the results obtained and comparison of performance across different models.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/Miami_housing_price_prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Miami_housing_price_prediction
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the notebook:
    ```bash
    jupyter notebook Miami_housing.ipynb
    ```

## Dataset

This project uses the [Miami Housing Dataset](https://www.kaggle.com/datasets/deepcontractor/miami-housing-dataset) available on Kaggle, provided by **DeepContractor**.

## Contribution

Contributions are welcome. If you find a bug or have an improvement, please open an issue or submit a pull request.

## License

This project is licensed under the terms of the MIT License.
