# Methodology
Upload your methodology description here

How should we deal with the strongly right skewed data?
- After discussion with professor we decided to delete all the cases with grade of zero, and cases with unreasonably extreme data 
- Then we will change our research aim to find what and how features are correlated with students’ grades for online courses given they finished assignments.
      - We have two options of methodology. We decided to compare two methodologies.
            - Method 1: More traditional regression model with cross validation. Base on our visualization, the regression would be linear. 
                   - Assumption for linear regression:
                    - Linear relationship
                    - Multivariate normality
                    - No or little multicollinearity
                    - No auto-correlation
                    - Homoscedasticity
        - Method 2:  Classification And Regression Tree (CART) analysis
         -Assumption: there's no distributional assumption for data.
- Validation
      - we'll use cross validation techinique.We'll generate a model for one class. And then we'll apply it to other classes and see whether it can also fit well. 

Next week:
 Clean the data, do the deletion 
 Study how to use R to produce Scatter Plots and Correlation Matrix

