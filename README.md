# Neural_Network_Charity_Analysis
## **Overview of the analysis**: 
 The purpose of this analysis is to create a neural network model that can predict whether to help the foundation predict where to make investments.

To achieve this purpose, we have used a supervised machine learning technique called neural networks. We have trained a neural network model on a dataset, I’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The model has been optimized by removing noisy variables, adding neurons to hidden layers, adding additional hidden layers, changing activation functions, and saving the weights of the model every 5 epochs. Our aim is to achieve an accuracy of over 75%.

## **Results**: 
### **Data Preprocessing**

   - What variable(s) are considered the target(s) for your model?
   
     - The Target variable considered for this model was IS_SUCCESSFUL
     
   - What variable(s) are considered to be the features for your model?
        - APPLICATION_TYPE
        - AFFILIATION
        - CLASSIFICATION
        - USE_CASE
        - ORGANIZATION
        - STATUS
        - INCOME_AMT
        - SPECIAL_CONSIDERATIONS
        - ASK_AMT
        
   - What variable(s) are neither targets nor features, and should be removed from the input data?
        - EIN 
        - NAME
  - **Compiling, Training, and Evaluating the Model**
       - How many neurons, layers, and activation functions did you select for your neural network model, and why?
       I use a total of:
       Neurons = 80, Hidden Layers = 30 Activation used was sigmoid
       ![image](https://user-images.githubusercontent.com/112348240/221383749-21bf23b3-2bb0-4d7d-8c6f-f32ab5b513e9.png)

       - Were you able to achieve the target model performance?
       - What steps did you take to try and increase model performance?

## **Summary**:
![image](https://user-images.githubusercontent.com/112348240/221384315-c4631cfe-5593-4519-8fb0-fd54fb5d2be1.png)
