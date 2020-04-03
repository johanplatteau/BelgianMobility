# api testing of several open api initiatives from Belgiul

## National Belgian railways punctuality

### api to be tested 
https://infrabel.opendatasoft.com/explore/dataset/ruwe-gegevens-van-stiptheid-d-1/api/?

### tests
200 - Api available
200 - data available from three railway operators (NMBS/Thalys/Eurostar)

## Available shared bikes Vilo

### api to be tested 
https://api.jcdecaux.com/vls/v1/stations

### tests
200 - Api available
200 - data available for bike stations in Brussels

## Get carpool parkings in Flanders/Belgium

### api to be tested 
https://wegenenverkeer.be/carpoolparkings/json

### tests
200 - Api available
200 - Schema validation of the json response


# run as postman collection with test data
import "Belgian Mobility.postman_collection.json" collection file in Postman
run the collection in the Collection runner
upload test data file "rail_operators_testdata.csv" in the Collection runner

# run as postman collection with test data
import "Belgian Mobility.postman_collection.json" collection file in Postman
run the collection in the Collection runner

