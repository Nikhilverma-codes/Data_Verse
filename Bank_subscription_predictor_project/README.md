# 💼 Bank Subscription Classifier (Logistic Regression)

This project uses **Logistic Regression** to predict whether a client will subscribe to a term deposit based on marketing campaign data from a Portuguese bank.

## 📊 Dataset
- **Source**: UCI Bank Marketing Dataset
- **Target Variable**: `y` (Subscribed: yes/no)
- **Features**: Age, job, marital status, balance, previous campaign outcomes, etc.

## 🔍 Project Highlights
- Handled **class imbalance** using upsampling
- Preprocessed categorical and numerical features
- Trained a **Logistic Regression** model
- Evaluated with **confusion matrix**, **precision**, **recall**, and **F1-score**

## 📈 Final Results
- **Accuracy**: ~64.6%
- Balanced precision/recall for both classes after upsampling

## 🛠️ Tools & Libraries
- Python, pandas, scikit-learn, matplotlib, seaborn

## 📁 Files

- [`bank.csv`](https://github.com/Nikhilverma-codes/Data_Verse/blob/main/Bank_subscription_predictor_project/bank.csv): Dataset used for training and evaluation  
- [`Bank_subscription_classifier.ipynb`](https://github.com/Nikhilverma-codes/Data_Verse/blob/main/Bank_subscription_predictor_project/Bank_subscription_classifier_project.ipynb)  
- `README.md`: Project overview and documentation

## 📌 Future Improvements

- Experiment with other classifiers like **Random Forest**, **XGBoost**, etc.  
- Perform **hyperparameter tuning** to optimize model performance  
- Apply **feature selection** and **regularization** for better generalization

### 🙏 Acknowledgements

Thanks to the UCI Machine Learning Repository for the dataset and the open-source community for the amazing tools that made this project possible.
