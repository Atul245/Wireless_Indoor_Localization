# 📡 Wireless Indoor Localization

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)  
[![scikit-learn](https://img.shields.io/badge/scikit--learn-0.21.3-green.svg)](https://scikit-learn.org/stable/)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Made with ML](https://img.shields.io/badge/Machine-Learning-black.svg)](#)  

## 📌 Abstract
This project focuses on building a **Wireless Indoor Localization system** that predicts a user’s position indoors using **WiFi signal strengths** from multiple access points — an area where GPS-based methods fail.  

It is my **first public machine learning project**, where I implemented and compared different classification algorithms. For each model, multiple hyperparameters were tuned, and the best-performing configuration was selected to generate results such as confusion matrices and accuracy scores.  

---

## 🧠 Description
The project implements and evaluates the following **machine learning classifiers**:
- k-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- Gradient Boosting  

Key highlights:
- Applied **GridSearchCV** for hyperparameter tuning.  
- Performed **comparative analysis** between models to highlight performance trade-offs.  
- Achieved **~96% accuracy** with **Random Forest**, supported by confusion matrix and heatmap visualizations.  
- Conducted **EDA** to analyze WiFi signal distributions across different rooms.  

---

## 📊 Source Dataset
- **Dataset:** [UCI Wireless Indoor Localization](https://archive.ics.uci.edu/ml/datasets/Wireless+Indoor+Localization)  
- **Details:**  
  - **2000 samples**  
  - **7 features** (signal strength values)  
  - **4 room classes**  

---

## 🛠️ Tools and Libraries Used
- Python 3.7.1 (Jupyter Notebook)  
- **pandas** 0.25.1  
- **numpy** 1.16.5  
- **matplotlib** 3.1.0  
- **scikit-learn** 0.21.3  
- **seaborn** 0.9.0  

---

## 📈 Results
- Best-performing model: **Random Forest (~96% accuracy)**  
- Visualization of performance with **confusion matrices** and **heatmaps**.  
- Compared results across **5 ML models** for clarity and reproducibility.  

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Wireless-Indoor-Localization.git
   cd Wireless-Indoor-Localization
2. **Install dependencies:**
   ```bash
    pip install -r requirements.txt
3. **Open the Jupyter Notebook:**
  ```bash
  Run the notebook to reproduce experiments and results.
  ```

## ✨ If you like this project, don’t forget to star ⭐ the repo!
