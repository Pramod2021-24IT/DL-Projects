![](https://img.shields.io/badge/python-3.x-blue?logo=python&logoColor=yellow&labelColor=black)
![](https://img.shields.io/badge/License-MIT-green?labelColor=black)
-----------------------------------------------------------------------------------------------------------------------
# Osteoarthritis Probability 

## About
- Orthopaedist is a medical doctor specializing in diagnosing and treating disorders related to the skeletal system.
- Part of their job is to distinguish between a healthy person and a person with Osteoarthritis by looking at their knee X-ray images.
  
- **Osteoarthritis:** Osteoarthritis, commonly known as wear-and-tear arthritis, is a condition in which the natural cushioning between joints -- cartilage -- wears away. When this happens, the bones of the joints rub more closely against one another with less of the shock-absorbing benefits of cartilage. The rubbing results in pain, swelling, stiffness, decreased ability to move, and sometimes the formation of bone spurs.

## Tasks:
Our task is to create a deep learning model that can provide the probability of having osteoarthritis for a given knee X-ray image using inceptionV3(GoogleNet) architecture.

## Dataset 

The Dataset contains three folders-  
1. Test (845 images)
2. Train (2350 images)
3. Valid (641 images)
   
Each of these folders has two folders-  
1. Test
2. Normal

[Click heare](https://trainings.internshala.com/uploads/deep-learning/content_media/Osteoarthritis_Assignment_dataset.zip) to download the dataset.

## Performed the following tasks:

Performed the following steps-
* Loaded the database to variable named digit_mnist using the Keras inbuilt datasets (digit_mnist = keras.datasets.mnist)
* Imported data to create X_train_full, y_train_full, X_test and y_test variables
* Reshaped the independent (X) data
* Normalized the data
* Created a validation set of 6000 images
* Created a CNN model (Model_A) with a Conv layer of filters = 32, kernel_size = (3, 3), strides=1, padding='valid', a Max pooling layer of 2 by 2 window and two dense layers with 200 and 100 neurons
* Compiled and train the model for 60 epochs
* Ploted the loss and accuracy against epoch
* Evaluated the model accuracy on the test dataset
* Created another model (model_B) with number of filter =64
* Compared the performance and execution time for Model_A and Model_B


### Features

- User Login & Signup
- Upload/Drag and Drop Interfere 

       
### Tools used
- Python3x
- Jupyter Notebook


### Preview:


--------------------------------------------------------------------------------------------

**Healthy Knee Joint**

![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/991c23c1-92ca-4e67-9006-08c66ab488f0)


**Osteoarthritis**

 ![image](https://github.com/Pramod2021-24IT/DL-Projects/assets/95674009/3a40f1e9-03b5-46d9-95e0-98016e3a1f01)

#

### Next Updates 

| To Do                     |
|---------------------------|
| 1. Mobile Application     |
| 2. Web Extension          |

#

**Get me on:** <br>
[![](https://img.shields.io/badge/LinkedIn-pramodmaurya9621-blue?logo=Linkedin&logoColor=blue&labelColor=black)](https://www.linkedin.com/in/pramodmaurya9621/)
[![](https://img.shields.io/badge/Gmail-pramod.maurya12321%40gmail.com-red?logo=Gmail&logoColor=Red&labelColor=black)](mailto:pramod.maurya12321@gmail.com)
[![](https://img.shields.io/badge/Telegram-PramodMaurya9621-blue?logo=Telegram&labelColor=black)](https://t.me/PramodMaurya9621) <br>
