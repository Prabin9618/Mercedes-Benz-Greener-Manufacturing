# Mercedes Benz Greener Manufacturing

### Problem Background:
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with the crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz cars are leaders in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.
To ensure the safety and reliability of every unique car configuration before they hit the road, Daimler’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Daimler’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.

### Objective:
It is required to reduce the time that cars spend on the test bench and working with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.

### Data Dictionary:
Field | Description
--- | ---
y | Output variable
X0 - X9 | One letter variable signifying characteristics of car model
X10 - X385 | Values in 0s and 1s

### Steps performed:
1. Checking for variance and removing columns with zero variance
2. Pre processing, cleaning dataset
3. Applying label encoder for categorical variables
4. Performing dimensionality reduction
5. Predicting test_df values using XGBoost regressor algorithm
