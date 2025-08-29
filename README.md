# Abalone Age Prediction using ANN

## 📌 Overview
This project builds an Artificial Neural Network (ANN) to predict the age of abalone, a type of marine mollusk. The prediction is based on physical measurements of abalones. The goal is to estimate age from given features while improving model performance using deep learning techniques.

## 📊 Dataset
- **Source:** Kaggle – Abalone Dataset
- **Features:** Length, Diameter, Height, Whole Weight, Shucked Weight, Viscera Weight, Shell Weight, Sex (categorical)
- **Target:** Rings (used to approximate age)

## ⚙️ Approach
1. **Data Preprocessing:**
   - Applied **label encoding** to handle categorical features (Sex).
   - Performed **feature scaling** to normalize continuous variables.

2. **Model Building:**
   - Constructed an **ANN** with input, hidden, and output layers.
   - Used **Batch Normalization** to stabilize and accelerate training.
   - Applied **Dropout** to prevent overfitting.

3. **Training & Optimization:**
   - Optimized with Adam optimizer and MSE loss.
   - Evaluated model using regression metrics (MAE, MSE, R²).

## 🚀 Results
- The ANN model successfully learned patterns in the dataset.
- Batch Normalization and Dropout improved generalization.
- Achieved reliable performance for predicting abalone age.

## 📂 Project Structure
```
├── Abalone's Age.ipynb   # Jupyter Notebook with code and experiments
├── README.md             # Project documentation
```

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/abalone-age-prediction-ann.git
   cd abalone-age-prediction-ann
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "Abalone's Age.ipynb"
   ```

## 📌 Future Improvements
- Experiment with deeper networks and regularization techniques.
- Compare performance with other models (Decision Trees, Random Forest, XGBoost).
- Deploy as a web app for interactive predictions.

---

🔗 *Feel free to fork and improve this project!*
