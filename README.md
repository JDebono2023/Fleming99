# Fleming99
Coursework for Web GIS Development Weeks 1 &2

Shark Spotting Map
https://jenniferdebono.github.io/Fleming99/W1/SharkMap/sharkMap.htm

JavaScript: Hello World
https://jenniferdebono.github.io/Fleming99/W1/HelloWorld.htm


JavaScript: Directions
V1: with class issued API
https://maps.googleapis.com/maps/api/directions/json?origin=Disneyland&destination=Universal+Studios+Hollywood&key=AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

Results: Returns appropriately expected series of information for directions

V2: with personal API key
https://maps.googleapis.com/maps/api/directions/json?origin=Disneyland&destination=Universal+Studios+Hollywood&key=AIzaSyBuYSt0c0U4mITHOit9WZGoJvhHecCt3Hc

Results:
{
   "error_message" : "This API project is not authorized to use this API.",
   "routes" : [],
   "status" : "REQUEST_DENIED"
}

Returned to the Google Maps Platform console and enabled Directions API. Refreshed the V2 URL with the personal API key, and enableing allowed the URL to call and
display the directions information as expected

Results Documented at: 
https://jenniferdebono.github.io/Fleming99/W1/apiDirections.json
