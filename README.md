# Neural_Network_Charity_Analysis
Module 20 Neural Networks

In the final module of our data science bootcamp we were tasked with creating a neural network to analyze charity funding & success. 
Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
What variable(s) are considered the target(s) for your model? Our target per the module was to achieve 75% accuracy. Due to the constraints of the data set we were unable to achieve 75% accuracy but instead regressed in accuracy using different techniques. 

What variable(s) are considered to be the features for your model? Most of the dataset was a feature of our module, we did however, scrub EIN & NAME right away since those are arbitrary values assigned to organizations. We found most other items relevant including insights with a corporation when we set up a pivot table in excel. This merged dataset still performed relatively well. 

What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME & whether or not it was a CORPORATION could be removed safely from the dataset. Most other datapoints are relevant. 

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why? Initially we did two activation functions but added a third for some of our final attempts in the Optimization code. 

Were you able to achieve the target model performance? No, we were unable to even improve upon the initial code of around ~71% accuracy rounded up. 

What steps did you take to try and increase model performance? The steps we took were changing the output function to relu, increasing & decreasing epochs, changing the values for the activation function. Unfortunately, all of these were unsuccessful. 

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.