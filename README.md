# random_forest_explore

## data
### data_cropped.csv - cropped (n = 100) data of the original 999 outbreak dataset, with outbreak attack rate and corresponding covariate values 
### covariate_metadata.csv - includes the covaraite column name and a more descriptive label for plotting

## sandbox 
### rf_explore.Rmd - includes ROC and AUC to test the performance of the covariates against a binary classifier, attack rate >mean (1) or <mean (0) 
### rf_explore2.Rmd - includes code for testing model covariate combinations to find the best fit, covariate effect plots e.g., PDP and marginal effects and additional random forest tuning. 
### rf_explore3.Rmd - allows the random forest to set its own best fit, with code to test performance and additional tuning

## notebook
