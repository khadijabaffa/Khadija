.. _recipe_generation_page:

Recipe Generation Page
======================

Usage
-----
The recipe generation page allows users to generate recipes based on their selected ingredients. It comprises three main components:
-- **API Search:** The `api_search.dart` file contains the `RecipeService` class, which communicates with the Edamam API to fetch recipes based on user ingredients.
- **Recipe Generation:** The `generation_page.dart` file implements the `GenerationPage` widget, which displays the generated recipes and provides an option to refresh the content.
- **Recipe Model:** The `recipe.dart` file defines the `Recipe` and `Ingredient` classes, which represent recipe data fetched from the API.

API Search (api_search.dart)
-----------------------------
The `RecipeService` class interacts with the Edamam API to fetch recipes based on user ingredients. It provides the following functionalities:
- **fetchRecipesBasedOnUserIngredients():** Fetches recipes from the Edamam API based on the user's selected ingredients.
- **fetchRecipes():** Fetches recipes from the Edamam API using HTTP GET requests and returns a list of dynamic objects representing recipe data.
- **getRecipeNames():** Retrieves the names of recipes generated based on user ingredients.
- **getRecipeUrls():** Retrieves the URLs of recipes generated based on user ingredients.

Generation Page (generation_page.dart)
--------------------------------------
The `GenerationPage` widget displays the generated recipes and allows users to refresh the content. It includes the following components:
- **State Management:** Utilizes stateful widgets to manage the content displayed on the page dynamically.
- **Content Display:** Displays the generated recipe titles and their corresponding URLs.
- **Refresh Button:** Allows users to refresh the content to generate new recipes based on updated ingredients.

Recipe Model (recipe.dart)
---------------------------
The `Recipe` and `Ingredient` classes represent recipe data fetched from the Edamam API. They provide the following attributes and functionalities:
- **Recipe Class:** Represents a recipe item with various properties such as label, image, source, URL, etc.
- **Ingredient Class:** Represents an ingredient item within a recipe with attributes like text, quantity, unit, and food.
- **fromJson() Constructor:** Parses JSON data into instances of the `Recipe` and `Ingredient` classes.
