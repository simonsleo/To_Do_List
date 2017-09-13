1. The authors make use of Deep convolutional Nerual Networks to predict financial markets.
There are three categories, price moving up,unchanged,moving down. In order to deal with time series  as a classification 
frame, they apply walk-forward method, cutting the time series into small pieces, both of which may overlap, 
sliding a window with a certrain width to get the training data. Therefore  a time series would be tranformed many training 
sub-samples with a clasa(1-up,0-unchanged,-1-down).

Classification-based Financial Markets Prediction using Deep Neural Networks
https://arxiv.org/abs/1603.08604

2. Dilated CNNs

They also use 'reflection padding' to fill the buffer zone by reflect the image about each edge.
dilation in the convolutional layers  to increase its receptive field
Multi-Scale Context Aggregation by Dilated Convolutions
https://arxiv.org/abs/1511.07122

3. Camparison of dilated CNN and factorisation 

http://www.inference.vc/dilated-convolutions-and-kronecker-factorisation/

