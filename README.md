# Fruit Classifier ML Project 🍎🍊🍌🍓🍉

## Overview
This project is my first machine learning model built with Python and scikit-learn.  
It uses **Logistic Regression** to classify fruits based on three features:
- Weight
- Size
- Color score

Currently, the model can classify **five fruits**:
- Apple
- Orange
- Banana
- Strawberry
- Watermelon

---

## Files
- `myfirstMLproject.ipynb` → Jupyter Notebook containing the full code and workflow
- `fruits.csv` → Dataset with fruit features and labels (optional if you add one)
- `requirements.txt` → List of Python libraries needed

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Fruit-Classifier-ML.git
   2. Install dependencies:
   pip install -r requirements.txt
   3.Open the notebook:jupyter notebook myfirstMLproject.ipynb
   4. Run all cells from top to bottom.
Example Prediction
new_fruit = [[170, 8, 6]]
result = model.predict(new_fruit)
print("The model predicts this fruit is:", result[0])
Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy
- jupyter

Next Steps
- Expand dataset with more samples per fruit
- Try other models (Decision Tree, KNN)
- Improve accuracy with feature scaling and tuning

