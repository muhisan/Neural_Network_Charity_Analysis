# Neural_Network_Charity_Analysis
## 1. Overview of the analysis: 
Beks wants us to help her create a binary classifier that can predict whether applicants will succeed if they are funded by Alphabet Soup.

We will use our knowledge of machine learning and neural networks to help the foundation determine where to invest or not. 

We will also use a CSV that Beks received from Alphabet Soup, which contains over 34,000 organizations that have received funding from the foundation over the years.

## 2. Results
### Data Preprocessing
* The IS_SUCCESSFUL column is considered the target column for my model.

![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image3.png)

* The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, 
  INCOME_AMT, and ASK_AMT columns are considered to be the features of my model.
  
 ![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image2.png)
 
* The EIN, NAME, SPECIAL_CONSIDERATION and STATUS columns are neither targets nor 
  features and should be removed from the input data.
  
  ![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image1.png)
  

### Compiling, Training, and Evaluating the Model

* After many attempts of droping all unnecessary colums , adding more layers and neurons, changing number of epochs.
  I finally selected 3 hidden layers beacuse it was the best way i found to increase the target model performance.
  
     * 80 neurons in Layer1: with ReLU function 
     * 50 neurons in Layer2: with ReLU function 
     * 30 neurons in Layer3: with ReLU function 
     * Outer layer: with sigmoid function 
     
     ![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image4.png)
     ![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image5.png)
     
* I achieved an accuracy of 72.5 % that is a bit closer considering the target performance of the model which was 75%
     ![hidden layers](https://github.com/muhisan/Neural_Network_Charity_Analysis/blob/main/Resources/image6.png)
     
## 3. Summary
The overall result achieved with our deep learning model was 72.5% of accuracy by using 2 hidden 
layers of 80, 50 and 30 neurons for each layer.
It would be preferable to try different classification models to solve this problem and get better results.

