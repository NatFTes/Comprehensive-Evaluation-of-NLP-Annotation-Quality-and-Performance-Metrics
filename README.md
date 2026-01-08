# Sentiment Classification with Annotation Protocols

This project explores the impact of annotation quality on sentiment classification.  
Using a dataset of 5,000 samples, we simulate annotator disagreement, apply refined consensus heuristics, and measure how annotation agreement affects downstream model performance.  

- **Annotation Agreement Analysis**: Cohen’s Kappa improved from ~0.6 (moderate) to 1.0 (perfect) after applying consensus rules.  
- **Model Training**: Implemented a simple yet effective pipeline with **TF‑IDF + Logistic Regression**.  
- **Performance Metrics**: Achieved **Accuracy = 0.751** and **F1 Macro = 0.751**, showing balanced results across positive and negative classes.  
- **Storytelling & Documentation**: Includes comparative tables and diagrams to illustrate how annotation quality directly impacts model reliability.  
- **Portfolio Value**: Demonstrates a full NLP workflow — from annotation and agreement to model training and evaluation.

---

## 📑 Table of Contents
- Data subset & Cleaning
- Simulation of scorers and calculation of Cohen's Kappa.
- TF–IDF & Logistic Regression

---

## 🧰 Technologies and Tools
- Python
- pandas
- numpy
- random
- matplotlib
- scikitlearn
- Supervised Classification in NLTK

------

## 📂 How to Use This Repository

You can explore the full analysis, visualizations, and conclusions in the PDF document:  
**[Comprehensive..](https://)**  
This version was exported directly from the original Jupyter Notebook using LaTeX.

To explore the original datasets, refer to the links mentioned in the PDF report.
