# ECE_C247_project
Analyzing EEG Signals using Neural Networks and Deep Learning

######################################################################################################################################################################

Questions:

1.) Optimize the classification accuracy for subject 1. Does it help to train across all subjects? Answer: As mentioned in the results section of the report, optimizing the model for Subject 1 is causing an overfit failing to be more generic for all the other subjects.

2.) Optimize the classification accuracy across all subjects. How does the classifier do? Do you notice any interesting trends? Answer: When optimized for all the subjects the classifier tends to perform poorly in terms of the testing accuracy however, this is the expected behaviour. While the cascaded CNN+LSTM typically performed better than the CNN+GRU architecture as expected, we observed that the CNN+GRU architecture trained much more efficiently as expected, given that the GRU contains less parameters than an LSTM.

3.) Evaluate the classification accuracy as a function of time (e.g., does it increase as you have data over longer periods of time? how much time is required to get a reasonable classification accuracy?) Answer: As the time goes on increasing the classification accuracy was observed having an increasing trend. A reasonable classification accuracy was achieved anywhere between 20-30 minutes.

########################################################################################################################################################################## NOTE TO THE EVALUATORS: The Code Files Folder contains the Code for the EEG Dataset. The code needs to be verified in the following order: 1.) Model Comparison wrt Subjects (This folder needs to be evaluated to confirm an accuracy of more than 70% for subjects considered individually). 2.) CNN_LSTM(This file needs to be evaluated to confirm the accuracy of approximately 70% for all the subjects considered together). Supporting images have been included and also pasted in the report.
