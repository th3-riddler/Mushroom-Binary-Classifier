# Mushroom Binary Classifier
Mushroom binary classifier is a basic binary-classification project that trains different models on recognizing if a given mushroom is poisonous or edible based on its characteristics. \
Some of these features are:
- cap-shape
- cap-surface
- habitat
- has-ring
- stem-color
- etc...

Models such as **Perceptron**, **Random Forest** and **Gradient Boosting** are trained in this project. Each of them is associated to its Confusion Matrix. \
Eventually, a **ROC Curve** is displayed, in order to better visualize the performance of each model.

Then, after applying **RFECV** to the dataset, one of the best models (Gradient Boosting) is trained again, in order to boost its performance, and saved in a `.sav` file using the `pickle` library.\
So, this model can be reused to classify future given mushrooms.