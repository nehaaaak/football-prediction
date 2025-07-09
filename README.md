# ⚽️ Football Match Outcome Prediction – English Premier League (EPL)

## 📌 Project Overview
In this project, we predict the winner of football matches in the English Premier League (EPL) using machine learning. The model is trained on past match statistics and aims to forecast match outcomes based on venue, opponent, and other encoded features.

---

## 🔧 Project Steps
- Load and explore match data (`matches.csv`) using pandas.
- Prepare the dataset by encoding features like venue, opponent, day, and hour.
- Split data into training and test sets based on match date.
- Train a **Random Forest Classifier** on the training set.
- Predict match outcomes for the test set.
- Evaluate model performance using:
  - Accuracy Score  
  - Classification Report  
  - Visualizations: Feature Importance, Prediction Accuracy Chart

---

## 🧠 Tech Stack & Libraries
- Python 3.8+
- Jupyter Notebook (or VS Code with Jupyter extension)
- `pandas`
- `scikit-learn`
- `seaborn`
- `matplotlib`

---

## 📁 File Overview
- `prediction.ipynb` – Full machine learning workflow, from data loading to model training, prediction, and evaluation.
- `matches.csv` – Historical EPL match dataset used for training/testing the model.

---

## ⚙️ Local Setup Instructions

1. **Clone or download** the project folder.

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   # For macOS/Linux
   source venv/bin/activate
   # For Windows
   venv\Scripts\activate

3. **Install required packages**:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
  OR open prediction.ipynb directly in VS Code (Jupyter extension needed). 

---

## 📌 Note
- All predictions are based on historical data (matches.csv).
- The model was trained using basic encoded features; improvements like team form, player stats, or betting odds could be explored later.
