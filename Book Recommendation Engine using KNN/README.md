# Book Recommendation Engine using KNN

## Overview

In this project, you'll create a book recommendation algorithm using the K-Nearest Neighbors (KNN) algorithm. This project is part of the Machine Learning with Python certification and demonstrates your ability to handle and analyze large datasets using machine learning techniques.

## Objective

Develop a function named `get_recommends` that takes a book title (from the dataset) as an argument and returns a list of 5 similar books with their distances from the given book. The function should utilize the K-Nearest Neighbors algorithm to measure the "closeness" of books based on user ratings.

## Dataset

You will use the Book-Crossings dataset, which contains:
- 1.1 million ratings (scale of 1-10)
- 270,000 books
- 90,000 users

## Instructions

1. **Data Import and Cleaning:**
   - Import the Book-Crossings dataset.
   - Clean the data by removing users with less than 200 ratings and books with less than 100 ratings to ensure statistical significance.

2. **Model Development:**
   - Use the `NearestNeighbors` class from `sklearn.neighbors` to develop a model that finds books similar to a given book based on user ratings.
   
3. **Function Implementation:**
   - Implement the `get_recommends` function that takes a book title as an argument and returns a list of 5 similar books with their distances from the given book.

4. **Example Usage:**
   - The function call:
     ```python
     get_recommends("The Queen of the Damned (Vampire Chronicles (Paperback))")
     ```
     should return:
     ```python
     [
       'The Queen of the Damned (Vampire Chronicles (Paperback))',
       [
         ['Catch 22', 0.793983519077301],
         ['The Witching Hour (Lives of the Mayfair Witches)', 0.7448656558990479],
         ['Interview with the Vampire', 0.7345068454742432],
         ['The Tale of the Body Thief (Vampire Chronicles (Paperback))', 0.5376338362693787],
         ['The Vampire Lestat (Vampire Chronicles, Book II)', 0.5178412199020386]
       ]
     ]
     ```

## Implementation Notes

- The returned data from `get_recommends` is a list where:
  - The first element is the book title passed into the function.
  - The second element is a list of five lists, each containing a recommended book and the distance from the recommended book to the given book.

- Optionally, graph the dataset to visualize the distribution of book ratings.

## Submission

After completing the project, save your work and submit your project link. If you're using Google Colaboratory, ensure link sharing is turned on for "anyone with the link."

Example submission link: [Colab Notebook](https://colab.research.google.com/drive/1i5EmInTWi1RFvFr2_aRXky96YxY6sbWy)

## Resources

We are continuously developing the instructional content for the machine learning curriculum. For now, you can refer to the video challenges in this certification and seek out additional learning resources as needed.

## Contact

If you need any help or have questions, feel free to ask for help in the community.

Happy coding!
