# Human Activity Recognition

*In Human Activity Recognition we are trying to predict 6 human activities which are treated as class labels.*

- Activity 1 -> Walking
- Activity 2 -> Walking_Upstairs
- Activity 3 -> Walking_Downstairs
- Activity 4 -> Sitting
- Activity 5 -> Standing
- Activity 6 -> Laying

*Raw data are the signals which are generated from Accelerometer and Gyroscope. These signals are in x,y,z directions. Sensor signals are filtered to have only body acceleration excluding the acceleration due to gravity. Triaxial acceleration from the accelerometer is total acceleration.*

- Signal 1 -> body_acc_x
- Signal 2 -> body_acc_y
- Signal 3 -> body_acc_z
- Signal 4 -> body_gyro_x
- Signal 5 -> body_gyro_y
- Signal 6 -> body_gyro_z
- Signal 7 -> total_acc_x
- Signal 8 -> total_acc_y
- Signal 9 -> total_acc_z

*Different combinations of Long Short Term Memory (LSTM) models are used for Human Activity Recognition.*

## LSTM Models

- Model 1 -> 30 Epochs + Sigmoid + RMSprop + 32 hidden layers + Dropout
- Model 2 -> 30 Epochs + Sigmoid + ADAM + 32 hidden layers + Dropout
- Model 3 -> 30 Epochs + Sigmoid + RMSprop + 64 hidden layers + Dropout
- Model 4 -> 30 Epochs + Sigmoid + ADAM + 64 hidden layers + Dropout

## Steps Followed

- Load the raw data.
- Split the data into train and test.
- Try out different LSTM models with different number of hidden layers and different optimizers.
- Draw confusion matrix.
- Print score of the predicted data.
- At the end in conclusion section compare train log loss, train accuracy, test log loss and test accuracy for each LSTM model.
