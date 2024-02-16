# P8451_HW5_ML


exercise:  Predicting Current Alcohol Consumption from Behavioral Scores

Dataset Description:

These data were collected as part of an online survey related to drug and alcohol use and personality traits. Individuals answered standardized questions which were used to calculate continuous scores on personality traits. Individuals were also asked about consumption of alcohol and multiple drugs. Further information on this dataset can be found at http://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29#Links to an external site..

For the purpose of this exercise, the data has been subset to include only 7 features on personality traits and the variable which distinguishes those who reported current alcohol use (defined as alcohol use in the past month or more frequently) vs no current use. Data are stored in the csv file alcohol_use.csv on the course site.

Feature Information: Below is a list of the 7 features and outcome variable within the dataset. Note the dataset also contains an ID variable. In general, the higher value of the score, the greater the personality trait observed within the individual based on the questionnaire.

alc_consumption: CurrentUse, NotCurrentUse 
neurotocism_score: Measure of Neuroticism
extroversion_score: Measure of Extroversion
openness_score: Measure of Openness to Experiences
agreeableness_score: Measure of Agreeableness
conscientiousness_score: Measure of Conscientiousness
impulsiveness_score: Measure of Impulsivity
sens_seeking_score: Measure of Sensation-Seeking Behaviors.
 

Instructions for Assignment

Goal: You want to predict current alcohol consumption but it is expensive and time-consuming to administer all of the behavioral testing that produces the personality scores. You will conduct a reproducible analysis to build and test classification models using regularized logistic regression and traditional logistic regression. You will produce a shareable report that includes code, results and answers to questions using R Markdown.

Address the following:

You should create and compare three different models listed below :
A model that chooses alpha and lambda via cross-validation using all of the features in the dataset
A model that uses all the features in the dataset and traditional logistic regression. This can also be learned using cross-validation, even though there are no hyperparameters
A lasso model using all of the features in the dataset, tuning the hyperparameter using cross-validation.
Decide which model you would choose as your final model. Provide justification for your choice. (1-2 sentences. no more!)
Apply your final model in the test set and report your final evaluation metrics. 
What research questions could this analysis either a) directly address or b) indirectly help to address by providing information that could be used in subsequent analyses? Limit this response to no more than 1 paragraph. Be sure to use complete sentences.
Remember to remove the ID variable as you do not want to include that in your analysis. Remember to use 123 as your random seed.