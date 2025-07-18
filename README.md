# ⚛️ Quantum Diabetes Classifier (NQCC Hackathon)

A beginner-friendly project comparing **classical logistic regression** with a **quantum machine learning (QML)** approach using the **PIMA diabetes dataset**.

---

## 🔧 Built With:
- 🧠 **Scikit-learn** – for classical ML and evaluation
- ⚛️ **PennyLane** – to build and run quantum circuits on a simulated quantum device (`default.qubit`)
- 📊 **PIMA Indians Diabetes Dataset** – real-world medical data for diabetes prediction

---

## 🎯 Goals:
- Understand and visualize the differences between **classical ML** and **quantum-enhanced ML**
- Use QML to simulate a simple quantum circuit that processes real health data
- Compare the performance (accuracy) of both approaches

---

## 🧪 Technologies Used:
- **Python** (via VS Code)
- **PennyLane QNode** to build a quantum circuit layer
- **Logistic Regression** trained on:
  - Raw input features (Classical)
  - Output of a parameterized quantum circuit (Quantum)

---

## 📈 Results:
- **Classical ML Accuracy**: `74.68%`
- **Quantum ML Accuracy**: `69.18%`

> *Your results may vary slightly depending on feature selection and weights initialization.*

---

## 🚀 Built For:
**[NQCC UK Quantum Hackathon 2025](https://www.nqcc.ac.uk/)**  
Use Case: *Applied Quantum Computing – Quantum ML for Diabetes Identification*

---

## 📂 Structure:
├── classical_model.ipynb   -  Classical ML with Scikit-learn

├── quantum_model.ipynb   -  Quantum circuit and training logic

├── README.md   -  This file

├── .venv/   -  Virtual environment ***(optional)***

---

## 🧠 For Beginners:
This project was created as a learning journey into:
- Machine Learning fundamentals
- Quantum computing basics using PennyLane
- Comparing classical vs. quantum results in a real-world use case

