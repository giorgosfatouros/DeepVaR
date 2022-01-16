# DeepVaR
Portfolio Risk Assessment leveraging Probabilistic Deep Neural Networks

This notebook both explains and implements the DeepVaR, which is a Value-at-Risk model based on deep neural networks and Monte Carlo simulations.
The DNN is used to estimate the parameters of the portfolio returns' distribution, which are used to produce the MC samples. 
As far as the DNN is concerned, the DeepAR estimator from GluonTS package is utilized in order to perform probabilistic forecasts, 
while the VaR is calculated leveraging DeepAR's output.

This model was developed in the scope of H2020 INFINRTECH project
