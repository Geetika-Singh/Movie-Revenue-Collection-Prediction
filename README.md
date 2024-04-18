# Movie-Revenue-Collection-Prediction
The dataset contains data of movies, where the task is to predict the collection (revenue) the movie is going to make using variables such as expense, rating genre, etc. 

The following tasks are performed: 

Import ‘Movie_collection’ csv files in data_x and data_y variables. <br>
Look at the shape and first five rows of both dataframes to understand the data <br>
Split the data into test, train, and validation <br>
Look at the shape of the test, train, and validation set <br>
Standardize the data <br>
Create an ANN model with 2 dense layers of 30 neurons each <br>
Compile the model with loss="mean_squared_error", optimizer=keras.optimizers.SGD(lr=1e-2) and metrics=['mae']) <br>
Train the model for 100 epochs <br>
Evaluate the model performance on the test set <br>
Predict the values of the first 5 test records <br>
