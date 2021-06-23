# ML_End_to_End_project_creditCardDefaulters
Full stack ML project with end to end pipeline. 

Problem Statement													
To build a classification methodology to determine whether a person defaults the credit card payment for the next month. 													

KNN 	kneed import KneeLocator
Models	XGBoost and GaussianNB with HyperParameter tuming trained for each cluster and best model with best parameters are choosen for each cluster 

	
Feature Engineering
Scaling	Standard Scaler
Encoding	data['target'].map({target1: 0, target2: 1…..})
handle ImbalanceDataset	"sample = SMOTE()
sample.fit_resample(X, y)"


