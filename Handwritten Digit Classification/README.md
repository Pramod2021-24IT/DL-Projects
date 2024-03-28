## About the Projrct:
- For this project, I've worked on the MNIST database.
- The MNIST data is a database of handwritten digits from 0 to 9.
- The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.

## Tasks:
Our task is to create an ANN model for identifying the digit from the handwritten images.

## Steps performed:

Performed the following tasks:

* Loaded the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist)
* Imported data to create X_train_full, y_train_full, X_test and y_test variables
* Normalized the data
* Created a validation set of 6000 images
* Created an ANN model with two dense layers of 200 and 100 neurons
* Compiled and train the model for 60 epochs
* Ploted the loss and accuracy against epoch
* Evaluated the model accuracy on the test dataset
* Predicted the digit for the first 5 records of the test dataset


![](https://img.shields.io/badge/python-3.x-blue?logo=python&logoColor=yellow&labelColor=black)
![](https://img.shields.io/badge/License-MIT-green?labelColor=black)
-----------------------------------------------------------------------------------------------------------------------
# Movie-Collection-Predictions

### About
This dataset contains data of movies, where our task is to predict the collection (revenue) the movie is going to make using variables such as expense, rating genre, etc.

## Performed the following tasks:

Performed the following tasks-
* Imported ‘Movie_collection’ csv files in data_x and data_y variables.
* Looked at the shape and first five rows of both dataframes to understand the data
* Splited the data into test, train, and validation
* Taken a look at the shape of the test, train, and validation set
* Standardized the data
* Created an ANN model with 2 dense layers of 30 neurons each
* Compiled the model with loss="mean_squared_error", optimizer=keras.optimizers.SGD(lr=1e-2) and metrics=['mae']
* Trained the model for 100 epochs
* Evaluated the model performance on the test set
* Predicted the values of the first 5 test records

### Features

- User Login & Signup

       
### Tools used
- Python3x
- Jupyter Notebook


### Preview:


![image](https://github.com/Pramod2021-24IT/MNIST_Digit_Classification/assets/95674009/33b82919-1651-4e38-904d-00f919be2f16)

![image](https://github.com/Pramod2021-24IT/MNIST_Digit_Classification/assets/95674009/52b351db-1b29-48d5-b02a-b2b190490442)


#

### Next Updates 

| To Do                     |
|---------------------------|
| 1. Mobile Application     |
| 2. GPS Integration        |

#

**Get me on:** <br>
[![](https://img.shields.io/badge/LinkedIn-pramodmaurya9621-blue?logo=Linkedin&logoColor=blue&labelColor=black)](https://www.linkedin.com/in/pramodmaurya9621/)
[![](https://img.shields.io/badge/Gmail-pramod.maurya12321%40gmail.com-red?logo=Gmail&logoColor=Red&labelColor=black)](mailto:pramod.maurya12321@gmail.com)
[![](https://img.shields.io/badge/Telegram-PramodMaurya9621-blue?logo=Telegram&labelColor=black)](https://t.me/PramodMaurya9621) <br>



Model_A:


![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/f53b9e34-e12e-497f-83e7-af81be713dae)

Model_B:


![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/c42f8ae8-5361-4d68-82d9-87c67422d783)
