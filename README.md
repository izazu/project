This code is a JavaScript that fetches data from the PokeAPI, creates a card for each Pokemon, and displays them in a container on a webpage. It also allows the user to search for specific Pokemon by name.

The code uses the Fetch API to get the data from the PokeAPI and uses async/await for handling the promises returned by the Fetch API. The code creates a new div element for each Pokemon and assigns the data to it, it also assigns a background color to the element based on the type of the Pokemon and appends the div element to the container element.

The code includes a search button that allows the user to filter the Pokemon cards based on the search value. When the search button is clicked, the code filters the Pokemon cards based on the search value and only display the ones that match, it does this by getting the value of the search bar and comparing it to the name of each Pokemon.


Built With:

JavaScript
HTML
CSS
Fetch API
PokeAPI