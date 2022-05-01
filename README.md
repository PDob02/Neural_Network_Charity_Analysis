# Neural_Network_Charity_Analysis
Module 20 Neural Networks

In the final module of our data science bootcamp we were tasked with creating a neural network to analyze charity funding & success. As shown below, through half of the module & before the optimization code, our accuracy score was 70.56% or 71% rounded. 

![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Accuracy_score.png)

The purpose of this analysis was to judge the success of charities based on a number of factors inclduing asking amount, type of application, use case, & classfication etc. 

Data Preprocessing
What variable(s) are considered the target(s) for your model? Our target per the module was to achieve 75% accuracy. Due to the constraints of the data set we were unable to achieve 75% accuracy but instead regressed in accuracy using different techniques. 

![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Accuracy_score.png)

What variable(s) are considered to be the features for your model? Most of the dataset was a feature of our module, we did however, scrub EIN & NAME right away since those are arbitrary values assigned to organizations. We found most other items relevant including insights with a corporation when we set up a pivot table in excel. This merged dataset still performed relatively well. 

![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Pivot_corporation_insight.png)

What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME & whether or not it was a CORPORATION could be removed safely from the dataset. Most other datapoints are relevant. 

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why? Initially we did two activation functions but added a third for some of our final attempts in the Optimization code. 

![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Added_third_hidden_layer.png)

Were you able to achieve the target model performance? No, we were unable to even improve upon the initial code of around ~71% accuracy rounded up. 

![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Add_relu_in_output_accuracy.png)


![](https://github.com/PDob02/Neural_Network_Charity_Analysis/blob/main/Resources/Added_relu_lowered_hidden_node_layer_50.png)

What steps did you take to try and increase model performance? The steps we took were changing the output function to relu, increasing & decreasing epochs, changing the values for the activation function. Unfortunately, all of these were unsuccessful. 

To summarize the overall results of the deep learning model, we would need to look at additional data or be satisfied with a lower accuracy score. Though not characterized as a failure since we adhered to the requirements of the model, plenty of tweaks & tuning had been done but no change in our accuracy score. This code would help with the added layer of another data scientist or interviewing the charity for more qualitative information. 