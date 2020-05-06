# Platoblockchain News Api
News Apis 

# news api

## 1. https://us-central1-plato-blockchain.cloudfunctions.net/newsApi 
    - @params
    - Query parameters 
    - GET Method
     - q      (string)    e.g. q=blockchain 
     - limit  (integer)   limit=10
     - offset (integer)   offset=0
     - @response
       {
         "status" : "ok",
         "articles" : [] <-- array of items
       }
     Query parameter i.e q should be a string e.g. blockchain, bitcoin.
     
## 2. https://us-central1-plato-blockchain.cloudfunctions.net/newsApi
    - @params
    - GET Method
    - Query parameters 
     - q      (string) e.g. q=latest 
     - limit  (integer)   limit=10
     - offset (integer)   offset=0
     - @response
       {
         "status" : "ok",
         "articles" : [] <-- array of items
       }
      Query parameter i.e q should be 'latest'
       
