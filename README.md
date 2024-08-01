## Module 21 Challenge

Name: Andrea

### Objective
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

### Notes to User
Please run "Starter_Code.ipynb" for the initial model. 

Libraries that need to install before running:
- TensorFlow
- Scikit-learn
- Pandas

Please run "AlphabetSoupCharity_Optimization.ipynb" for the optimized model. 

Things did to optimize the model:
- Dropped "Status" column as it doesn't seem to be related to successful rate.
- Increased the Number of Neurons
- Added the third hidden layer
- Added the number of epochs to the training regimen
