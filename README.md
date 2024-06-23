# 📊 Data Manipulations and Predictive Modeling

This repository contains a Jupyter notebook focused on data manipulation and predictive modeling using two datasets: **netflix daily top 10** and **starbucks-menu-nutrition-drinks**.

## 📝 Project Overview

This project aims to preprocess datasets, perform data analysis, and apply predictive modeling techniques.

### 📁 Datasets Used

1. **Netflix Daily Top 10:** Contains information on the daily top 10 shows on Netflix.
2. **Starbucks Menu Nutrition Drinks:** Contains nutritional information about drinks from Starbucks.

## 📚 Notebook Contents

- **Data Preprocessing:**
  - Loading and cleaning the `netflix daily top 10` and `starbucks-menu-nutrition-drinks` datasets.
  - Conversion of columns to appropriate types.
  - Creation of derived columns for analysis.

- **Exploratory Data Analysis (EDA):**
  - Analysis and visualization of trends in the Netflix dataset.
  - Nutritional analysis of Starbucks drinks.

- **Model Training (Starbucks Data):**
  - Binary classification to predict if a drink is high-calorie based on its nutritional content.
  - Splitting the data into training and test sets.
  - Training a Decision Tree Classifier.
  - Evaluating the model's accuracy.

- **Visualization:**
  - Scatter plot visualization of drinks classified by calorie content.
  - Visualization of trends in Netflix's top 10 shows.

- **Prediction:**
  - Prediction of the calorie category for a new Starbucks drink based on its nutritional content.

## 🚀 Getting Started

To get a copy of the project up and running on your local machine, follow these steps.

### 📋 Prerequisites

Ensure you have the following installed:
- Python 3.6 or higher
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`

### 📦 Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/data-manipulations.git
    cd data-manipulations
    ```

2. Install the required libraries:
    ```sh
    pip install pandas numpy scikit-learn seaborn matplotlib
    ```

### 🖥️ Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook data_manipulations.ipynb
    ```

2. Run the cells in the notebook to see data preprocessing, analysis, visualization, and predictions.

## 📈 Results

- Analysis results of the Netflix daily top 10 trends.
- Nutritional analysis of Starbucks drinks.
- Model accuracy and predictions for new Starbucks drinks.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Thanks to the open-source community for providing valuable tools and libraries.
