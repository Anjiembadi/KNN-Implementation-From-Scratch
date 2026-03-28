# 📊 K-Nearest Neighbors (KNN) From Scratch

A Machine Learning project that implements the **K-Nearest Neighbors (KNN) algorithm from scratch using Python in a Jupyter Notebook**, without relying on pre-built libraries like Scikit-learn.

This project demonstrates a complete ML pipeline for **distance calculation, neighbor selection, majority voting, and prediction**, helping understand the core working of KNN at a fundamental level.

---

## 🚀 Key Features

* 🧠 KNN algorithm implemented from scratch  
* 📏 Euclidean distance-based similarity calculation  
* 🔢 Manual neighbor selection logic  
* 🎯 Classification using majority voting  
* ⚡ Step-by-step implementation in Jupyter Notebook  
* 📊 Easy to understand and beginner-friendly  

---

## 🛠️ Tech Stack

* **Python**  
* **NumPy** – Numerical computations  
* **Pandas** – Data handling  
* **Jupyter Notebook** – Interactive development  
* **Matplotlib** – Visualization (optional)  

---



## ⚙️ Installation & Setup

git clone https://github.com/your-username/knn-from-scratch.git  
cd knn-from-scratch  
python -m venv venv  
venv\Scripts\activate   # Windows  
pip install -r requirements.txt  

---

## ⚙️ Usage & Details

### ▶️ Run the Notebook
jupyter notebook  

Open the file:
`knn_from_scratch.ipynb`

### 🧠 System Workflow

- Load dataset  
- Perform preprocessing:
  - Apply **Ordinal Encoding** for categorical features  
  - Apply **Robust Scaling** for numerical features  
  - Combine transformations using **ColumnTransformer**  
- Split data into training and testing sets  
- For each test point:
  - Calculate distance from all training points  
  - Sort distances  
  - Select top K nearest neighbors  
  - Perform majority voting  
- Predict class label  
- Evaluate model performance  

## 📂 Output

- Predicted class labels  
- Model accuracy / evaluation metrics  
- Notebook-based step-by-step outputs  

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
