# Human Activity Recognition with Smartphones

📝 This repository contains a dataset of accelerometer and gyroscope sensor data from smartphones, collected for the purpose of Human Activity Recognition (HAR). The dataset is intended for use in developing machine learning models to accurately classify various human activities, such as walking, running, sitting, and more.

## ⌛Dataset

The dataset used in this project consists of:
- Number of Entries: 2,947
- Number of Columns: 563
- Data Types: 561 columns with float64, 1 column with int64, and 1 column with object (string) data.
- Memory Usage: Approximately 12.7 MB.

## 🎯Approach

1. **Importing the Dataset**: The dataset is loaded from `train.csv` and `test.csv` files using pandas.
2. **Data Exploration**: The top and last 5 rows of the dataset are displayed to get a glimpse of the data structure.
3. **Handling Duplicate Values**: Duplicate columns in the dataset, if any, are identified and removed.
4. **Handling Missing Values**: Missing values are checked for and addressed if present.
5. **Feature Engineering**: The feature matrix `X` and the target vector `y` are created from the dataset.
6. **Data Splitting**: The dataset is split into training and testing sets.
7. **Model Training**: Two models, Logistic Regression and Random Forest Classifier, are trained and evaluated.
8. **Feature Selection**: Feature selection is performed using the Filter and Wrapper methods to improve model performance.
9. **Model Evaluation**: The Random Forest Classifier is retrained with the selected features and its performance is evaluated again.
10. **Saving Models**: The trained model and feature selection objects are saved using the joblib library.
11. **GUI Application**: A simple GUI application is built using tkinter to apply the trained model on new data.

## 📥Installations

To run the project, ensure you have the following installed:
- Python (version >= 3.6)
- pandas
- scikit-learn
- seaborn
- matplotlib
- tkinter (usually comes pre-installed with Python)

## ⚙️Setup

1. Clone the repository or download the project files.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Place the training and testing datasets (`train.csv` and `test.csv`) in the project directory.

## 🛠️Requirements

The project requires:
- Basic understanding of machine learning concepts.
- Familiarity with Python programming and data manipulation using pandas.

## 🚀Technology Used

- Python
- pandas
- scikit-learn
- seaborn
- matplotlib
- tkinter (for GUI)

## ▶️ Run

To run the project, execute the following steps:
1. Navigate to the project directory in your terminal or command prompt.
2. Run the main Python code-Notebook.
3. The GUI application will open, allowing you to predict human activities using the trained model on new data.

---

📝 I frequently create content focused on complete projects in the realm of data science using Python and R.

💬 Feel free to inquire about data science, computer vision, Python, and R.

---

<p align="Right">(◕‿◕) Thank you for exploring my GitHub project repository. 👋</p>
