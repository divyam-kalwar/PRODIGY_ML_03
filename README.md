# Image Classification using SVM

This repository contains code for a simple image classification task using Support Vector Machines (SVM). The goal is to classify images of dogs and cats.

## Overview

- `train_data.pickle` and `test_data.pickle` contain preprocessed image data.
- The `model.sav` file stores the trained SVM model using the RBF kernel.

## Usage
    - Download the dataset from: https://www.kaggle.com/c/dogs-vs-cats/data
1. **Data Preparation:**
    - The training images are in the `train` folder, and test images are in the `test1` folder.
    - Images are preprocessed and saved as pickles: `train_data.pickle` and `test_data.pickle`.

2. **Model Training:**
    - SVM with RBF kernel is used for training.
    - Cross-validation is performed to evaluate the model's performance.
    - The trained model is saved as `model.sav`.

3. **Model Evaluation:**
    - The model is evaluated on a test set, and accuracy metrics are printed.
    - Confusion matrices and classification reports are visualized for both the test set and unseen data.

4. **Prediction:**
    - Predictions are made on the unseen test data, and results are saved in `submission.csv`.
    - An example prediction and corresponding image are shown.

## Files

- `train_data.pickle`: Preprocessed training data.
- `test_data.pickle`: Preprocessed test data.
- `model.sav`: Trained SVM model.
- `submission.csv`: Predictions on the unseen test data.

## Requirements

- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, OpenCV, scikit-learn

## Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repository.git
    cd your-repository
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the code:

    ```bash
    python your_script.py
    ```

4. View results in the generated files.

Feel free to explore and modify the code according to your needs. If you encounter any issues or have questions, please create an issue in the repository.

Happy coding!
