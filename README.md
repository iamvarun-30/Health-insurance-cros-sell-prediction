# Health-insurance-cros-sell-prediction

The aim of the project is to make sure that the people who have aleady brought the health insurance will also go likely to buy the vehicle insurance. The health insurance is kind of a compensation that is being provided by the company in regard for some premium in case of Death, illness or any accidents.
This model is a classification model, that focuses to understand the target variables from the idea that the whether the people have responded yes or no, considering all the demographics like age, gender, vehicle' s age, the person has driving license or not , the amount of annnual premium they pay, all of this things are responsible for giving the responses.  





I have done EDA( Exploratory data analysis) where I have plotted various charts such as count plot, barplot, piechart, etc. to show the relations of the target variable to other independent variables. Showcased the bivariate analysis of the project . After that, I have done feature manipulation and feature importnace chart with the help of the feture importance chart .I have plottted the correlation heatmap to better understand the correlation between the variables.



Talking about the ML algorithms, the main algorithms that I have used are -

Logistic Regression

Random Forest

Decision Tree classifier

XGBoost


I have trained the dataset on all of the algorithms after handling the imbalance relationhip of the target variables with the help of the SMOTE analysis.


The major metrics that I have used are-

Precision score


 Recall Score

confusion matrix

ROC_AUC score

Accuracy score
                                                                  precision    f1              recall     accuracy   ROC_AUC

Logistic Regression                                              	0.977323	    0.255166  	   0.404676  	0.653248	0.793066

Logistic Regression after tuning	                                0.977690	   0.255182    	0.404728	  0.653193	  0.793193

Random Forest	                                                    0.327580	   0.336858    	0.332154	  0.841150	  0.619576

random forest after tuning	                                       0.921594	    0.287745	    0.438561	  0.715458	0.804393

Decision Tree                                                     	0.320143	  0.294759    	0.306927	  0.825650	0.607555

XGB Classifier	                                                    0.434355	  0.362418	   0.395139	   0.839644	  0.664787

XGB Classifier after tuning	                                       0.933346 	  0.282263	  0.433444	 0.705770	     0.803955

