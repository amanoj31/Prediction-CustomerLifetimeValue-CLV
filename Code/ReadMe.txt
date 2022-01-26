Note:
Notebooks and Datasources
A. Creating Features and Final Datasets
A1.	
	'Feature Creation and EDA.Rmd' : Feature Creation, 
	input: 'Online Retail.csv',
 	output: 'final_data.csv'	
A2.	
	'2nd_months_predicting_variables.Rmd' : Future Scoring Dataset, 
	input: 'Online Retail.csv',
 	output: '2nd_months_predicting_variables.csv'
	

B. Inital Analysis and Train Test Creation
B1.	
	'Initial Analysis and Test-Train Split.Rmd' : Initial Analysis, 
	input: 'final_data.csv',
	Output: 'train3.csv','test.csv'


C. Regression Analysis and Results
C1.	
	'Final Analysis and output.Rmd' : Final Analysis, 
	input: 'train3.csv','test.csv', '2nd_months_predicting_variables.csv'
	Output: 'output_test_predictions_results_comparison.csv','output_variable_selection.csv','output_goodness_of_fit.csv'