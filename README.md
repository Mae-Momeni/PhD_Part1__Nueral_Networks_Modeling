# PhD Project: Neural Network Modeling to design a Manufacturing Process
<br>
In summary:<br>
<br>
I’ve used neural network modeling to improve and industrialize a novel manufacturing process. Indeed, I developed predictive models using a relatively novel approach which was the integration of neural network modeling and design of experiments (DOE) using the Taguchi method to optimize the process parameters. It was a regression model, and the loss function was RMSE. So, the goal was to minimize the RMSE while being careful to avoid overfitting. So, we tried to find the simplest architecture while capturing as much as detail we can until we are not overfit. It resulted in boosting the production performance by 9 times at only a small fraction of the cost of available techniques in the market.<br>
<br>
Technically, we did DOE to minimize the number of experimental tests. Then I used ANN to model the effect of independent features on the target variables. We had 10 independent features and 2 target variables. The relationships between these features were non-linear, so ANN models are a great option in these cases.
Target features were quality of products and welding force. The goal was to increase the quality while decreasing the force to reduce the manufacturing costs. Some examples of independent variables are geometrical tool parameters, geometrical errors of welds, welding rotational speed, and vertical speed. Most of them were numerical, and the rest were categorical such as weld configuration that I managed by encoding. <br>
<br>
We needed to introduce a range of independent features to have the process optimized for the potential customers so that if they select the parameters in that range based on their own business metrics and resources, the cost would be low and the quality high enough.<br>
<br>
For NN, software was written with C++ in our research group, in which favorable functions for our application were implemented. I’ve studied and done hyperparameter tuning of learning rate, momentum, number of epochs, and architecture of the network to optimize the model.
<br>
During my PostDoc, I developed Machine Learning model on all the use cases from my PhD theses. Different machine learining models were studied to take the one with the best performance. Also Nueral network models by Keras were optimized. The results are presented in another repo in my github.
