# Recipe-Management-Application-Springboot
A springboot based application to manage recipes, ingredients, shopping list.

# Recipe Management System

## Summary
A digital platform enabling users to store, search, and organize recipes while automatically generating shopping lists based on selected recipes. This system streamlines meal planning and grocery shopping by centralizing recipe management and ingredient tracking.

## Definitions

### Recipe
A set of instructions and ingredients required to prepare a specific dish, including quantities, preparation steps, and cooking methods.

### Cuisine
A specific style of cooking characterized by distinctive ingredients, techniques, and dishes associated with a particular culture or geographic region.

### Shopping List
A compiled list of ingredients needed to prepare selected recipes, organized for efficient grocery shopping.

## User Stories

### Store New Recipe
As a home cook  
I want to add my recipes with ingredients and instructions  
So that I can digitally preserve and access my recipe collection  

#### Acceptance Criteria
1. User can input recipe name, servings, and preparation time
2. User can add multiple ingredients with quantities and units
3. User can add step-by-step cooking instructions
4. User can specify cuisine type
5. User can save the recipe to their collection
6. User can edit the recipe after saving

### Search Recipes
As a user  
I want to search recipes by ingredients or cuisine type  
So that I can quickly find suitable recipes based on my preferences or available ingredients  

#### Acceptance Criteria
1. User can search by single or multiple ingredients
2. User can filter recipes by cuisine type
3. Search results display recipe names and key details
4. Results update in real-time as search criteria change
5. User can sort results by preparation time or recipe name

### Generate Shopping List
As a meal planner  
I want to generate shopping lists from selected recipes  
So that I can efficiently purchase all required ingredients  

#### Acceptance Criteria
1. User can select multiple recipes for the shopping list
2. System combines ingredients from all selected recipes
3. System consolidates duplicate ingredients and quantities
4. User can modify quantities in the generated list
5. User can export or share the shopping list

## Bonus Features
* User can scale recipe quantities based on desired servings
* User can add photos to recipes and view in gallery format
* User can rate recipes and add personal notes
* User can create meal plans by assigning recipes to specific dates
* User can track pantry inventory and receive alerts for low ingredients
