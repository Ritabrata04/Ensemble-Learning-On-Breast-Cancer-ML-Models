# Wisconsin Breast Cancer Prediction using Multiple Machine Learning Models

This project involves the use of various machine learning models including Logistic Regression, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Random Forest (RF), and Decision Trees to classify breast cancer cases using the Wisconsin Breast Cancer Dataset. Each model is used independently, and their performance is compared against each other. The ultimate aim of the project is to develop an optimized classifier using Principal Component Analysis (PCA) for feature reduction, and GridSearch CV for hyperparameter tuning.

The project further explores two cases of voting using ensemble learning:

1. **Hard Voting**: This method takes the mode of the predictions made by the individual models in the ensemble. It's a majority vote mechanism where each classifier gets one vote per prediction and the final output prediction is the one that receives the majority of votes.

2. **Soft Voting**: Unlike hard voting, soft voting takes into account the confidence level (probability) of each classifier’s prediction, and returns the class that has the highest mean predicted probabilities. This often leads to better performance as it leverages the strengths of individual classifiers.

## Future Directions

We are planning to extend this project by implementing bootstrap aggregating (bagging) and boosting ensemble methods to improve the classifier's performance. These techniques are expected to further enhance the predictive power of the model by reducing the variance and bias respectively.

## Dataset

The dataset used in this project is the Wisconsin Breast Cancer Dataset. It is publicly available and it contains 569 instances with 32 attributes (features) each. The goal is to predict whether the breast cancer is benign or malignant.

## Setup and Installation

The project requires Python 3.7+ and the following Python libraries installed:

- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Seaborn

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
```

To run the project, simply clone the repository and run the main script.

```bash
git clone https://github.com/username/project.git
cd project
python main.py
```

Please replace 'username' and 'project' with the actual GitHub username and project name.

## Contribution

This project is open-source and welcomes contributions. Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

