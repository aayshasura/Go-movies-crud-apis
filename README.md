##This repo contains code for creating a server with 5 end points which can be used to read all ,read by id, create , delete and update movies to a slice of struct movies  
To view the list of all movies use - GET: http://localhost:8000/movies  
To view the list of a movie of a specific id use - GET: http://localhost:8000/movies/{id}  
To add a new movie to the list - POST: http://localhost:8000/movies  
To update a movie with an existing id to the list - PUT: http://localhost:8000/movies/{id}  
To delete a movie with an existing id to the list - DELETE: http://localhost:8000/movies{id}