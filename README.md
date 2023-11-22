# MachineLearning

# Assignment 1
**Project Summary: Polynomial Regression for Function Approximation**

**Objectives:**

1. **Estimation of \( \hat{w} \):**
   - **Objective:** Implement a function to calculate \( \hat{w} \) directly from \( X \), \( y \), and a regularization parameter \( \lambda \).
   - **Outcome:** Successful implementation, providing the foundation for further analysis.

2. **Solving for \( n = 3 \) and \( \lambda = 0 \):**
   - **Objective:** Calculate \( \hat{w} \) for a specified polynomial degree (\( n = 3 \)) and regularization parameter (\( \lambda = 0 \)).
   - **Outcome:** Displayed the estimated function \( \hat{y} = X\hat{w} \) alongside given \( y \) values, offering a visual representation of the model's performance.

3. **Grid Search for Best \( n \) and \( \lambda \):**
   - **Objective:** Conduct a grid search to identify the optimal combination of polynomial degree (\( n \)) and regularization parameter (\( \lambda \)) minimizing mean squared error (MSE).
   - **Outcome:** Found the best MSE, providing insights into the impact of different parameters on model accuracy.

4. **3D Visualization of Grid Search Results:**
   - **Objective:** Display results of the grid search in a 3D plot, illustrating the relationship between polynomial degree, regularization parameter, and MSE.
   - **Outcome:** Visualized parameter tuning, aiding in the understanding of the trade-offs involved.

5. **Definition of Function \( f \):**
   - **Objective:** Implement a function \( f(x) \) using obtained \( \hat{w} \) for calculating \( f(x) \) at any given \( x \).
   - **Outcome:** Established a function for future use in predictions.

6. **Visualizing Results:**
   - **Objective:** Load points from the ground truth function \( g \) and visualize results for different \( x \) ranges.
   - **Outcome:** Displayed ground truth \( g(x) \), given data points, and polynomial regression approximation \( f(x) \) in various scenarios.

**Overall Insights:**
   - Dependencies include Numpy and Matplotlib.
   - Instructions provided in a Jupyter Notebook for user interaction.
   - Licensed under MIT License.
   - README.md includes key insights like interpolation vs. extrapolation and limitations of high-degree polynomial regression.

# Project Summary: Linear Regression Analysis for Weather Data

## Code Structure

1. **Data Loading and Preprocessing:**
   - Dataset, "Regression.csv," is loaded and examined.
   - Irrelevant columns are removed, and missing values are handled.

2. **Min-Max Scaling:**
   - Features are scaled using min-max scaling for consistent model input.

3. **Gradient Descent Implementation:**
   - Gradient descent algorithm is implemented for TMax and TMin predictions.
   - Functions for min-max scaling and gradient descent are included.

4. **Training and Evaluation:**
   - Linear regression model is trained and evaluated for TMax and TMin temperatures.
   - RMSE calculated for training and testing sets.

5. **Hyperparameter Tuning:**
   - Fine-tuning of hyperparameters (learning rate, iterations) for optimal performance.

6. **Results Visualization:**
   - Error curves plotted to visualize convergence and performance.

7. **Mean RMSE Calculation:**
   - Mean RMSE calculated over multiple trials for both TMax and TMin.

## Key Insights

- **Impact of Learning Rate:**
  - Crucial; finding a balance between fast convergence and avoiding divergence is essential.

- **Impact of Data Preprocessing:**
  - Careful handling of missing values and normalization significantly influences prediction performance.

- **Impact of Random Initialization:**
  - Initial random weights can affect convergence speed; multiple runs with different seeds reveal model stability.

- **Impact of Iterations:**
  - Critical hyperparameter affecting underfitting and overfitting.

## GitHub Usage

1. **Dependencies:**
   - Ensure dependencies (NumPy, Matplotlib) are installed using:
     ```
     !pip install numpy
     !pip install matplotlib
     ```

2. **How to Run:**
   - Open the provided Jupyter Notebook.
   - Adjust hyperparameters and experiment with different configurations.
   - Run code cells sequentially for insights into model training and evaluation.

3. **License:**
   - Open-source under the MIT License.

4. **Contributions:**
   - Contributions and suggestions welcome; open issues or pull requests.

5. **Acknowledgments:**
   - Acknowledgments for data sources or related works can be included.

## Impact and Considerations

- Adapt for other datasets and regression tasks.
- Understanding hyperparameter impact crucial for successful model training.
- Considerations for data preprocessing and model interpretation highlighted.
