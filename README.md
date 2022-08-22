# Nueral_Network_Charity_Analysis

### Overview of Project:

Using nueral networks and machine learning, a binary classifier is used to predict whether applicants will be funded by the foundation project "Alphabet Soup". Using a dataset that has over 34,000 orginizations that have funded Alphabet soup, a clearer idea of will be created of investment opportunities. 

# Data Preprocessing
### What variable(s) are considered the target(s) for your model?

The column "IS_SUCCESSFUL" is the target of my model

### What variable(s) are considered to be the features for your model?

APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and ASK_AMT columns are the features of my model.

### What variable(s) are neither targets nor features, and should be removed from the input data?

The columns EIN and NAME are neither targets nor features and have been removed from the input data.

# Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?

![Screen Shot 2022-08-22 at 3 49 41 PM](https://user-images.githubusercontent.com/100393032/186032264-018df440-cdb8-4b2e-b9b6-c61eb598c632.png)

I chose this set based on recommendations from fellow data analyst. Running these layers also seemed to give me a better answer.
### Were you able to achieve the target model performance?

I was not able to acheive the target model performance

### What steps did you take to try and increase model performance?

In order to increase the model perforamnce I attempted to reduce the layers and nuerons while focusing on the ASK_AMT. I was hopeful that the decreased amount of data would deliver a closer mark to the target but I was unsuccesful.
## Summary

In summary, I was unable to succesfully reach the target performance put forth by the company. This analysis would cover a great majority of finding the applicants that would be best suited to to get funding to "Alphabet Soup."
