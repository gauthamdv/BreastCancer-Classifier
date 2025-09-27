# Breast Cancer Classifier

## 📖 Introduction

This project demonstrates a complete pipeline for classifying breast cancer as benign or malignant using Logistic Regression. The repository includes data preprocessing, feature analysis, model training, threshold tuning, evaluation with ROC and Precision-Recall curves, and saving the trained model for future predictions.

**Note:** To use this notebook and scripts, you need a clean and preprocessed dataset. To generate it, run the `data-preprocessing.py` file provided in this repository. The cleaned dataset will be saved in the `datasets/` folder.

---

## 🗂 File Structure

```
BreastCancer-Classifier/
│
├── datasets/                 # Folder to store cleaned datasets
├── models/                   # Folder to store trained models
├── plots/                    # Folder for plots
├── data-preprocessing.py     # Script to clean and preprocess raw data
├── logistic-classifier.ipynb # Jupyter Notebook with model training and evaluation
├── requirements.txt          # Required Python packages
└── README.md                 # Project documentation (this file)
```

---

## ⚙️ Setup Instructions

1. **Clone the repository:**

```bash
git clone https://github.com/gauthamdv/BreastCancer-Classifier.git
cd BreastCancer-Classifier
```

2. **Install dependencies:**
   Use the `requirements.txt` file in the root directory to install all required packages:

```bash
pip install -r requirements.txt
```

3. **Preprocess the data:**

```bash
python data-preprocessing.py
```

This will clean the raw dataset and save the processed dataset in the `datasets/` folder.

4. **Run the Jupyter Notebook:**

```bash
jupyter notebook logistic-classifier.ipynb
```

Follow the notebook to explore the dataset, train the Logistic Regression model, evaluate it, and visualize the results.

---

## 🧪 Model Workflow

1. **Data Preprocessing:** Clean the raw dataset using `data-preprocessing.py`.
2. **Feature Analysis:** Explore and understand the significance of each feature.
3. **Model Training:** Train a Logistic Regression classifier.
4. **Threshold Tuning:** Optimize decision threshold for better classification.
5. **Evaluation:** Use ROC and Precision-Recall curves to evaluate performance.
6. **Save Model:** Save the trained model in the `models/` folder for future use.

---

## 📊 Evaluation Metrics

* **ROC Curve:** Shows the trade-off between sensitivity and specificity.
* **Precision-Recall Curve:** Focuses on the performance with respect to the positive (malignant) class.

Additional metrics such as accuracy, F1-score, and confusion matrix can also be calculated.

---

## 💻 Requirements

All dependencies are listed in the `requirements.txt` file in the root directory. Install them with:

```bash
pip install -r requirements.txt
```

---

## 🎯 Conclusion

This project provides a clear, reproducible pipeline for breast cancer classification. By following the preprocessing steps and using the notebook, anyone can train and evaluate a Logistic Regression model effectively.
