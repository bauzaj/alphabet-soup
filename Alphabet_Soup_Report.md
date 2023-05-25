Overview of the analysis: The purpose of this model is to help screen applicants with the best possible chance of success

Results: 

Data Preprocessing

-From the dataset, used the 'Is_Successful' column as the target.
-Used all columns except for 'Classification' and the target columns


Compiling, Training, and Evaluating the Model

-The original model consisted of two layers, with 8 and 6 neurons
-This format was not able to reach the target model performance metric
-Added two hidden layers with respective neuron additions as well
-Dropped Epochs down from 200 to 75


Summary: 

Target Accuracy never reached higher than 72% throughout modifications. Recommendation would be to include more data to insert into training.