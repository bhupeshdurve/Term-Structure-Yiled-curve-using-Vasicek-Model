# Term-Structure-Yiled-curve-using-Vasicek-Model



his repository contains Python code that implements the Vasicek Interest Rate Model. The Vasicek model is a mathematical model describing the evolution of interest rates over time. The model is widely used in finance for interest rate modeling and derivative pricing.

Usage

**Model Parameters**
The Vasicek model is defined by the following parameters:
drt = alpha(gamma - rt )d_t +sigma(d(z_t))

gamma: Long-term mean of the interest rate.
alpha: Speed of mean reversion or kappa.
sigma: Volatility of the interest rate.
dt: Time step size.


**Data**
The script retrieves monthly Treasury interest rate data using the pandas_datareader library. The data is then used to plot the interest rate graph.

**Maximum Likelihood Estimation (MLE)**
The script employs the Maximum Likelihood Estimation method to estimate the model parameters (alpha, gamma, and sigma) based on the observed interest rate data.

**Simulation**
The code simulates both the short-term interest rate process and the term structure using the estimated model parameters. It includes functions to simulate the short-term interest rate process and the term structure of zero-coupon bonds.

**Results Visualization**
The results are visualized through various plots:

Interest Rate Graph: Plot of monthly Treasury interest rates.
Short-Term Interest Rate Process: Simulation of the short-term interest rate process over time.
Term Structure: Plot of the term structure based on simulated bond prices and yields.
Feel free to modify the parameters, time periods, or other inputs in the script to explore different scenarios.






