# Facies-Classification-ML
Prediction of Facies Classification using Machine Learning in the Hugoton and Panoma Fields in Southwest Kansas

The use of machine learning in geoscience data is based on growing of volume and increasing data types so that it makes a challenge to be able helping geoscientists automate their work. Prediction using the machine learning method produces non-unique results because it depends on the condition of the input data (features) which contain a lot of noise or the selection of various features. This study aims to predict facies classification using the supervised learning algorithm k-nearest neighbors, random forest and support vector machines in the Hugoton and Panoma fields in Southwest Kansas. Six wells are used as training data for the model in order to learn then it could predict one well of testing data. The conditioning data used to remove outliers or noise in data log are clipping filter and median filter. Data is also transformed into a non-linear form, therefore there are various features to be selected into 5 experimental scenarios based on the features of the facies correlation coefficient value. The results show the use of the most optimal features is in the fifth scenario which produces the highest accuracy in the random forest algorithm, then followed by k-nearest neighbors and support vector machine.

Keywords: accuracy, classification, feature, filter, machine learning, KNN, Random Forest, SVM

flow chart to get know more about this project:
1. Data
It provides raw data of the project which get from SEG Open Source Data
2. Well Log Display
It started from analyze raw data into well log display to get information of wells. It will give information to do QC using filtering method
3. Facies Distribution
It will give information about subsurface condition along wells
4. Filtering
Filtering data is most important flow in this project, it accelerate machine learning result
5. Maachine Learning Scenario
There are 3 types of supervised machine learning in this project. K-NN, Random Forest, and SVM is compared by 5 scenarios which related to input variable.
