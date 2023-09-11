# Melanoma_Assignment

# Project Name:-  
Melanoma Assignment
# Objective :- 
To build a CNN based model to predict the Melanoma a type of cancer that can be deadly. A solutios in needed that can evaluate images and alert dermatologists the presence of mealanoma. 

# Technologies used:- 
CNN - Convolutional Neural Network with Tensor flow and keras. 

The file consists of different data set for following diseases :-
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

These data sets consists of images for different diseases, we have to use CNN model to understand and train the model to predict the disease. 
With these built model will be usefult to calssify melanoma with just images processing and will be usefult to dermatologists. 

# Project Pipeline :- 

# Data Reading/Data Understanding 
Defining the path for train and test images 
# Dataset Creation 
Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
# Dataset visualisation 
Create a code to visualize one instance of all the nine classes present in the dataset 
# Model Building & training : 
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs

Here, we have seen that the difference between training and valiadation accuracy increase with number of epochs.
Similarly, for the loss function as the epochs increases the difference between trainging and test value increases. 

# Model Building & training on the augmented data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs

# Class distribution: 
1.   melanoma, basal cell carcinoma, nevus and pigmented beningin keratosis show class imblance, more data sets are available for these four classes and these classes dominates.
2.   seborrheic keratosis shows least number of samples with 77.

# Handling class imbalances: 
Rectify class imbalances present in the training dataset with Augmentor library.

# Model Building & training on the rectified class imbalance data :
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~30 epochs

# Conclusion :- 
Model3 resolves class imbalance using augmentor technique. Accuracy and loss function fits very well. The accuracy and loss varies with 

# Team Memebers :- 
Jagadeesh Shivaprasad
Dhruv Joshi
Arun M





