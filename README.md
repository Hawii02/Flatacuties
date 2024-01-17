Summary of the project
This project involves fetching and displaying animal details from a specified URL and allowing users to interact with the displayed information.

Description
This script retrieves animal data from a given URL endpoint (http://localhost:3000/characters) and displays it on an HTML page. The displayed details include the animal's name, image, and voting counts.

Functionalities:
getAllAnimals()
The getAllAnimals() function fetches data from the specified URL using the fetch() API. It processes the received JSON data and dynamically creates HTML elements to display each animal's name as a clickable link. Upon clicking an animal's name, it updates the displayed information including the name, image, and voting counts.

Updating Votes
Users can interact with the displayed information by adding votes to their preferred animals. Clicking on the "Add Votes" button increases the vote count for the selected animal.

Resetting Votes
There's a reset button (reset-button) available that sets the total vote count back to zero.

Languages used for the front-end
Css and Html. (CSS was used for styling the page).

Languages used for the functionality
*Javascript - giving the functionality of the buttons once clicked and fetch data from db.json
*(Used a database Json) to display details and images of animals.

