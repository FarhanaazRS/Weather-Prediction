# 🌦️ Weather Prediction

A machine learning project to predict if it will rain tomorrow using weather data. This includes traditional ML models, a 1D CNN for classification, and fuzzy logic to interpret CNN confidence scores more intelligently.

---

## 🔧 Features

- Weather data preprocessing (handling missing values, encoding, scaling)
- Machine Learning Models:
  - Linear Regression
  - Lasso Regression
  - Random Forest
- Deep Learning using 1D CNN
- Fuzzy logic applied on CNN output for confidence-based decision making
- Accuracy comparison and result visualization

---

## 💻 Tech Used

- Python
- NumPy, Pandas, Matplotlib, Plotly
- scikit-learn
- TensorFlow / Keras
- Custom fuzzy logic

---

## 🚀 How to Use

1. Clone the repository or open in Jupyter/Colab.
2. Install required packages:
   ```bash
   pip install numpy pandas matplotlib plotly scikit-learn tensorflow
   ```
3. Ensure the dataset file ```weatherAUS.csv``` is in the same directory.
4. Run the script or notebook to train and evaluate all models.

## 📌 Notes
 - The fuzzy logic layer is manually implemented to interpret CNN probabilities (Low, Medium, High confidence).
 - All models are trained on 80% of the data and tested on the remaining 20%.
 - Results may vary slightly based on system performance and random seed.
