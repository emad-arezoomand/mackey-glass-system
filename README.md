# mackey-glass-system
implementation of mackey glass system. 


the system results are then shifted and squashed with tanh() function to have a range between -1 and 1.


an input_ and output_ is created to be used in training. 


input can have a shift backwards using a paramter, which could be used in tasks which the model predicts n-step ahead target.


a test_input and test_output is created to be used in testing. 
 
test data mentioned above is the training data augmented with further system responses. 

mathematical detail of the system is taken from the paper https://scholar.google.com/citations?view_op=view_citation&hl=en&user=0uztVbMAAAAJ&citation_for_view=0uztVbMAAAAJ:u5HHmVD_uO8C 


snippets of the text explaining this system : 


<img src="https://user-images.githubusercontent.com/50669689/189479258-7ee9bceb-49e9-4477-8262-41a088790711.png" width="700" height="300">
<img src="https://user-images.githubusercontent.com/50669689/189479472-0be093ab-e3c1-41ed-99bf-c36280e47643.png" width="700" height="300">



