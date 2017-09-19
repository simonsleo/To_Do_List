# To_Do_List
remove them asap
1. lgmhead and laptop, cuDNN needed.
```
Using gpu device 0: Tesla P100-SXM2-16GB (CNMeM is disabled, cuDNN not available)

```
fixed

2. office,device gpu is  not available.
```
>>> import theano
WARNING (theano.sandbox.cuda): The cuda backend is deprecated and will be removed in the next release (v0.10).  Please switch to the gpuarray backend. You can get more information about how to switch at this URL:
 https://github.com/Theano/Theano/wiki/Converting-to-the-new-gpu-back-end%28gpuarray%29

WARNING (theano.sandbox.cuda): CUDA is installed, but device gpu is not available  (error: Unable to get the number of gpus available: CUDA driver version is insufficient for CUDA runtime version)

```

3. how to do fine-tunning in machine learning

https://www.evernote.com/shard/s118/nl/13408391/4b71e179-2ec8-4828-9f94-26c5403d5e62/

4. regression based on multivariate time series

https://medium.com/@alexrachnog/neural-networks-for-algorithmic-trading-2-1-multivariate-time-series-ab016ce70f57

5. What is the connection between Multi-level Clustering, time blocks referred in the book and multi-scale CNN?

The book "Time－Series_Prediction_and_Applications_－__A_Machine_Intelligence_Approach" 
The author proposed dynamic stochastic automaton to predict the time series. state transition is used to predicit time series??
What is the theory?

6. how to define the prediction error of time series.

7. Time series forcasting with python

Deep Time Series Forecasting with Python 
http://www.doc88.com/p-2972802120200.html

8. Neural Networks for Conditional Probability Estimation

https://www.springer.com/gp/book/9781852330958
Conventional applications of neural networks usually predict a single value as a function of given inputs. In forecasting, for example, a standard objective is to predict the future value of some entity of interest on the basis of a time series of past measurements or observations. Typical training schemes aim to minimise the sum of squared deviations between predicted and actual values (the 'targets'), by which, ideally, the network learns the conditional mean of the target given the input. If the underlying conditional distribution is Gaus­ sian or at least unimodal, this may be a satisfactory approach. However, for a multimodal distribution, the conditional mean does not capture the relevant features of the system, and the prediction performance will, in general, be very poor. This calls for a more powerful and sophisticated model, which can learn the whole conditional probability distribution. Chapter 1 demonstrates that even for a deterministic system and 'be­ nign' Gaussian observational noise, the conditional distribution of a future observation, conditional on a set of past observations, can become strongly skewed and multimodal. In Chapter 2, a general neural network structure for modelling conditional probability densities is derived, and it is shown that a universal approximator for this extended task requires at least two hidden layers. A training scheme is developed from a maximum likelihood approach in Chapter 3, and the performance ofthis method is demonstrated on three stochastic time series in chapters 4 and 5.
