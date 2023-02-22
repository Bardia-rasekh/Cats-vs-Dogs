# Cats-vs-Dogs

Dogs vs Cats dataset is a standard computer vision dataset in deep learning for beginners to learn. The objective of this project is to analyse the images from the dataset and classify if it's a dog or a cat.

In this project tutorial we will use Convolutional Neural Network (CNN) for image feature extraction and visualise the results with plot graphs.

In this project we used the dataset below : 
https://www.kaggle.com/competitions/dogs-vs-cats/data

1.IMPORTING PACKAGES : 
The first step is importing necessary packages in order to file handling , implementing CNNs , plating data and results etc.

2.CREATING INPUT_PATH AND LABEL INORDER TO INTEGRATE THOSE TWO INTO A DATAFRAME : 
Here we import the dataset which is downloaded through the mentioned link above.

3.CREATING DATA FRAME : 
We use a data frame in order to integrate the name of the files and their labels. 

4.DETECTING NON-JPG FILES IN DATASET : 
Data cleaning is a vital step in our project , remember that we can’t train our model with broken images.

5.DELETE DETECTED FILES : 
Here we delete the detected files in the previous step (4) in order to reach a clean dataset.

6.DISPLAY SOME IMAGES IN DATASET FOLDER USING MATPLOTLIB : 
Visualising the dataset helps us to have a better intuition about the project , it’s not a necessary step but in my experience it will be helpful.

7.PLOTTING BAR GRAPH OF CLASSES COUNT : 
Plotting statistics of our dataset helps us to have a better vision about the mathematical side  of our data it will be very helpful specially in vast and complicated datasets.

8.PRINTING FINAL DATA FRAME : 
Here we check the data frame and make sure it has no issue

9.DIVIDE DATASET INTO TRAIN SET AND TEST SET : 
In large AI projects we divide the dataset into validation dataset , train dataset and test dataset but in the small projects (like this)  we divide our dataset into just train dataset and test dataset.

10.GENERATING IMAGES IN TRAIN SET AND TEST SET : 
The goal of this step is to avoid from Overfitting , Overfitting is an expression in Machine learning which is explained completely in the below link 
https://www.ibm.com/topics/overfitting

11.DEFINING MODEL THROUGH ADDING LAYERS AND CHOOSING ACTIVATION FUNCTION : 
This is the first step of implementing  our CNN here we define the type and count  of layers as well as activation functions.

12.COMPILING MODEL AND GETTING SUMMARY OF THE RAW-MODEL : 
Here we compile the CNN that means initialising some parameters like optimizer , loss etc. and also we get a summary of the architecture of CNN in order to have a better vision  

13.TRAINING THE RAW-MODEL : 
This step is the main learning process here the CNN trains by using methods like (forward/backward) propagation 

14.PLOTTING THE PROGRESSES OF ACCURACY AND LOSS : 
In this step we plot the previous step. It helps us to recognize the weaknesses of our model and it gives us a better intuition to eliminate those bugs.

15.TESTING THE TRAINED MODEL USING NEW UNKNOWN IMAGE WHICH IS NOT AVAILABLE IN DATASET : 
Now that we trained our model successfully it is time to use it with some  unknown photos that model has never seen.
