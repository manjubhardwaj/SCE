# SCE
An SVM-based Ensemble Technique
Self Chastising Ensemble (SCE) is an SVM-based classification ensemble technique, designed to handle two-class classification problems with numeric attributes only. The algorithm has been tweaked to handle imbalanced datasets.
Input: a) Dataset in LIBSVM format,
       b) SVM Kernel to be used, 
       c) Kernel parameter values, 
       d) #Folds to be generated for Dataset,
       e) #SVM Classifiers to be generated
Output: CV-Performance Metrics (Precision, Recall, F-measure, Accuracy, g-mean) 
