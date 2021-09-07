# ML-model-analyze-of-Parkinson-s-Disease

## abstract:
For many years, lots of people have been suffering from Parkinson’s disease all over the world, and some datasets
are generated by recording important PD features for reliable decision-making diagnostics. But a dataset can contain correlated
data points and outliers that can affect the dataset’s output. In this work, a framework is proposed where the performance of an
original dataset is compared to the performance of its reduced version after removing correlated features and outliers. The
dataset is collected from UCI Machine Learning Repository, and many machine learning (ML) classifiers are used to evaluate its
performance in various categories. The same process is repeated on the reduced dataset, and some improvement in prediction
accuracy is noticed. Among ANOVA F-test, RFE, MIFS, and CSFS methods, the Logistic Regression classifier along with RFEbased feature selection technique outperforms all other classifiers.
We observed that our improved system demonstrates 82.94% accuracy, 82.74% ROC, 82.9% F-measure, along with 17.46%
false positive rate and 17.05% false negative rate, which are better compared to the primary dataset prediction accuracy metric
values. Therefore, we hope that this model can be beneficial for physicians to diagnose PD more explicitly

## Structure:
```
📁 ML-model-analyze-of-Parkinson-s-Disease/
├─ 📁 Dataset/
├─ 📁 Result/ 
├─ 📁 Source code/
─
```
## Contents:
  1. [Dataset](https://github.com/iamfahim/ML-model-analyze-of-Parkinson-s-Disease/tree/main/Dataset)- is a folder that contains the dataset for `Parkinson-s-Disease-ML-Model-analyze-project`.
  2. [Result](https://github.com/iamfahim/ML-model-analyze-of-Parkinson-s-Disease/tree/main/Result)- is a folder that contains the results obtained from dataset.
  3. [Source code](https://github.com/iamfahim/ML-model-analyze-of-Parkinson-s-Disease/tree/main/Source%20code)- is a folder that contains the all the codes. 
  

## How to run:
  1. Clone the repository from [here](https://github.com/iamfahim/ML-model-analyze-of-Parkinson-s-Disease.git) and the Dataset from [here](https://github.com/iamfahim/ML-model-analyze-of-Parkinson-s-Disease/tree/main/Dataset)
  2. Extract the files.
  3. Open `Google Colab` or `Jupyter Notebook` or `Python Spyder`.
  4. Copy any code and Set your working directory using 
                
                ```
                import os
                
                #Please specify your dataset directory. 
                os.chdir("..../Dataset/")
                ```

