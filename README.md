## Getting the Data Onto the page

The DOM allow us the write Data to the page by setting the innerHTML
+ pass the type parameter to getData function so that types could be identified
+ take out base URL and create a constant from it 
+ modify open() method, add baseURL + type. this will append the base URL with the type that we're parsing in, so that could be people, films, vehicles, or species.
+ modify HTML page accordingly

## Unpacking the data onto the DOM (main1.js)

the combination of JSON data and the DOM allows us to present our data to our users
+ to unpack the data, firstly access them by .dir() method
+ set innerHTML to "data.results" to display the objects results
+ overwrite existing data variable with "data.results"
+ add a forEach() loop for data.results and then display the name by add name property to item
+ use += instead of =, so that the result wont be overwrited
+ var el = document.getElementByID("data"), el.innerHTML = "" to clear up the screen every time button is clicked

## Tabular Data - Part one (main2.js, main3.js)

## Pagination 