# House-Prices

## Approach

The work was split up into two seperate workbook files:
- Data_Processing_and_EDA.ipynb
- Model.ipynb

This file structure was utilised so that the dataset could be thoroughly analysed and processed, as well as to add modularity and aid in readability. 

The following models were evaluated to identify the best-suited model for the dataset:
- Linear Regression
- Scaled Linear Regression
- Lasso Regression
- Second-degree Polynomial Regression
- Decision Tree
- Random Forest

Hyperparameter tuning was conducted using scikit-learn's 'GridSearchCV' and 'RandomisedSearchCV' functions,.

Evaluate all models using, key metrics (including R-squared and Mean Absolute Error) and visualisations.


### Data processing
- Key take aways
  
### EDA
- Key take aways


### Models

## Graphs

## Evaluation table

|       Algorithm         | R2 Training Accuracy | R2 Validation Accuracy | MAE Training Accuracy | MAE Validation Accuracy |
| ------------------------- | ------------- | ------------- | ------------- | ------------- |
| Linear Regression         | 0.829198	    | 0.650785	    | 21077.066551  | 24909.080194  |
| Scaled Linear Regression  | 0.780732	    | 0.826103	    | 22503.308689	| 22574.392352  |
| Lasso Regression          | 0.829198	    | 0.650772	    | 21076.750588  | 24908.739164  |
| Second-degree Polynomial  | 0.933185	    | 0.723125	    | 14599.744518  | 21971.565993  |
| Decision Tree             | 0.811926	    | 0.786335	    | 24906.906021  | 25942.917001  |
| Random Forest             | 0.979563	    | 0.859481	    | 6888.674690	  | 18265.270063  |
| Grid Search RF            | 0.960858	    | 0.817013	    | 8402.097840	  | 18349.898467  |
| Randomised Search RF      | 0.959223	    | 0.811049	    | 8327.449120	  | 18642.484215  |
