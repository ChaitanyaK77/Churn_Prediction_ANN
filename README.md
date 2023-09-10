# Churn_Prediction_ANN
This repository contains a comprehensive Python script for building and training an Artificial Neural Network (ANN) model to predict customer churn using customer data. The code includes extensive data preprocessing steps, such as scaling, one-hot encoding, and visualization, to ensure the model's accuracy and effectiveness.

Churn Prediction with Artificial Neural Network (ANN)

## Getting Started

To run this code, you will need to have Python installed on your system. Additionally, make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow
- seaborn (for visualization)

You can install these libraries using `pip`:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow seaborn
```

## Usage

1. Clone this repository to your local machine or open it in a Jupyter Notebook environment.

2. Make sure to upload your dataset (`Churn_pred_data.csv`) to the appropriate location or specify the correct file path in the code.

3. Open the script and run each code block sequentially. Here's a brief overview of what each section of the code accomplishes:

   - **Data Loading**: The code starts by loading the dataset from a CSV file using Pandas and displays basic information about the data.

   - **Data Preprocessing**: This section includes extensive data preprocessing steps, such as handling missing values, encoding categorical features using one-hot encoding, scaling numeric features using Min-Max scaling, and visualizing data distributions.

   - **Neural Network Model**: A feedforward neural network model is defined using TensorFlow and Keras. The architecture includes multiple layers with ReLU activation functions and a final sigmoid output layer for binary classification. You can customize the architecture and hyperparameters as needed.

   - **Model Training**: The model is compiled with the Adam optimizer and binary cross-entropy loss function. It is then trained on the preprocessed data using a training and validation split.

   - **Model Evaluation**: The trained model is evaluated on a test dataset, and comprehensive classification metrics, including accuracy, precision, recall, F1-score, and a confusion matrix with a heatmap visualization, are computed and displayed.

4. Feel free to modify the code to suit your specific dataset or experiment with different neural network architectures and preprocessing techniques.

