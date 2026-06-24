# Stroke Prediction: Traditional ML vs Deep Learning

A summative ML project comparing four classical models (Logistic Regression, Random Forest, Gradient Boosting, SVM) against three TensorFlow architectures (Sequential, Functional Wide & Deep, tf.data pipeline) on the Kaggle Stroke Prediction Dataset.

**Author:** Alain Ishimwe NGABO · African Leadership University, Rwanda

---

## 🔗 Links

- 📓 **Notebook:** [stroke_prediction_notebook.ipynb](https://docs.google.com/document/d/1L-YNVqiYJ3jNebKS6dVB35DA15_lsCBGZvXLXRtODEc/edit?usp=sharing)
- 🎞️ **Demo Video:** [Demo video Link](https://youtu.be/gE2ZLa-64BQ)

---

## 📦 Dataset

Kaggle — [Stroke Prediction Dataset (fedesoriano)](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)  
5,110 patients · 10 clinical features · 4.87% stroke prevalence.

---

## 🚀 Run the Notebook

```bash
pip install kagglehub[pandas-datasets] scikit-learn tensorflow imbalanced-learn matplotlib seaborn
jupyter notebook stroke_prediction_notebook.ipynb
```

> Set up your Kaggle API key at `~/.kaggle/kaggle.json` to auto-download the dataset.

---

## 📊 Key Result

Logistic Regression won with **AUC = 0.839** and **Recall = 0.78**: catching 39 of 50 actual stroke patients in the test set. The Wide & Deep Functional API was the strongest deep model (AUC = 0.828).
