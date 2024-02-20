# Skin Cancer Classification with SVM

This project implements a Support Vector Machine (SVM) classifier to distinguish between skin and non-skin lesions using data from the "Skin_Nonskin(mod).csv" dataset. It aims to aid in the early detection of skin cancer by accurately classifying potential lesions.

## Key Features

- Loads the "Skin_Nonskin(mod).csv" dataset containing features and labels for skin and non-skin lesions.
- Splits the data into training and testing sets for model evaluation.
- Trains a linear SVM classifier to learn the decision boundary between skin and non-skin classes.
- Evaluates the model's performance using accuracy and Root Mean Squared Error (RMSE) on the test set.
- Visualizes the data distribution using a scatter plot to understand the class separation.

## Installation and Usage

1. **Prerequisites:** Ensure you have Python and the following libraries installed:
   - pandas
   - scikit-learn
   - matplotlib

   You can install them using pip:

   ```bash
   pip install pandas scikit-learn matplotlib
  
  2. **Running the Script:** Navigate to the project directory and run the Python script:
     
    ```bash
    python skin_classification.py

## Results and Visualization

The script outputs the model's accuracy and RMSE, providing insights into its performance. Additionally, a scatter plot is generated to visualize the distribution of data points in the feature space, potentially revealing patterns and class separation.

**Note:** The specific values for accuracy and RMSE might vary depending on dataset characteristics and random splits.
