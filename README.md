
# 📱 Spam SMS Classification with Naïve Bayes  

This repository contains a **Machine Learning mini-project** designed for students to practice both the **theory and implementation** of Bayesian classifiers using the well-known [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data).  

## 📌 Project Overview  
The goal is to classify SMS messages as **Spam** or **Ham (legitimate)** using different versions of the **Bayes classifier**.  
Students are expected to explore the dataset, implement classifiers from scratch, and compare results with scikit-learn implementations.  

## 📝 Tasks  
1. **Dataset Exploration**  
   - Analyze and describe the dataset.  
   - Visualize message length distributions for spam vs. ham.  
   - Generate word clouds for spam and ham messages.  

2. **Bayesian Classifiers**  
   - Explain and compare **Naïve Bayes** vs. **Optimal Bayes**.  
   - Discuss which type of Naïve Bayes (Gaussian, Multinomial, Bernoulli) is best for this dataset.  

3. **Implementation**  
   - Implement a Naïve Bayes classifier **from scratch** (no ML libraries).  
   - Train and evaluate classifiers with **scikit-learn**.  
   - Compare confusion matrices, accuracy, precision, and recall with your manual implementation.  

4. **Theoretical Analysis**  
   - Prove why the Bayes decision rule minimizes classification error.  
   - Extend the classifier with a **cost-sensitive risk function** (e.g., misclassifying spam as ham costs 5x more).  

## ⚙️ Requirements  
- Python 3.8+  
- Libraries:  
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn wordcloud
