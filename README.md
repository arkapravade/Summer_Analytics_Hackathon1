# Summer Analytics Hackathon Project

The Hackathon Project was done using two methods, Linear Regression & Neural Network

##Neural Network
The dataset contains over 15,000 patterns. From the dataframe, two features, being 'Rating' and 'Actual Price' were found to be the most correlated to the output which is 
'Discounted Price'. In order to generalise the model we are willing to develope, a certain 
percentage of the data that can be considered as outlier values have been excluded from consideration. The values were then scaled to proper a range and fitted to the model.

While we could transform the testing parameters according to the values in the testing set, we performed the step using the model used to fit the training values. The model was tested through several hyper-parameter tunings and ultimately settled with two hidden layers, each having 1,500 nodes and Rectified Linear Unit (ReLU) activation function. The model was optimized using 'Adam' optimizer and the Mean Squared Error (MSE) was considered as the loss function.

The final Root Mean Squared Error turned out to be around 238.6.
