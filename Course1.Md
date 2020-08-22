#### Neural Networks
Tanh bettter than sigmoid. Relu and its variant are even better.  
Sigmoid to be used when 0 or 1 and in the end layer only.  
If non linear function is not used then no matter how large the network at the end it is equivalent to some linear combination.  
WX not WTX, when propgating forward.  
Dimensions of W - N_l* N_l-1, where N_l denotes the number of neurons in the layer l, B - N_l * 1, Z - N_l * m(training samples).  
