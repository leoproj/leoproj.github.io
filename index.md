Learning to Tune Compiler Optimizations for Symbolic Execution Acceleration
---
*Under Construction*  

###<h2 id="1"> Data </h2>

The experimental data and source can be downloaded from the following link.   
[Download](./file/leo.zip)   


ReadMe: 

After downloading, there are two folders in the package: data and source   
   
For data:   
   
	This folder saves the results of our experiments:   
		Comparison.xlsx: saves comparison results among LEO, ALL and NO   
		LEO-A/B/C/D.csv: saves the results of LEO's four variants   
		Machine-learning.xlsx: saves the results of LEO with different machine learning algorithms  
		lib-prediction: saves the prediction results of the libraries each subject used
		method-prediction: saves the prediction results of each method in each subject
   
   
For source:   

	This folder saves the code of our implementations:   
		predicttest-smo-31-smote-new.jar & predicttest-smo-31-smote-trained.jar: implement SMOTE and SMO algorithms
		predict_method.py: implements to predict the compiler optimization settings for each method in each subject
		predict_lib.py: implements to predict the compiler optimization settings for the libraries each subject used
		runklee.py: implements to apply our prediction results to analyze each subject using KLEE  
		splitter+optimizer: contains the implementations of the program-splitter and method-optimizer, and also contains corresponding scripts for using the tools 		 	
		