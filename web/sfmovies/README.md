Project Description:
=============================
Create a service that shows on a map where movies have been filmed in San
Francisco. The user should be able to filter the view using autocompletion
search.

The data is available on [DataSF](http://www.datasf.org/): [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am).

1. Back-end:
Use DataSF API, and here is URL example: http://data.sfgov.org/resource/yitu-d5am.json?title=180&release_year=2013&director=Jayendra
Use PHP cURL lib to get data and use JSON transfer data to Fron-end (search.php)

2. Front-end
Use Ajax send GET request to search.php, the parameters are title、releaseyear, and director. I think title、releaseyear, and director are most popular things to search the filming location 
Convert the address string to latitude and longitude to mark the location on the google map. Using ‘geocode’ to implement.
Create a list to show all results, it can be allowed to click one result and showing on the map view.

This project test page:
http://lou-mi.net/sfmovies/

Mi Lou
