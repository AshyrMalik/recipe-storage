# recipe-storage

### Recipe Manager Web Application

This JavaScript-based web application allows users to create, manage, and search for recipes easily. Below is a summary of the key features and functionality implemented in the code:

#### Features:
1. **Add Recipes:**
   - Users can input the name, ingredients, and instructions for a new recipe. Upon submission, the recipe is added to an array of recipes and displayed in a list.

2. **Edit Recipes:**
   - Users can edit existing recipes by clicking the "Edit" button. The recipe details are populated back into the form, allowing for modifications. After editing, the old version of the recipe is removed, and the updated one is added back to the list.

3. **Delete Recipes:**
   - Users can delete a recipe from the list by clicking the "Delete" button.

4. **Search Recipes:**
   - A search function enables users to filter recipes based on their name. The search is case-insensitive and displays only the matching recipes.

5. **Form Management:**
   - The form is automatically cleared after each submission, preventing duplicate entries and ensuring a smooth user experience.

#### Functions:
- **addRecipe()**: Handles the creation and addition of new recipes to the list.
- **clearform()**: Clears the form inputs after a recipe is added or edited.
- **displayRecipe()**: Dynamically updates the displayed list of recipes based on the current state of the `recipes` array.
- **editRecipe(id)**: Allows users to modify existing recipes by pre-filling the form with the selected recipe's details.
- **deleteRecipe(id)**: Removes a recipe from the list based on its unique identifier.
- **searchRecipes()**: Filters the recipe list based on user input in the search bar.

This project is an excellent starting point for building a simple yet functional recipe management web application.
