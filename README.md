# Titanic Classification

This project predicts the survival of passengers on the Titanic using factors such as socio-economic status, age, gender, and more.

## Data

The dataset used in this project is from [Kaggle's Titanic dataset](https://www.kaggle.com/c/titanic/data).

## Project Structure

- `data/`: Contains the Titanic dataset.
- `notebooks/`: Contains the Jupyter Notebook and R Markdown file for data analysis and model training.
  - `titanic_classification.ipynb`: Jupyter Notebook for Python implementation.
  - `titanic_classification.Rmd`: R Markdown file for R implementation.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python packages.

## How to Run

### Python

1. Clone the repository.
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
3. Open the Jupyter Notebook:
    ```sh
    jupyter notebook notebooks/titanic_classification.ipynb
    ```

### R

1. Clone the repository.
2. Install the required packages:
    ```r
    install.packages(c("tidyverse", "caret", "randomForest", "ranger", "gridExtra", "ggcorrplot"))
    ```
3. Open the R Markdown file:
    ```r
    rmarkdown::render("notebooks/titanic_classification.Rmd")
    ```

## Conclusion

In this project, we successfully predicted the survival of passengers on the Titanic using a Random Forest model. We explored various features and their impact on survival and performed hyperparameter tuning to improve the model's performance.