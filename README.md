# MappaApp
 Maps app built on Google APIs
 
Sign up for a google api key:

Add in a  application.properties file in the resources file.

Add in these lines to the aforementioned application.properties file.

google_api_key = (Put your api key here xxx)

transit_url = http://developer.itsmarta.com/BRDRestService/RestBusRealTimeService/GetAllBus

geocoding_url = https://maps.googleapis.com/maps/api/geocode/json?address=

distance_url = https://maps.googleapis.com/maps/api/distancematrix/json?units=imperial&

Run application and type the below http address into your browser and voila!

http://localhost:8080/home to get to the cat bus map.


Home Page:
![index.html](https://github.com/jadedragon21/MappaApp/blob/main/src/main/resources/static/Screenshot_2021-03-08%20Maps.png)
