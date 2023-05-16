# Neural_Network_Charity_Analysis


Overview 

The purpose of the Neural Network Charity Analysis was to compare the differences between the traditional machine learning classification and regression models and the neural network models. Next, we described the perceptron model and its components. Followed by implementing a neural network models using TensorFlow.  We had to explain how different neural network structures change algorithm performance.  This is where we preprocessed and constructed datasets for neural network models.
After that we compared the differences between neural network models and deep neural networks.  Then, we implemented deep neural network models using TensorFlow.  Finally, we saved the trained TensorFlow models for later use.


Results 

We checked to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.  In our model, the IS_SUCCESSFUL column is the feature chosen for this dataset.  The EIN and NAME columns did not increase the accuracy of the model, making them neither targets or features and can be removed from the model to improve code efficiency. In the optimized model, layer 1 started with 120 neurons with a relu activation. For layer 2, it dropped to 80 neurons and continued with the relu activation. From there, the sigmoid activation seemed to be the better fit for layers 3 (40 neurons) and layer 4 (20 neurons).  The target for the model was 75%, but the best the model could produce was 72.7%.  Columns were reviewed and the STATUS and SPECIAL_CONSIDERATIONS columns were dropped as well as increasing the number of neurons and layers. Other activations were tried such as tanh, but the range that model produced went from 40% to 68% accuracy. The linear activation produced the worst accuracy, around 28%. The relu activation at the early layers and sigmoid activation at the latter layers gave the best results.


Summary

The Neural Network Charity Analysis resulted in the relu and sigmoid activations of 72.7% accuracy, which is the best the model could produce using various numbers of neurons and layers.  I recommend that the next steps in the proccess should be to try the random forest classifier as it is less influenced by outliers in the dataset. 
