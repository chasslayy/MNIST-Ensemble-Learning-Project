# MNIST-Ensemble-Learning-Project

This repository contains a full implementation of **ensemble learning techniques** using the **MNIST handwritten digits dataset**.  
The project demonstrates how combining multiple models—through voting and stacking—can improve performance compared to individual classifiers.

This notebook was created as part of a Machine Learning assignment and showcases practical ML engineering skills.

## 🚀 Project Summary

We train three base classifiers:

- **Random Forest Classifier**  
- **Extra Trees Classifier**  
- **SVM (RBF Kernel)** (with feature scaling)

Then we build multiple ensemble models:

- **Hard Voting Ensemble**  
- **Soft Voting Ensemble**  
- **Manual Stacking / Blender Model**  
- **`StackingClassifier` from Scikit-Learn**

The goal is to compare validation and test accuracy across these models and determine whether ensembling provides measurable performance gains.

## 🧠 Key Concepts Demonstrated

✔ Bagging-based models (Random Forest, Extra Trees)  
✔ SVM classification with scaling  
✔ Hard vs. soft voting  
✔ Meta-learning with stacking  
✔ Model comparison and evaluation  
✔ Train/validation/test splitting  
✔ Working with scikit-learn pipelines  

This project is ideal for anyone learning ensemble methods or building an ML portfolio.

## 📊 Dataset

The MNIST dataset (from OpenML) contains:

- **70,000** grayscale images of handwritten digits
- **28 × 28** pixel resolution
- Classes **0–9**

The dataset is split as:

- **50,000** for training  
- **10,000** for validation  
- **10,000** for testing  

## 📂 Repository Structure

```
mnist-ensemble-learning/
│
├── ensemble_learning_mnist.ipynb   # Main notebook with all training code
└── README.md                       # Documentation
```

## ▶️ How to Run

### Option 1: Google Colab
1. Upload the notebook  
2. Run all cells  
3. No installs required  

### Option 2: Local Environment

Install dependencies:

```bash
pip install numpy scikit-learn matplotlib
```

Start Jupyter:

```bash
jupyter notebook ensemble_learning_mnist.ipynb
```

## 📈 Expected Performance

| Model | Approx. Validation Accuracy |
|-------|-----------------------------|
| Random Forest | 96–97% |
| Extra Trees | ~97% |
| SVM (RBF) | ~98% |
| **Soft Voting Ensemble** | ~98–98.5% |
| **Manual Stacking** | ~98–99% |
| **StackingClassifier** | Often best (up to 99%) |

Your results may vary depending on system performance.

## 🧩 Skills Shown in This Project

This notebook demonstrates:

- Hands-on machine learning model training  
- Ensemble learning (bagging, voting, stacking)  
- Advanced scikit-learn techniques  
- Data preprocessing  
- Evaluation & comparison of multiple ML models  
- Reproducible ML workflow design  

## ✨ Author

**Chastity Lewis**  
Graduate Student – Computer Science (AI & Machine Learning)  
Machine Learning Engineer (in progress)  
Creator of beauty-tech brand **Chasslayy Luxe**
