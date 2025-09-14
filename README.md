# 🌳 Decision Tree Classifier from Scratch

A simple implementation of **Decision Tree Classifier** using **Information Gain (Entropy)** as the splitting criterion.  
This project trains a decision tree on the classic **Iris Dataset** and demonstrates how trees are built recursively without using libraries like scikit-learn.

---

## 🚀 Features

- Implements entropy and information gain calculation  
- Recursive tree building up to a maximum depth  
- Handles multi-class classification (Iris dataset with 3 classes)  
- Simple and clean Python implementation using `pandas` and `numpy`  
- Easily extendable for other datasets  

---

## 📊 Dataset

- Uses the famous **Iris dataset** from `sklearn.datasets`  
- Predicts the Iris flower type based on sepal and petal measurements  
- Data converted to integer for simplicity

---

## ⚙️ How It Works

1. Calculate **Entropy** for dataset splits  
2. Compute **Information Gain** to select the best feature  
3. Recursively split the dataset until:
   - All samples belong to one class, or  
   - Maximum depth is reached  
4. Assign class labels at leaf nodes

---

## 📚 Example Output

Level 0
Count of setosa = 50
Count of versicolor = 50
Count of virginica = 50
Current entropy = 1.58496
Splitting on Tree Features petal width (cm) with information gain 3

...
Reached leaf Node


---

## ⚡ Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/decision-tree-from-scratch.git

# Run the script
python decision_tree.py

🧱 Requirements

Python >= 3.7

numpy

pandas

scikit-learn

🔧 Future Improvements

Add prediction functionality

Support for continuous attributes more elegantly

Visualization of the decision tree structure

📄 License

This project is open source under the MIT License.

Made with ❤️ by Sk Samim Ali

