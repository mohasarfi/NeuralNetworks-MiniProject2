# NeuralNetworks-MiniProject2
Second mini project of the Neural Networks and Deep Learning course instructed by Dr.Kalhor,School of Electrical and Computer Engineering, University of Tehran\
Following Topics have been covered in this project
* Question 1 : Next frame prediction
  First animation of a simple pendulum  is created with respect to its dynamic equations. Then the next probable position of this pendulum  is predicted 
  using a CNN-LSTM network. This end to end network is consisted of three parts. First one is the Encoder used for feature extraction and dimensionality reduction. 
  LSTM is the second part where prediction occurs based on the previous frames(Memory neural network). The obtained result is the probable position of the pendulum but it's in the 
  compact form. Therefore a Decoder network should be used in the final stage in order to illustrate pendulum in a sensible manner. Our final End to End network is capable of 
  predicting the next 50 frames just based on the 10 first frames.
* Question 2 : Stock market prediction
  In this Question three different types of memory networks(RNN, LSTM and GRU) are used for the google stock prediction. The results prove that LSTM predicts more precisely
  compared to other networks.
  
