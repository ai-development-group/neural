# neural
Simple Nerual Network wrote in Python using numpy
#Main Code
The main code is in neural.py file. The class neural contains the forward (for getting the predictions) and backward (for training) propagation. One interesting thing I noticed while implementing the code was that the initial values of the weights are really important. (Dont know why but I will read more about it) It seems that if I started with all the weigths being the same and equal to 1 or zero, it will never converges to the desired values but if I started with random values it will converge. Well now that I think about it, it maybe related to the prescence of different minimum and maximums, so my initial value converge to a different value. Still I need to read more about it. Also while coding I made a mistake in the backpropagation method, specifically while propagating the error (the main point right?) I was just propagating the error (predicted_output - desired_output) but it should be error times the derivative of the sigmoid evalutated in the output. 
#Other codes
The other codes were just silly codes to test the main nerual code. Just having fun with it.:) 
