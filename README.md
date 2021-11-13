# Neural_Network_Charity_Analysis
## 1. Overview of the analysis: 
Beks wants us to help her create a binary classifier that can predict whether applicants will succeed if they are funded by Alphabet Soup.

We will use our knowledge of machine learning and neural networks to help the foundation determine where to invest or not. 

We will also use a CSV that Beks received from Alphabet Soup, which contains over 34,000 organizations that have received funding from the foundation over the years.

## 2. Results
### Data Preprocessing
* The IS_SUCCESSFUL column is considered the target for my model.
* The APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, 
  INCOME_AMT, and ASK_AMT columns are considered to be the features of my model.
* The EIN, NAME, SPECIAL_CONSIDERATION and STATUS columns are neither targets nor 
  features and should be removed from the input data.

### Compiling, Training, and Evaluating the Model

* After many attempts of droping all unnecessary colums , adding more layers and neurons, changing number   of epochs, I finally selected 3 hidden layers beacuse it was the best way i found to increase 
  the target model performance.
  
     *  neurons in Layer1: with ReLU 
     *  neurons in Layer2: with 
     *  neurons in Layer3: with 
     *  The sigmoid function for the outer layer
            
* I achieved an accuracy of which is a little low considerd the target model performance which is 75%

## 3. Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

