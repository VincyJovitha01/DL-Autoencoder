# DL- Convolutional Autoencoder for Image Denoising

## AIM
To develop a convolutional autoencoder for image denoising application.

## THEORY
This code implements a **Denoising Autoencoder** using PyTorch to clean noisy images from the MNIST dataset. It uses a convolutional neural network architecture, where the encoder compresses the input image into a lower-dimensional representation, and the decoder reconstructs the original image from this compressed form. To train the model to remove noise, Gaussian noise is added to the clean images, and the network learns to recover the original from the noisy version. The training process uses **Mean Squared Error (MSE)** as the loss function to measure the reconstruction error and the **Adam optimizer** to update the model weights. The autoencoder is trained over multiple epochs using mini-batches of data for efficiency. After training, the model's performance is visually evaluated by displaying the original, noisy, and denoised images side by side.



## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 
Problem Understanding and Dataset Selection

### STEP 2: 
 Preprocessing the Dataset
 
### STEP 3: 
Design the Convolutional Autoencoder Architecture

### STEP 4: 
Compile and Train the Model

### STEP 5: 
Evaluate the Model

### STEP 6: 
Visualization and Analysis

### OUTPUT

### Model Summary
<img width="758" height="567" alt="image" src="https://github.com/user-attachments/assets/b319d5c7-83c6-427a-930f-eb28b15543f2" />

<img width="1700" height="708" alt="image" src="https://github.com/user-attachments/assets/8cdc0ad8-9510-40fe-afb5-2add5ab472ec" />


## RESULT
Therefore, To develop a convolutional autoencoder for image denoising application executed successfully.





