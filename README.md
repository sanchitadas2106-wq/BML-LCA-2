# BML-LCA-2
# LCA 2 - Decision Tree Classification on Breast Cancer Dataset

## Student Details

**Name:** Sanchita Das
**PRN:** 1262241864
**Roll No:** 69
**Class:** TY CSE B
**Batch:** C

## Subject

Basics of Machine Learning (BML)

## Aim

To train the system using the Breast Cancer dataset obtained from the UCI Machine Learning Repository and determine the accuracy using the Decision Tree Classifier.

## Dataset

* **Source:** UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Dataset
* **Instances:** 569
* **Features:** 30 numerical features describing characteristics of cell nuclei, such as radius, texture, perimeter, area, smoothness, compactness, concavity, and symmetry.
* **Target:** Diagnosis of breast cancer (converted to binary: 0 = Benign, 1 = Malignant)

## Steps Performed

1. Loaded the Breast Cancer dataset from the UCI Machine Learning Repository.
2. Separated the input features and target variable.
3. Removed the ID column as it is not useful for classification.
4. Converted the diagnosis labels into binary classes:

   * `0 = Benign`
   * `1 = Malignant`
5. Split the dataset into training and testing sets.
6. Applied the Decision Tree Classifier to the training data.
7. Used the trained model to predict the classes of the test data.
8. Calculated the classification accuracy using `accuracy_score`.

## Libraries Used

* pandas
* numpy
* scikit-learn

## Result

The Decision Tree Classification model was successfully trained on the Breast Cancer dataset. The accuracy achieved by the model is displayed in the notebook output.

