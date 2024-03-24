# Data Preprocessing #
### Targets, Variables, and Extraneous Information
The target for my model was the 'IS_SUCCESSFUL' column.
The variables that compiled the features of my model were: 	APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	
ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS, and	ASK_AMT.
I removed EIN and NAME.

# Compiling, Training, and Evaluating the Model #
### Details on Your Network
I finished my work on my network with four layers (3 hidden node layers, 4, 15, and 5 nodes respectfully) and one output 
layer. The hidden node layers used relu, and the output layer utilized sigmoid for activiation.

### End Results
I was not able to acheive target performance. Perhaps with more time or more patience, that would have been possible. 
I added and removed layers, changed the amount of epochs, tried a wild variety of nodes in each layer, and was 
unsuccessful to acheive anything past about 70% Accuracy with 60% Loss.

## Summary
Overall, I think the deep learning model was fairly consistent with its output. It either tanked or hit about 70% accuracy. 
If I had to choose a different model, I would--at least initially-begin with a Random Forest option. I enjoy how the RF model 
gives you a visual of how different features are weighted in the model, and allows you to adjust based on that. I would have 
greatly appreciated that kind of insight while attempting the deep learning model, because I could have potentially dropped 
some features from the algorithm, and gotten more maleability out of the model. I think one of the frustrating bits about the 
neural network is that it is so ambigious on the outside that it doesn't make it easy to know what is an issue.
