# Detecting Bearing Faults in Motors
### The rising use of smart sensors on the assembly line has resulted in the accumulation of datasets that can reveal important information about machine health. Signals data of motor systems are analyzed by extracting useful features from the plethora of signals data recorded. Multiple time and time-frequency domain features are among the features extracted from raw signal data. Statistical features also extracted such as mean, standard deviation, and the others. 14 features in total extracted from the raw data of more than 50000 signals. The target label, which is the bearing fault, is of 3 types, 0,1 and 2. Th3 stratified Kfold validation was used, and the metrics used were the accuracy score and f1 score. 3 machine learning models were used for the modeling, the support vector machine, Decision tree, and random forest algorithm. The random forest achieved the highest score with 52.2% accuracy and 51.6% f1 score. The various hyperparameters of the random forest were tuned, and the optimized model achieved an accuracy of 52.5% and an f1 score of 51.8%. The feature importance to determine the features that contribute most to determining bearing fault was constructed, and absolute mean, var and rms were the top 3 features. Some of the features that contributed very little to determining bearing fault, were removed and the model was improved by about 1%. The information from this is crucial for the manufactures since vibration signal data is a vital and dependable indicator of machine health that can help us better understand the many issues that can arise from it.
## Libraries used:
### Pandas
### Numpy   
### Matplotlib
### Seaborn
### Scikit-Learn
### Scipy
