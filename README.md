# Fleming99
## Coursework for Web GIS Development Weeks 1 &2

### Google Maps Tutorial: Shark Spotting Map

https://jenniferdebono.github.io/Fleming99/W1/SharkMap/sharkMap.htm

* Includes basic css 


### Google Maps Platform: Maps, Routes & Places

1. JavaScript API (HTML Interactive Map)

https://jenniferdebono.github.io/Fleming99/W1/HelloWorld.htm

* Location set to Kildrummy Castle, Scotland


2. Directions API (JSON Return)

* V1: with class issued API

https://maps.googleapis.com/maps/api/directions/json?origin=Disneyland&destination=Universal+Studios+Hollywood&key=AIzaSyA5a1FoKmbmQ1djPh6pRx7oiknBf3ACNOE

* Results: Returns appropriately expected series of information for directions

* V2: with personal API key

https://maps.googleapis.com/maps/api/directions/json?origin=Disneyland&destination=Universal+Studios+Hollywood&key=AIzaSyBuYSt0c0U4mITHOit9WZGoJvhHecCt3Hc

- Results:
{
   "error_message" : "This API project is not authorized to use this API.",
   "routes" : [],
   "status" : "REQUEST_DENIED"
}

- Returned to the Google Maps Platform console and enabled Directions API. Refreshed the V2 URL with the personal API key, and enableing allowed the URL to call and
display the directions information as expected

- Results Documented at: 
https://jenniferdebono.github.io/Fleming99/W1/apiDirections.json


### 3. Places API (JSON Return)
https://maps.googleapis.com/maps/api/place/details/json?place_id=ChIJN1t_tDeuEmsRUsoyG83frY4&fields=name,rating,formatted_phone_number&key=AIzaSyBuYSt0c0U4mITHOit9WZGoJvhHecCt3Hc

- Result:
{
   "html_attributions" : [],
   "result" : {
      "formatted_phone_number" : "(02) 9374 4000",
      "name" : "Google Workplace 6",
      "rating" : 4.1
   },
   "status" : "OK"
}