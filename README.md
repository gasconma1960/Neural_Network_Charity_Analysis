![image](https://user-images.githubusercontent.com/112348240/221391084-1a0d04c1-09f6-43c9-b618-8379cb2ea3e9.png)

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
       
       ### **First Code**
       
       Neurons = 80, Hidden Layers = 30 Activation used was sigmoid
       
       ![image](https://user-images.githubusercontent.com/112348240/221383749-21bf23b3-2bb0-4d7d-8c6f-f32ab5b513e9.png)
       
       ## **Optimization Code**
       
       Neurons = 100, Hidden Layers = 60, Hidden Layers = 30,  Hidden Layers = 10, Activation used was linear     
       
       ![image](https://user-images.githubusercontent.com/112348240/221389570-9ccd8d97-4938-477a-91c9-65a58d24736f.png)
       
       ## **Test # 1**
       
       Neurons = 50, Hidden Layers = 20, Hidden Layers = 15, Activation used was sigmoid 
       
       ![image](https://user-images.githubusercontent.com/112348240/221389724-1fdda52a-ddca-45d0-aef0-8f313d4aa024.png)
       
       ## **Test # 2**
       
       Neurons = 70, Hidden Layers = 40, Hidden Layers = 20, Hidden Layers = 10, Activation used was linear
       
       ![image](https://user-images.githubusercontent.com/112348240/221389747-a87b4766-a741-486b-81cd-78a89c0dd431.png)
  
       ## **Test # 3**
       
       Neurons = 50, Hidden Layers = 30, Hidden Layers = 10, Activation used was sigmoid
       
       ![image](https://user-images.githubusercontent.com/112348240/221390122-2c76d4c3-0bf1-4bb6-89ae-a3ff95d2bcdc.png)
       
  - Were you able to achieve the target model performance?
    No, I wasnt able to achieve the target
  
  - What steps did you take to try and increase model performance?
  
      - Increase/decrease the neurons,
      - Increase/decrease the hidden layers
      - Try changing the activation output linear and sigmoid the most used one on the test
      - Last but not least test different epochs

## **Summary**:

  After trying different steps to improve the results, I wasn't able to reach the 75% target, using the Deep Machine Learning and neural network models. The max achieve was 72.78%, with fourth hidden layers and 50 epochs. 
  
![image](https://user-images.githubusercontent.com/112348240/221384315-c4631cfe-5593-4519-8fb0-fd54fb5d2be1.png)

# **Sources**:

GoogleColab

tensorflow libraries

charity_data.csv

## **Module 20 Challenge**

by: **Marisol Gascon Linarez**

**UCF Bootcamp Data Visualization and Analytics**


