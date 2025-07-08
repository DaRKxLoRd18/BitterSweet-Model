# BitterSweet-Model

A machine learning-based model to predict bitterness and sweetness of molecules using molecular descriptors and deep learning.

## 🧪 Title
**Bittersweet: Predicting Molecular Taste using Machine Learning and Deep Learning Models**

## 📄 Description
Taste plays a vital role in food preference and toxin avoidance. Among the five basic tastes, sweetness signals energy-rich nutrients, while bitterness often indicates harmful substances. In this project, we develop a robust ML pipeline to predict the bitterness and sweetness of compounds, overcoming limitations of prior work that focused on binary classification and limited descriptors.

We adopt a **two-way strategy**:
- **Boruta-selected descriptors + ML models** (Random Forest, AdaBoost) for bitter/non-bitter and sweet/non-sweet classification.
- **Neural Networks (NN) and Convolutional Neural Networks (CNN)** for multi-class classification across bitter, sweet, and tasteless categories.

The feature set is curated from over **15,000 molecular descriptors**, and model interpretation is enabled through SHAP-based explanations.

## 📁 Data
All datasets follow the same folder architecture as this repository and can be accessed at the **[link below]** :



> 🔗 **[Dataset Link]** – (https://drive.google.com/drive/folders/1mrl9RhQ27PfHQbEJk7fZ-fN6CBFOCd0F?usp=sharing)

## 📘 Paper
The official paper (under submission) describing this work in detail is attached here:  
📄 [`Bittersweet.pdf`](./Bittersweet.pdf)

## 🛠️ Tech Stack
- Python, Scikit-learn, Keras
- Boruta for feature selection
- SHAP for model explainability
- Deep learning architectures for multi-class classification

## 📊 Performance Summary

| Model      | AUPR  | AUROC | F1    | Accuracy | Sensitivity | Specificity |
|------------|-------|-------|-------|----------|-------------|-------------|
| Random Forest (RF) | 0.9175 | 0.9686 | 0.8631 | 0.9006   | 0.9002      | 0.9394      |
| CNN        | 0.9162 | 0.9357 | 0.8515 | 0.9048   | 0.8571      | 0.8821      |
| NN         | 0.9014 | 0.9326 | 0.8616 | 0.9089   | 0.8634      | 0.9034      |
| AdaBoost   | 0.5841 | 0.7630 | 0.6249 | 0.7453   | 0.6883      | 0.6667      |

---

## 🔍 Citation (once published)
_To be updated upon paper acceptance/publication._

---

