# Recipe-and-Ingredient-Recommendation-system

### Description

This was my final project presented in December 2022 at the end of the Data Science course by AllWomen. 

This project developed using Python and the K-nearest neighbors (KNN) algorithm, with the aim to recommend ingredients and recipes based on user input. 

You can find the presentation in the uploaded files in this folder. 



### The process

---

- First, I gathered a large dataset of recipes and their associated ingredients.
- Preprocessed the data by cleaning and formatting it as needed. This included removing duplicates, handling missing values, and encoding categorical variables as numerical values.
- Used feature engineering to extract relevant information from the ingredients list for each recipe. NLP processing was used.
- Trained a KNN model on the ingredient data using a subset of the recipe data as the training set.
- Once the model was trained, it could be used to recommend ingredients and recipes based on user input. To do this, the user could input a list of ingredients they already have, and the model would use the KNN algorithm to recommend additional ingredients that are commonly used with those ingredients in recipes.
- The model can also be used to recommend complete recipes based on a user's input ingredients. The user can input a list of ingredients they have on hand, and the model would use the KNN algorithm to recommend recipes that use those ingredients.
