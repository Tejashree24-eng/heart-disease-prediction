# Heart Disease Prediction

A binary-classification learning project that uses a feed-forward neural network to estimate the target class in a tabular heart-disease dataset.

## Project overview
- Dataset: Heart Disease dataset loaded from the TensorFlow-hosted CSV
- Framework: TensorFlow / Keras
- Data tools: Pandas and NumPy
- Evaluation: Scikit-learn classification report and confusion matrix

## Workflow
1. Load and inspect the dataset.
2. One-hot encode categorical columns.
3. Split rows into training and test sets.
4. Standardize numerical features using statistics calculated from the training set.
5. Train a neural network with a 16-unit ReLU hidden layer and sigmoid output.
6. Evaluate predictions using accuracy, a classification report and a confusion matrix.

## Recorded result
**Test accuracy: approximately 84%** (the notebook's held-out test classification report shows 0.84 accuracy on 61 examples). Training accuracy is higher, so the gap is worth considering when discussing generalization.

## Run
Open `heart_disease_prediction.ipynb` in Jupyter or Google Colab and run the cells in order. The notebook downloads the CSV from the URL in its code, so internet access is required.

## Dependencies
See [requirements.txt](requirements.txt).

## Important disclaimer
This is an educational machine-learning exercise, not a medical device or clinically validated diagnostic tool. It must not be used to diagnose, treat or make healthcare decisions.
