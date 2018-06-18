# Project Planning

Recipes Adviser

## Problem Statement

Primary User

A person who wants to cook something different at home with the ingredients he/she already has in the fridge

User Need Statement

This user has some ingredients in the fridge, but don't know how to combine them into a good recipe. This person doesn't want to buy new ingredients yet because he/she wants to make the most from what it's already available, saving money and time. It would be helpful to have an app where the user can input the ingredients and the output is a complete recipe using as many of the given ingredients as possible.


As-is Process Description

1. Access an API with a large database of recipes
2. Get the user input of ingredients
3. Make a request to the API to search for matching recipes
4. List the recipes
5. User chooses the recipe based on its complexity and popularity
6. Make a request to the API to get recipe information
6. Output is the complete recipe with ingredients and instructions
7. Record the result into a .txt file, creating his own Cookbook


To-be Process Description

1. Get user inputs (ingredients)
2. Run a script with an API request to get the list of matching recipes
3. Get user input (choosen recipe)
4. Run a script with an API request to get and print the complete recipe
3. Produce a .txt file


## Information Requirements

### Information Inputs

1. A list of ingredients typed by the User
2. Selected recipe

### Information Outputs

1. A list of matching recipes according to the inputs
2. A .txt file with all the recipes selected by the user over time


## Technology Requirements

### APIs and Web Service Requirements
The following API will provide the recipes:
https://spoonacular.com/food-api
To get the information, I'll also need the Spoonacular API Key


### Python Package Requirements

Following packages will be used...
To download the data from the API: 'json' and 'requests'
To save the file: 'os'
To debug the program: 'pdb'
To make the http request: 'unirest'

### Hardware Requirements

The App will run in the command prompt in my personal machine because it will be an initial test. Besides, for this test, I'm using my private API Key, in which if the maximum amount of requests exceeds, I'll be charged for it.
