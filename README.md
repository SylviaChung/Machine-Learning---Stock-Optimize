Clicke here to have access to full report:https://docs.google.com/document/d/1tMg09din1mikhNL59yXyrgslmvz3L_OJpmF93S7NlfU/edit?usp=sharing

---------------------------------------------------------------------------------------------------------------------------
# Use Machine-Learning for Stock Portfolio Optimization Models
In the financial field, investors usually have the right to restructure their investment portfolios based on different stock selection concepts (such as large book-to-market ratio, large return on equity, etc.) to optimize investment returns. However, the traditional weighted scoring stock selection model has the following three major flaws:

Unable to identify a relationship between stock selection concept weights and portfolio performance.
Unable to systematically find the best combination of weights to optimize performance.
Unable to meet the individual preferences of different investors.

Therefore, in order to solve these problems, we aim to develop a stock selection model with a higher weight score, effectively using  Simplex Centroid Mixture Design and Artificial Neural Network (ANN) to simulate investment performance and optimize weight configuration.

# Turn business problems into machine learning solutions
![image](https://github.com/user-attachments/assets/95df37db-2083-4f37-a8b1-3d1d4021b5f6)

# Find a suitable data set
use a dataset from UC Irvine(https://archive.ics.uci.edu/dataset/390/stock+portfolio+performance). The data set of performances of weighted scoring stock portfolios are obtained with mixture design from the US stock market historical database.

# Data preparation : clean the data 
Check data type, Check for missing values, Check for outliers, Duplicate value check, Standardize features, Remove useless features

# Features engineering
Step 1 : Multi-target output variable processing
Step 2 : Use multi-objective regression methods to build artificial neural network models that can predict multi-dimensional outputs simultaneously.
Step 3 : Data partition
divided into a training set (80%) and test set (20%) for model evaluation

# Model selection 
-- Phase 1 : Model Selection
Performance prediction models were built with the simulated performance data set and artificial neural networks. Use Artificial Neural Network (ANN) as the core prediction model for the following reasons:
a) It helps to capture the complex non-linear relationship between weights and investment performance.
b) It’s scalable, which is suitable for multi-objective regression tasks.

--Phase 2 : Model Building
5 steps: Input layer > Hidden layer > Output layer > Loss function > Optimizer

--Phase 3 : Model Validation and Hyperparameter Tuning

# Cross validate the model and pick the hyperparameters 
use optimization algorithms such as Markowitz Mean-Variance Optimization or modern techniques like Genetic Algorithms or Simulated Annealing, to optimize the investor preferences




