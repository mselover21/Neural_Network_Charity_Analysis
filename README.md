# Neural Network Charity Analysis

## Purpose
The purpose od this analysis is to predict if whether applicants will be successful if funded by the company Alphabet Soup. 

### Results
- Data Preprocessing
    - The target of this model is Is Successfull
    - The features of the the model are
        - Applications Type
        - Affiliation
        - Classification
        - Use Case
        - Organization
        - Income Amt
        - Special Considerations
- Compiling, Training, and Evaluating the Model
    - For this model I used 2 hidden layers the first layer had 80 neurons and and activation function relu. The second layer had 30 neurons and activation function relu.
    - I was unable to get to the target model performce of above %74.
    - I tried adding a third hidden layer as well as changing the number of neurons on all layers and using different activation functions of tanh and sigmoid.

#### Summary
All in all the model performs realativily well predicting the success of funded organizations. With an accuracy of %74 the model does predict successful organiztions rather well. I do reccommend exploring further analysis using an unsupervised learning model. I beleive there could be different patterns that arise if the data is clustered. This may show a different trend in the data and lead to higher accuracy.        