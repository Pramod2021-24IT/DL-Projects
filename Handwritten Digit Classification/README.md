## About the Projrct:
- For this project, I've worked on the MNIST database.
- The MNIST data is a database of handwritten digits from 0 to 9.
- The database contains 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.

## Tasks:
Our task is to create an ANN model for identifying the digit from the handwritten images.

## Steps performed:

Performed the following tasks:

•	Loaded the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist)
•	Imported data to create X_train_full, y_train_full, X_test and y_test variables
•	Normalized the data
•	Created a validation set of 6000 images
•	Created an ANN model with two dense layers of 200 and 100 neurons
•	Compiled and train the model for 60 epochs
•	Ploted the loss and accuracy against epoch
•	Evaluated the model accuracy on the test dataset
•	Predicted the digit for the first 5 records of the test dataset


Model_A:


![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/f53b9e34-e12e-497f-83e7-af81be713dae)

Model_B:


![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/c42f8ae8-5361-4d68-82d9-87c67422d783)
