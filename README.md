# TVMazeApplication
It is a web application which fetches tv shows from TVMaze API and helps user to search for particular shows. It was made using AngularJS
and Node.js, It allows user to - 
- Search for television shows that matched the submitted query
- used the factory pattern based on $resource in this AngularJS application to interface with the API
- created a custom directive to render each search result.
- Added a details button for each show returned from the search.
- Created a new route that included the show id.
- Used the resolve option inside the routeProvider to get show details by id from the service.
- In details page,  if the tv show don't have any image for cast members then provided default image, making sure to look at data structure to determine that there is no image for the character or person.
