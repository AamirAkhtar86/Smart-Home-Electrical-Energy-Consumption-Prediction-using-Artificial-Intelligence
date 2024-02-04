# IoT based Smart Home's Electrical Energy Consumption Prediction using Artificial Intelligence

This repository contains the dataset and python notebook which uses the dataset from 2016 apartment 1. 

# How the code works:

1. Read the CSV file.
2. Rename the columns. Column 1 to "timestamp" and column 2 to "power".
3. Use values from power column to create a new columns named "label". We label energy consumption from 0 to 0.85 as '0', greater than 0.85 and less than 3 as '1' and greater than 1.2 as '2'.
4. We drop NAN values and use power on X axis and labels on y axis. Split the data into 80:20 ratio for traing and validation of our model.
5. Define ANN model.
6. Train and validate the model based on our data.
7. Plot different graphs to visulaize model accurracy.
