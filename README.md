# Binary-Classification-with-TensorFlow-Rice-Classification
<img width="1084" height="525" alt="newplot (2)" src="https://github.com/user-attachments/assets/7328099f-c34f-4948-8107-d3d91cdb7397" />



# Binary Classification with TensorFlow

This project is based on Google's Machine Learning Crash Course Binary Classification exercise.

Rather than simply reproducing the notebook, I experimented with different hyperparameters, particularly:

- Classification Threshold
- Learning Rate

to understand how these affect model performance and evaluation metrics.

## Objective

Build a logistic regression model that classifies rice varieties using TensorFlow while exploring how tuning hyperparameters impacts model behavior.

## Dataset

Rice Classification Dataset provided in Google's Machine Learning Crash Course.

## Technologies Used

- Python
- TensorFlow
- Pandas
- NumPy
- Matplotlib

## Experiments

I modified the following parameters:

- Learning Rate
- Classification Threshold

and observed changes in:

- Accuracy
- Precision
- Recall
- Loss
- Confusion Matrix

## Key Learnings

- The classification threshold directly affects the trade-off between Precision and Recall.
- Lower thresholds generally increase Recall but may reduce Precision.
- Learning rate influences how quickly the model converges.
- Choosing an appropriate learning rate is essential to avoid slow learning or unstable training.
- Accuracy alone is not enough when evaluating a classifier.

## Repository Structure

- Binary Classification Notebook
- Experimental Results
- Visualizations
