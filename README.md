# project-library
A javascript project of a recipe list to practice filtering, sorting and searching with JavaScript.

# Solutions
- createCard() function to create the recipe cards.
- createList() function to repeatedly create recipe cards using the createCard() function based on the list the function is provided.
- various filtering and sorting functions that require a list argument and a value depending on the function and they return a filtered/sorted list.
- refresh() function that "chains" the functions one to another and the resulting list is created in html using the createList() function.
- filters/sorting/search bar all have event listeners to activate the refresh() function.
- addCuisineFilters() function to populate the cuisine filter dropdown menu with all the possible cuisine values in the original recipe list.

# Demo
A version of the site is deployed on netlify on the following link: https://gregarious-dango-5488ff.netlify.app/