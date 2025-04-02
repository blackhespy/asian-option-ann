# Analysis and Pricing Asian Option with Artificial Neural Network
## Abstract <d1/>
Pricing an Asian option with an arithmetic average is interesting because there is no analytical solution. Usually, pricing such
options uses numerical methods, one of which is the Monte Carlo method. This method’s weakness is the computation time length
because it must generate many trajectories of asset price movements. This paper uses a data-driven approach through the Artificial
Neural Network (ANN) method that can speed up computation time. The ANN method requires input and target data sets from
Levy’s approximation solution, Monte Carlo with antithetic variables, and Quasi-Monte Carlo. The ANN method learns the data
from these three data sets to form each model that can accept the input of option parameters to determine the price. The most
crucial thing in ANN models is the model architecture, such as assessing the number of neurons, layers, and the use of activation
functions. This paper presents several simulations to determine the best model architecture based on the smallest Mean Squared
Error (MSE). In addition, the evaluation of the three ANN models that have been built shows that each model is optimal based on
the smallest MSE and a coefficient of determination close to one. This paper also shows that option pricing using the ANN method
is more efficient than the Monte Carlo method.

Keyword: Asian Option, Artificial Neural Networks, Levy’s Approximation, Quasi Monte Carlo, ANN
