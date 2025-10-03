## Description
This repository demonstrates how repeated random sampling converges to true population parameters, using the Customer_Age variable from Kaggle’s Predicting Credit Card Customer Attrition dataset. The Jupyter Notebook calculates the population mean and standard deviation, then repeatedly draws bootstrap samples of fixed size. For each set of samples, it computes sample means and standard deviations, compares them to the population values, and visualizes the differences as the number of samples increases. The resulting plots clearly illustrate the Law of Large Numbers and the Central Limit Theorem (CLT) in practice—showing how randomness stabilizes into reliable estimates with enough repetitions.# Parameter_Estimation

The Jupyter Notebook performs the following steps:

1. **Population Statistics**  
   - Calculates the population mean and standard deviation for `Customer_Age`.

2. **Sampling Process**  
   - Draws repeated bootstrap samples (with replacement) of fixed size.  
   - Computes sample means and standard deviations.  

3. **Comparison with Population Values**  
   - Tracks the difference between sample estimates and true population parameters.  
   - Stores results in a tidy DataFrame.  

4. **Visualization**  
   - Plots the differences in mean and standard deviation as the number of samples increases.  
   - Shows how estimates converge toward the population truth.

The results provide a clear demonstration of the **Law of Large Numbers** and the **Central Limit Theorem (CLT)** in practice—illustrating how randomness stabilizes into reliable estimates as the number of samples grows.
