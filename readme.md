# api testing of several open api initiatives from Belgiul
# National Belgian railways punctuality

## api to be tested 
https://infrabel.opendatasoft.com/explore/dataset/ruwe-gegevens-van-stiptheid-d-1/api/?

## tests
200 - Api available
200 - data available from three railway operators (NMBS/Thalys/Eurostar)

## run as postman collection with test data
import "Belgian Mobility.postman_collection.json" collection file in Postman
run the collection in the Collection runner
upload test data file "rail_operators_testdata.csv" in the Collection runner

## run as newman cli

newman run "Belgian Mobility.postman_collection.json" -d rail_operators_testdata.csv -n 3
