# Linear Regression Health Costs Calculator

## Overview

In this project, you will predict healthcare costs using a regression algorithm. You will use a dataset containing information about different people, including their healthcare costs, to predict healthcare costs based on new data.

## Instructions

1. **Data Import and Setup:**
   - Import the required libraries.
   - Download the dataset and set key variables.

2. **Data Preprocessing:**
   - Convert categorical data to numerical values.
   - Split the data into `train_dataset` (80%) and `test_dataset` (20%).
   - Pop off the "expenses" column to create `train_labels` and `test_labels`.

3. **Model Creation:**
   - Create a regression model to predict healthcare costs.
   - Train the model using the `train_dataset`.

4. **Model Evaluation:**
   - Evaluate the model using the `test_dataset` to check how well it generalizes.
   - Ensure the `model.evaluate` returns a Mean Absolute Error (MAE) of under 3500.

5. **Results Visualization:**
   - Predict expenses using the `test_dataset` and graph the results.

## Implementation Details

### Data Import and Setup
The first two cells import the necessary libraries and the dataset.

### Data Preprocessing
Convert categorical data to numerical values and split the dataset:
- `train_dataset`: 80% of the data
- `test_dataset`: 20% of the data

Create labels:
- `train_labels`: "expenses" column from `train_dataset`
- `test_labels`: "expenses" column from `test_dataset`

### Model Creation
Create and train a regression model using the `train_dataset`.

### Model Evaluation
Evaluate the model using the `test_dataset`:
- Ensure the Mean Absolute Error (MAE) is under 3500 to pass the challenge.

### Results Visualization
Predict healthcare costs using the `test_dataset` and visualize the results.

## Submission

After completing the project, save your work and submit your project link. If you're using Google Colaboratory, ensure link sharing is turned on for "anyone with the link."

Example submission link: [Colab Notebook](https://colab.research.google.com/drive/1i5EmInTWi1RFvFr2_aRXky96YxY6sbWy)

## Resources

We are continuously developing the instructional content for the machine learning curriculum. For now, you can refer to the video challenges in this certification and seek out additional learning resources as needed.

## Contact

If you need any help or have questions, feel free to ask for help in the community.

Happy coding!
