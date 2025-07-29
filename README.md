# Customer Churn Prediction using Machine Learning

This project presents a data-driven approach to predicting customer churn for a financial institution. By analyzing customer demographics and banking behavior, this project builds and evaluates machine learning models to identify customers at risk of closing their accounts. The primary goal is to provide the bank with actionable insights to improve customer retention.

![Models Performance](https_placeholder_for_a_graph_image.png) *You can add a screenshot of one of your Plotly graphs here to make it visually appealing!*

## Project Highlights

- **End-to-End ML Pipeline:** Demonstrates the complete process from data cleaning and preprocessing to model training and evaluation.
- **In-depth Data Analysis (EDA):** Leverages `Plotly` and `Seaborn` to create insightful visualizations, uncovering key factors correlated with customer churn.
- **Model Comparison:** Implements and compares two powerful classification algorithms, `XGBoost` and `Random Forest`, to find the most effective predictive model.
- **Focus on Metrics:** The evaluation goes beyond accuracy, analyzing precision and recall to understand the model's real-world effectiveness in identifying churners.

## Technologies & Libraries
- **Languages:** Python
- **Libraries:**
    - **Data Manipulation:** Pandas, NumPy
    - **Data Visualization:** Matplotlib, Seaborn, Plotly
    - **Machine Learning:** Scikit-learn, XGBoost

## How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sanjanach/Customer-Churn-Prediction.git
    cd Customer-Churn-Prediction
    ```
2.  **Install the required dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib plotly scikit-learn xgboost
    ```
3.  **Launch the Jupyter Notebook:**
    ```bash
    jupyter notebook predict_customerchurn.ipynb
    ```

## Model Performance

The project concluded that the Random Forest Classifier performed slightly better for this dataset.

-   **Random Forest Accuracy:** **86.5%**
-   **XGBoost Accuracy:** **86.3%**

**Random Forest Classification Report:**
