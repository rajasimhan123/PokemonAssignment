Pokedex Assignment
This document explains about the 'PokemonAssignment' single page angularjs application .

Functionalities :

1) Search Pokemon: 
Pokemon can be searched using the search text provided in the top of the page
2)Sorting pokemons
Pokemon can be sorting in both ascending and descending order with fields name and id .
By clicking on the heading of the row will sort(ASC/DESC) the pokemon according to row .
3)Pokemon Details 
By clicking on the specific pokemon displays the details on the overlay page with all the details

Technical Aspects:



Folder structure 

Webcontent
	|
	-------css -> contains all the css feils

	-------data -> contains all the data files (json)

	-------images -> contains all the image files 

	--------scripts -> contains all the script files (js files )

pokemon.html file is the parent file contains all the UI details related to the project 

pokemonApp.js Application module file 

pokemonControllers.js contains all the controllers and related functions

pokemonDirectives.js contains the directives 

pokemonFactory.js contains the factory methods

pokemonServices.js  contains the services 


Installation :

Kindly paste the images folder inside the PokemonAssignment.war folder

Copy the PokemonAssignment.war file in the webapps folder of the server
Restart the server 
http://<ServerIP>:<Portnumber>/PokemonAssignment/pokemon.html

or 

import the PokemonAssignment in eclipse 
Add PokemonAssignment in the server
start the server 

	