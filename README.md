# astro-sn
Supernovae detection code repository

Graphs - The folder contains graphs for irregular time series testing with LSTM. The Irregular intervals has a folder structure where the home folder is the number of points used for testing. This home folder then has folders for every LSTM cell width with graphs taken at every 10th snapshot of the training to observe the accuracy of prediction.


Outputs - IRR_Error_LSTMWidth_Iterations.csv contains the results with sum squared errors for every combination of number of points, LSTM width and the training iteration count for which the graphs were generated
