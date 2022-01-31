# Overview of Project
Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:



# DELIVERABLE RESULTS:
Data Preprocessing
For this analysis and model, the target is held in IS_SUCCESSFUL field.

# The following variable(s) should be considered on features model
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATIONS
ASK_AMT
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
The following variable(s) should be removed from input and data.
NAME
EIN
Compiling, Training, and Evaluating the Model
Model Configuration:

hidden_nodes_layer1 = 80
hidden_nodes_layer2 = 30
number_input_features = 43
This model acheived 63.8% accuracy with several attempts to incraese the accuracy including:
Increasing the number of hidden nodes in layer 1 (3 X number of input features)
Increasing the number of hidden layers to include a 3rd
Changing the activation functions: tried linear, tanh, sigmoid for a combination of hidden layers and output layer
# SUMMARY
Our Analysis and Deep Learning Model Results include a recommendation for how a different model could solve this classification and results.
