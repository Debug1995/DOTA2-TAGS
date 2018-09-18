# DOTA2-TAGS
The Update Version of The Classification of DOTA2 Players

## Directory structure
Web directory contains the web application 
  - Server.py is the backend 
    - 10 models will be loaded during the initialization
  - models contains the 10 models
  - templates/index is the frontend 
    - The Javascript function Update() is the enterance of the D3 code

## How to run the demo

### dependency
1. Flask
2. urllib2
3. numpy
4. pandas
5. pyspark

### instruction
1. run Server.py
2. access to 127.0.0.0:5000
3. enter any available SteamId(Or you can try my ID: 185399450) 
4. tap the search button and wait for the request 
5. may need to tap the search button twice to refresh the page
  

## Dota2 API: 
- https://dota2api.readthedocs.io/en/latest/
- https://docs.opendota.com/
