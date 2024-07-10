# Cat and Dog Image Classifier

## Overview

In this project, you'll complete the code to classify images of dogs and cats. You will use TensorFlow 2.0 and Keras to create a convolutional neural network (CNN) that correctly classifies images of cats and dogs at least 63% of the time. Extra credit if you get it to 70% accuracy!


## Instructions

1. **Data Import and Setup:**
   - Import the required libraries.
   - Download the dataset and set key variables.

2. **Image Generators:**
   - Create image generators for the training, validation, and test datasets using `ImageDataGenerator`.
   - Rescale the images from values between 0 and 255 to values between 0 and 1.

3. **Plot Images:**
   - Use the `plotImages` function to plot images.

4. **Data Augmentation:**
   - Recreate the `train_image_generator` using `ImageDataGenerator` with random transformations to prevent overfitting.

5. **Model Creation:**
   - Create a Keras Sequential model with Conv2D and MaxPooling2D layers and a fully connected layer with a ReLU activation function.
   - Compile the model with the appropriate optimizer and loss function.

6. **Model Training:**
   - Train the model using the `fit` method, passing in the required arguments.

7. **Model Evaluation:**
   - Visualize the accuracy and loss of the model.
   - Predict whether new images are of cats or dogs and display the results.

## Implementation Details

### Cell 3
Set each variable correctly and create image generators for the three datasets. Use the `flow_from_directory` method to pass in the batch size, directory, target size, class mode, and other required parameters.

### Cell 4
Use the given `plotImages` function to plot five random training images.

### Cell 5
Recreate the `train_image_generator` with random transformations and rescale the images.

### Cell 6
Plot a single image five different times using the new `train_image_generator`.

### Cell 7
Create a neural network model with Conv2D and MaxPooling2D layers, followed by a fully connected layer with a ReLU activation function. Compile the model.

### Cell 8
Train the model using the `fit` method.

### Cell 9
Visualize the accuracy and loss of the model.

### Cell 10
Predict whether a new image is a cat or a dog and display the results.

### Cell 11
Check if you passed the challenge.

## Submission

After completing the project, save your work and submit your project link. If you're using Google Colaboratory, ensure link sharing is turned on for "anyone with the link."

Example submission link: [Colab Notebook](https://colab.research.google.com/drive/1i5EmInTWi1RFvFr2_aRXky96YxY6sbWy)

## Resources

We are continuously developing the instructional content for the machine learning curriculum. For now, you can refer to the video challenges in this certification and seek out additional learning resources as needed.

## Contact

If you need any help or have questions, feel free to ask for help in the community.

Happy coding!
