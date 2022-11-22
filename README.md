# Handwriting-Recoginition-with-HOG
Handwritten-Digits-Classification of Handwritten Recognition using HOG + SVM.Following below steps followed for buliding pipleline of opencv image classification

## Steps Followed
### Step1: Preprocessing

  Aligning digits before building a classifier similarly for producing superior results using variation in slant of their writing of different people. Preprossing step in OpenCV will fix this vertical slant by deskewing of grayscale images by calculating image moments.

### Step2: Calculate the Histogram of Oriented Gradients (HOG) descriptor

  Histogram of oriented gradients (HOG) is a feature descriptor used to detect objects in computer vision and image processing. The HOG descriptor technique counts occurrences of gradient orientation in localized portions of an image Parameters used for HOG descriptor in OpenCV:

### Step3: Training SVM Model:

  Used Support Vector Machines (SVM) for Classification.SVM works as Maximal-Margin Classifier with a hyperplane that splits the input variable space. The hyperplane is selected to best separate the points in the input variable space by their class.
  
## Usage 
  To run this project you need [Python](https://www.python.org/) and [Jupyter Notebook](https://jupyter.org/). Also you will need to install all the python libraries specified in the requirements.txt
