# Iris-Flower-Classification
Iris flower classification using Logistic Regression and Decision Tree
# Iris Flower Classification

## Project Overview
This project focuses on classifying Iris flowers into three species using supervised machine learning algorithms.

The project uses the Iris dataset and implements two classification models:
- Logistic Regression
- Decision Tree Classifier

## Dataset
The dataset contains four numerical features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target variable: Species

The three flower classes are:
- Setosa
- Versicolor
- Virginica

After removing one duplicate record, the dataset contains 149 samples.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data loading and exploration
2. Data cleaning and duplicate removal
3. Exploratory Data Analysis (EDA)
4. Train-test split (80:20)
5. Feature scaling using StandardScaler
6. Model training using Logistic Regression
7. Model training using Decision Tree
8. Model evaluation
9. Confusion matrix visualization
10. Decision boundary visualization

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 93.33% | 93.33% | 93.33% | 93.33% |
| Decision Tree | 93.33% | 93.33% | 93.33% | 93.33% |

*Evaluation metrics use weighted averaging.*

## Visualizations
- Pairplot for exploratory data analysis
- Confusion matrices
- Decision boundary visualization using Petal Length and Petal Width

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells.

## Conclusion
Both Logistic Regression and Decision Tree achieved 93.33% accuracy on the test dataset. Both models demonstrated equal performance on the evaluated metrics.

## Author
Neha More
