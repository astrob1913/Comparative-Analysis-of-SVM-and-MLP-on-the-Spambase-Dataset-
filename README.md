# Comparative-Analysis-of-SVM-and-MLP-on-the-Spambase-Dataset

## Project Overview

This project implements and compares two classification models:

1) Support Vector Machine (SVM)
2) Multilayer Perceptron (MLP)

The models are trained on a tabular dataset and evaluated using accuracy, precision, recall, F1-score, and confusion matrices. The final trained models are provided and can be directly evaluated by directly running the "FINAL TEST EVALUATION" section in the provided notebook.

---

## Files Included

1) `NECO_maincode.ipynb` - Main notebook for loading models and evaluating results
2) `mlp_model.pth` - Trained MLP model
3) `svm_model.pkl` - Trained SVM model
4) `scaler.pkl` - Fitted scaler used for preprocessing
5) `test_data.npz` - Test dataset
6) `requirements.txt` - Required Python packages

---

## requirements

numpy==2.1.1
pandas==2.2.3
scikit-learn==1.7.2
matplotlib==3.9.2
torch==2.11.0
jupyter==1.0.0

---

## setup_instructions

1. Extract all files from the provided zip archive.

2. Open a terminal/command prompt and navigate to the extracted folder:
   cd <project_folder_path>

3. Create and activate a virtual environment:

   For Windows:
   python -m venv Student_env
   Student_env\Scripts\activate

   For macOS/Linux:
   python3 -m venv Student_env
   source Student_env/bin/activate

4. Install required dependencies:
   pip install -r requirements.txt

5. Ensure the following files are present in the root folder:

   * test_data.npz
   * mlp_model.pth
   * svm_model.pkl
   * scaler.pkl

6. Launch Jupyter Notebook:
   jupyter notebook

7. Open and run:
   NECO_maincode.ipynb

---

## Notes

- The notebook loads pre-trained models and performs evaluation on the test dataset.
- No retraining is required.
- Ensure all files remain in the same directory to avoid file path errors.

---

## Reproducibility

All preprocessing steps (including feature scaling) are applied consistently using the saved `scaler.pkl`. The models and test data are provided to ensure reproducible results.
