# mackey-glass-system
implementation of mackey glass system. 


the system results are then shifted and squashed with tanh() function to have a range between -1 and 1.


an input_ and output_ is created to be used in training. 


input can have a shift backwards using a paramter, which could be used in tasks which the model predicts n-step ahead target.


a test_input and test_output is created to be used in testing. 
 
test data mentioned above is the training data augmented with further system responses. 

<img src="https://user-images.githubusercontent.com/50669689/189479258-7ee9bceb-49e9-4477-8262-41a088790711.png" width="300" height="300">

