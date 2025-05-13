# Explainable Artificial Intelligence for Obesity Level Estimation: A LIME-based Interpretation of Machine Learning Models

<p align="center">
This repository contains code and experiments related to the use of machine learning models to estimate obesity levels and interpret their predictions using the LIME method.
</p>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- Adicione seu logo aqui, se desejar -->
  <!-- <a href="https://github.com/seu-usuario/seu-repositorio">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a> -->
</div>

<div align="justify">

## 📋 Requirements

* Google Colab
* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* imbalanced-learn
* lime

## 📖 Dataset

The dataset used in this project includes phenotypic and behavioral attributes such as height, weight, physical activity, eating habits, and other lifestyle factors. Each record is labeled with a class representing the obesity level of the individual (e.g., normal weight, overweight, obesity type I, II, or III). The dataset is balanced and publicly available for research purposes.

## 🧠 Machine Learning Models

The following machine learning models were trained and evaluated:

* Extra Trees Classifier
* Random Forest Classifier
* Gradient Boosting Classifier
* Support Vector Classifier (SVC)
* Multi-Layer Perceptron (MLP)

## 📊 Evaluation and Methodology

* Data preprocessing included normalization, encoding, and class balancing.
* Models were evaluated using metrics such as Accuracy, Precision, Recall, F1-Score, and AUC-ROC.
* A stratified split was applied with 80% for training and 20% for testing.
* The LIME (Local Interpretable Model-Agnostic Explanations) method was applied to explain and interpret the predictions of the models.

## 🧾 Research Objective

The main objective of this work is to explain how machine learning models identify different levels of obesity using the LIME interpretability technique. This contributes to increasing trust and transparency in AI systems applied in the medical domain.

## 👏 Contributing

If you find any issues or have suggestions to improve the code or methodology, feel free to contribute or open an issue.

For questions or academic collaborations:  
📧 [Willian de Oliveira Cardoso](mailto:seu-email@exemplo.com)

## 📄 License

This project is licensed under the MIT License or another appropriate license.

## 📚 References

* Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). "Why Should I Trust You?": Explaining the Predictions of Any Classifier.
* Papers on XAI in healthcare and obesity prediction (adicionar conforme necessidade).
