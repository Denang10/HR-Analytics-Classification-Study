# HR-Analytics-Classification-Study

Predicting data scientists' likelihood to switch jobs using survey data. **Random Forest: 84.15% accuracy, 0.8415 ROC-AUC** (ordinal encoding). [Colab Demo](https://colab.research.google.com/github/[yourusername]/job-change-prediction/blob/main/ML_Project_Final_v1.4.ipynb)

## 📊 Key Results

| Model | Encoding | Accuracy | ROC-AUC |
|-------|----------|----------|---------|
| Gradient Boosting | Ordinal | **84.34%** | **0.8434** |
| **Random Forest** | Ordinal | 84.15% | 0.8415
| Random Forest | One-Hot | 84.04% | 0.8404 |
| KNN | One-Hot | 79.51% | 0.7951 |

**Feature Importance**: City dev index (~0.44 corr), company not provided (~0.15 corr), training hours (~0.12 corr).

## 🎯 Insights
- **1st-year flight risk**: 42% switch rate drops post-tenure.
- **Geography gap**: 58% risk in low-dev cities vs 25% high-dev.
- **Education paradox**: Graduates (28%) > PhDs (14%) attrition.

## 🚀 Quickstart
```bash
# Clone & run
git clone https://github.com/Denang10/HR-Analytics-Classification-Study
pip install -r requirements.txt
jupyter notebook ML_Project_Final_v1.4.ipynb
```

**Data**: [Kaggle HR Analytics (19k rows)](https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists)

## 🤝 Team
CSC1181 group project. **I implemented**: EDA, ordinal encoding, SMOTE, hyperparameter tuning, RF/GB modeling.

**Group II Members:**
Angelo Miculescu, 
Nikhil Verma, 
Stanley Masaku, 
Yuvashree Ponnurangan


## License
MIT
