# frontend-challenge

**Objective:** Create a simple web application that allows users to search for Pokemon using the [PokeAPI](https://pokeapi.co/). The application should provide a list of search results and detailed information for the selected Pokemon. No need to worry about or implement any CSS styling.

**Best Practices:**
   - Follow best practices for structuring your code, such as using modular JavaScript and well-organized HTML
   - Add comments to explain your code.

**Evaluation Criteria:**

Your solution will be evaluated based on the following criteria:

- Functionality: Does the application meet all the required features?
- Code Quality: Is the code well-organized, readable, and maintainable?
- Error Handling: Does the application handle errors gracefully?
- Best Practices: Are best practices for web development followed?

**Requirements:**

1. **Setup:**
   - Create a new HTML and JavaScript project, or framework of your choice for this challenge.
   - Use the PokeAPI (https://pokeapi.co/) to fetch Pokemon data.

2. **Pokemon Data**
   - Use the endpoint to [https://pokeapi.co/api/v2/pokemon/?limit=1292](https://pokeapi.co/api/v2/pokemon/?limit=1292) to retrieve all the Pokemon

3. **Search Component:**
   - Create a search input field where users can enter a Pokemon's name or ID.
   - Implement a search button or real-time search that updates the results as the user types.
   - Display a list of matching Pokemon as the search results, including their names.
   - Use the Pokemon data from Step 2 to provide the matching results.

4. **Detailed Information:**
   - When a user selects a Pokemon from the search results, display detailed information about that Pokemon.
   - This should include at least the Pokemon's name and an image (use sprites -> front_default).
   - Use the endpoint from the Pokemon Data in Step 2 to retrieve the detailed data for the Pokemon

5. **Implement a cache**
   - Implement a cache for the results in Step 4.

6. **Error Handling:**
   - Implement proper error handling for network requests, and display a user-friendly message if something goes wrong.
   - Handle cases where the searched Pokemon is not found.
