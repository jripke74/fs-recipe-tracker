# fs-recipe-tracker

In this workshop, you will review working with JavaScript objects by building a recipe tracker.

Step 1
In this workshop, you will create a recipe tracker using JavaScript objects.

Start by creating an empty array named recipes. This is the array you'll push the recipe objects into later.

Step 2
Create an object named recipe1. Inside the recipe1 object, create a name property with the value "Spaghetti Carbonara".

Also inside the recipe1 object, create an ingredients property with an array as the value. The array should have spaghetti, Parmesan cheese, pancetta, and black pepper inside it.

Create another ratings property with array value. The array should have 4, 5, 4, and 5 inside it.

Step 3
Add the following properties to the recipe1 object:

Key	Value
cookingTime	22
totalIngredients	null
difficultyLevel	""
averageRating	null
The properties with null and empty string values will be updated later after you calculate them.

Step 4
Create another recipe2 object with the following properties and values:

Key	Value
name	Chicken Curry
ingredients	["chicken breast", "coconut milk", "curry powder", "onion", "garlic"]
ratings	[4, 5, 5, 5]
cookingTime	42
totalIngredients	null
difficultyLevel	''
averageRating	null

Step 5
Before you move on, you should practice how to access properties from an object.

You can use either dot (.) or bracket ([]) notation to do this. Here's an example:

Example Code
const person = {
  name: 'John',
  age: 30,
  job: 'Software Engineer'
};

console.log(person.name); // John
console.log(person['age']);  // 30
Access the name properties of both recipe1 and recipe2, and assign them to the variables recipe1Name and recipe2Name, respectively.

Next, access the cookingTime properties of both recipes and assign them to the variables recipe1CookingTime and recipe2CookingTime, respectively.

Make sure all the variables you created are logged to the console.

Step 6 Passed
A third recipe3 object has been filled in for you. It has the same properties as recipe1 and recipe2.

You should now push the three objects into the recipes array. To do this, you can use the push() method.

Use the push() method to push all the recipe objects into the recipes array. Make sure to push recipe1, recipe2, and recipe3 in that order.

Also delete the recipe1Name, recipe2Name, recipe1CookingTime, and recipe2CookingTime variables, and the console.log statements which log those variables.

Step 7
Now, you should work on calculating the averageRating, totalIngredients, and the difficultyLevel for each recipe in the recipes array.

Start by creating a getAverageRating function that takes a single argument, which is an array with ratings. Inside the function, calculate the average rating from the array passed to the function.

Your getAverageRating function must return a number.

Step 8
Create a getTotalIngredients function that takes a single argument, representing an array with ingredients, and returns the number of ingredients from the array passed to the function.

Step 9
Create a getDifficultyLevel function that takes a number indicating the cooking time as a parameter.

If the cooking time is less than or equal to 30, the function should return "easy". If it is less than or equal to 60, the function should return "medium". Otherwise, the function should return "hard".

Step 10
It's time to test each of the functions. You can use any of the recipes for this, but this tutorial will start with recipe1.

Create three new variables: recipe1AverageRating, recipe1TotalIngredients, and recipe1DifficultyLevel. Assign them the values by calling the corresponding function for each variable and passing in the appropriate recipe1 property.

Finally, log each variable to the console to see the results.

Step 11
You can now fill in each item of the recipes array with values for the averageRating, totalIngredients, and difficultyLevel properties.

For now, access the averageRating, totalIngredients, and difficultyLevel of recipe1 and set them to the appropriate results of function calls and arguments.

Step 12
Repeat the process for the averageRating, totalIngredients, and difficultyLevel properties of recipe2.

Step 13
The averageRating, totalIngredients, and difficultyLevel properties of recipe3 have been filled in for you.

Now, log the recipes array to the console to see all its items filled with the updated values.

With that, your recipes tracker project is complete.