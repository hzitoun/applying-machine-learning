Applying the most used machine learning techniques to real world problems using public datasets. 
Libraries used:
- Python 🐍 (v > 3)
- Scikit-learn
- Pandas
- Numpy
- Scipy
- Matplotlib 
## 1 Diabetes Analysis:
Dataset of diabetes, taken from the hospital Frankfurt, Germany https://www.kaggle.com/johndasilva/diabetes 
### Threshold
We consider patient to be sick if the predicted value is higher than **0.8**
### Results:
- 3 Layers Neural Nets: **Acurray**: 77%, **F1 Score**: 51%
- SVM with Linear Kernel : **Accuracy**: 76%, **F1 Score**: 74%
- Logistic Regression: **Acurray**: 72%, **F1 Score**: 49%
- KMeans (clusters=2) : **Accuracy**: 69%, **F1 Score**: 39%

