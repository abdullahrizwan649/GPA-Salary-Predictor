# GPA-Salary-Predictor
This project involves building a GPA-Salary predictor using linear regression. The goal is to create a model that can predict salaries based on GPA. The given data consists of GPA values and their corresponding salaries. 

First, the project initializes numpy arrays to store the features (GPA) and target variables (Salary). These arrays are then used to plot the data points using the scatter function from the matplotlib library.

Next, the project defines a model function for linear regression, which takes in input variables, weights (w), and biases (b), and computes the model output using the formula: f(x) = wx + b. The compute_model_output function implements this calculation.

The model function is called with specified values for w and b, and the resulting model output is plotted as a straight line on the graph. The actual data points are also plotted for comparison.

Finally, the model is used to make a prediction for a hypothetical GPA value (3.9), and the corresponding predicted salary is printed.

Overall, this project demonstrates the use of linear regression to build a simple GPA-Salary predictor and showcases the relationship between GPA and salary using data visualization.
