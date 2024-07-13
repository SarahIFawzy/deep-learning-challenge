# deep-learning-challenge

**Data Preprocessing**

What variable(s) are the target(s) for your model?
  - the model was built to predict whethar applicants for Alphabet Soup funding would be successful if funded
What variable(s) are the features for your model?
  - the model looked at affiliation, classification, use_case, organization, status, income amount, ask amount, and special considerations
What variable(s) should be removed from the input data because they are neither targets nor features?
  - the variables that were removed from the consideration set were name and EID


**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - the initial model had 2 layers consisting of 80 and 30 neurons respectively, each layer using the relu activation function
Were you able to achieve the target model performance?
  - the result of the original model was 72.42% accuracy
What steps did you take in your attempts to increase model performance?
  - I attempted to optimize the accuracy of the model by modifying the following:
      - I increased the number of neurons in each hidden layer to 100 and 50 respectively; which increased optimization to 72.54
      - I then increased the number of hidden layers to 3, adding 30 neurons to the third layer; this actually decreased the optimization to 72.34
      - My last attempt was to change all activation functions to sigmoid and increase the number of epochs from 100 to 120; this increased optimization slightly to 72.46, but not as great an increase as I saw in my first optimization attempt


Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

With more time and resources this there are several more variables that can be adjusted to optimize the model to >75%, however I was not able to get there.
