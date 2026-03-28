# 📊 K-Nearest Neighbors (KNN) From Scratch

A Machine Learning project that implements the **K-Nearest Neighbors (KNN) algorithm from scratch using Python**, without relying on pre-built libraries like Scikit-learn.

This project demonstrates a complete ML pipeline for **distance calculation, neighbor selection, majority voting, and prediction**, helping understand the core working of KNN at a fundamental level.

---

## 🚀 Key Features

* 🧠 KNN algorithm implemented from scratch  
* 📏 Euclidean distance-based similarity calculation  
* 🔢 Manual neighbor selection logic  
* 🎯 Classification using majority voting  
* ⚡ Simple and efficient implementation  
* 📊 Easy to understand and beginner-friendly  

---

## 🛠️ Tech Stack

* **Python**  
* **NumPy** – Numerical computations  
* **Pandas** – Data handling (optional)  
* **Matplotlib** – Visualization (optional)  

---

## 📸 Screenshots

### 🔹 Output Visualization

![Output](assets/screenshot.png)

---

## ⚙️ Installation & Setup

git clone https://github.com/your-username/knn-from-scratch.git  
cd knn-from-scratch  
python -m venv venv  
venv\Scripts\activate   # Windows  
pip install -r requirements.txt  

---

## ⚙️ Usage & Details

### ▶️ Run the Script
python knn.py  

### 🧠 System Workflow

- Load dataset  
- Split data into training and testing sets  
- For each test point:
  - Calculate distance from all training points  
  - Sort distances  
  - Select top K nearest neighbors  
  - Perform majority voting  
- Predict class label  
- Evaluate model performance  

---

## 📂 Output

- Predicted class labels  
- Model accuracy (if evaluation included)  
- Optional visualization of classification  

---

## 🎯 Use Cases

- Understanding KNN algorithm fundamentals  
- Educational and learning purposes  
- Small-scale classification problems  
- Baseline model for ML tasks  

---

## 🔮 Future Enhancements

- ⚡ Optimize using KD-Tree / Ball Tree  
- 📊 Add visualization of decision boundaries  
- 🔄 Support regression (KNN Regressor)  
- 📈 Hyperparameter tuning (K selection)  
- 🚀 Convert into Streamlit app  

---

## 👨‍💻 Author

**Embadi Anji**  
GitHub: https://github.com/Anjiembadi  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
