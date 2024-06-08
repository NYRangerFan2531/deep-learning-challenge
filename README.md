# deep-learning-challenge
Leonid Lyakhovich
Module 21: Deep Learning
Rutgers Data Science Boot Camp

## Purpose :
 The purpose of this challenge is to create a deep learning model that can help it select the applicants for funding by Alphabet Soup with the best chance of success in their ventures. 
 
## Results:
  The target variable is the IS_SUCCESSFUL with it being a True / False variable.
  
  The features variable are the APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT.
  
  The removed variables are EIN and Name as they are not features nor targets. 
  
## Compiling, Training, and Evaluating the Model

	The layers were added. Layer one have 80 Nodes and layer two had 30 notes - These were just random guessed from the code before.
	
	I was  able to achive 75% accuracy as  model has 76.94% accuracy. This was done the first layer having 80 nodes and "relu" activation function. The second layer had 30 nodes and "relu" activation fuction. The last layer was single node with a "sigmoid" activation function. These were chosen as that is what i have practiced with and was the most confterable with. 
	
	To increase the accuracy, i increased the number of layers, the number of nodes and changed the activation functions. One of the other thing that i did was change the limit of "Other" catigories to be smaller. 
	
## Optimzing the model
	
	The model was optimized by Cutting the Number of Application Types, The Number of Classification Types and Number of Charity Names. The cut of for charity names was 20 occurances. For Classification, it was 1882. For Application Types, it was 275. The Charity Names help the model to achive the target accuracy. 
	
## Recommendation

	As this model has 76% accuracy, there is room for improvement. The recommendation is to run a model that could fit the data and chose the fuctions it self. Using code to select the activation fuctions and the number of nodes has the best chase to selecting the best model as it can vary all the inputs with out tiring out the user. This would give numerous number of models and each would have a tested accuracy. 
