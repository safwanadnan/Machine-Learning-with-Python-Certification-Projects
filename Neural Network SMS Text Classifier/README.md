# Neural Network SMS Text Classifier

## Overview

In this project, you will create a machine learning model to classify SMS messages as either "ham" (normal messages sent by friends) or "spam" (advertisements or messages sent by companies).

## Instructions

1. **Data Import and Setup:**
   - Import the required libraries.
   - Download the dataset and set key variables.

2. **Data Preprocessing:**
   - Use the provided SMS Spam Collection dataset, which is already divided into train and test data.

3. **Model Creation:**
   - Create a neural network model to classify SMS messages.
   - Train the model using the training data.

4. **Function Definition:**
   - Define a function `predict_message` that takes a message string as an argument and returns a list:
     - The first element should be a number between 0 and 1 indicating the likeliness of "ham" (0) or "spam" (1).
     - The second element should be the word "ham" or "spam", depending on which is most likely.

5. **Model Evaluation:**
   - Test your model using the provided test data to check its accuracy and performance.

## Implementation Details

### Data Import and Setup
The first two cells import the necessary libraries and the dataset.

### Data Preprocessing
Use the provided SMS Spam Collection dataset. The data is already split into train and test datasets.

### Model Creation
Create and train a neural network model using the training data to classify SMS messages.

### Function Definition
Define the `predict_message` function to take a message string as input and return a list:
- The first element: A number between 0 and 1 indicating the likelihood of the message being "ham" or "spam".
- The second element: The word "ham" or "spam", depending on which is most likely.

### Model Evaluation
Evaluate the model using the test data to ensure it accurately classifies SMS messages as "ham" or "spam".

## Submission

After completing the project, save your work and submit your project link. If you're using Google Colaboratory, ensure link sharing is turned on for "anyone with the link."

Example submission link: [Colab Notebook](https://colab.research.google.com/drive/1i5EmInTWi1RFvFr2_aRXky96YxY6sbWy)

## Resources

We are continuously developing the instructional content for the machine learning curriculum. For now, you can refer to the video challenges in this certification and seek out additional learning resources as needed.

## Contact

If you need any help or have questions, feel free to ask for help in the community.

Happy coding!
