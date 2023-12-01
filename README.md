# random_forest_explore

## data
Folder for all data needed to run the markdown in the notebook folder 
- data_cropped.csv - cropped (n = 100) data of the original 999 outbreak dataset, with outbreak attack rate and corresponding covariate values 
- covariate_metadata.csv - includes the covaraite column name and a more descriptive label for plotting

## sandbox 
Previous markdowns which are no longer in use
- rf_explore.Rmd - includes ROC and AUC to test the performance of the covariates against a binary classifier, attack rate >mean (1) or <mean (0) 
- rf_explore2.Rmd - includes code for testing model covariate combinations to find the best fit, covariate effect plots e.g., PDP and marginal effects and additional random forest tuning
- rf_explore3.Rmd - allows the random forest to set its own best fit, with code to test performance and additional tuning

## notebook
Current markdown being used 
- rf_explore4.Rmd - markdown for random forest covariate selection and model fitting. The markdown includes 6 sections: 1, data visualisation, 2, data distribution, 3, correlations and clustering, 4, finding the best fit model, 5, testing the best fit model and 6, extracting the variable importance 
