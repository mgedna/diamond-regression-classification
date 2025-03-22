# 💎 Diamond Regression and Classification with SVR, SVC & kNN

This project explores both regression and classification techniques applied to the diamonds dataset. It includes support vector regression (SVR) with various kernels, support vector classification (SVC), and k-nearest neighbors (kNN) for predicting diamond properties based on physical dimensions and quality grades.

---

## 📊 Project Goals

- Predict **carat weight** from diamond dimensions using:
  - Linear SVR
  - Polynomial SVR
  - RBF SVR
- Classify **cut quality (Ideal or not)** using:
  - Linear SVC
  - Polynomial SVC
  - RBF SVC
  - k-Nearest Neighbors

---

## 📁 Dataset

- **Name**: Diamonds Dataset  
- **Source**: [Kaggle – Diamonds by Shivam Bansal](https://www.kaggle.com/datasets/shivam2503/diamonds)
- **Description**: Contains over 50,000 observations of diamonds with physical dimensions (`x`, `y`, `z`), price, and quality-related attributes such as `cut`, `color`, and `clarity`.

> 🔗 You must be logged in to Kaggle to download the dataset.

---

## 🧪 Machine Learning Techniques Used

### Regression Models:
- **SVR (Linear)** – Predict carat weight from xlength
- **SVR (Polynomial)** – Degree 2 curve fitting for carat
- **SVR (RBF)** – Non-linear SVR for more complex trends

### Classification Models:
- **SVC (Linear)** – Classify Ideal cuts using x and y dimensions
- **SVC (Polynomial & RBF)** – For non-linear boundaries
- **kNN Classifier** – Classify Ideal cuts using distance-based voting

---

## 📈 Evaluation Metrics

- Regression:
  - R² Score
  - Mean Squared Error (MSE)

- Classification:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - Matthews Correlation Coefficient (MCC)
  - ROC Curve and AUC
  - Cross-validation scores

---

## 📂 Project Structure

```
diamond-regression-classification/
│
├── data/
│   └── diamonds.csv
│
├── Diamond_Regression_Classification.ipynb   # Jupyter notebook with code & visualizations
├── README.md
└── requirements.txt
```

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mgedna/diamond-regression-classification.git
   cd diamond-regression-classification
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/shivam2503/diamonds) and place it in the `data/` folder as `diamonds.csv`.

4. Run the notebook:
   ```bash
   jupyter notebook Diamond_Regression_Classification.ipynb
   ```

---

## 👤 Author

Edna Memedula 
📫 [LinkedIn](https://www.linkedin.com/in/edna-memedula-24b519245) • [GitHub](https://github.com/mgedna) 
