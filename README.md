# mackey-glass-system
implementation of mackey glass system. 
the system results are then shifted and squashed with tanh() function to have a range between -1 and 1.
an input_ and output_ is created to be used in training. 
input can have a shift backwards using a paramter, which could be used in tasks which the model predicts n-step ahead target.
a test_input and test_output is created to be used in testing. 

