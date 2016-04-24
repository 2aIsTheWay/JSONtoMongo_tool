# JSONtoMongo Tool

The JSON to Mongo tool used to upload the JSON data taken from Warren's ETL tool to the MLab Mongo database

## Directions

NOTE: Node.js must be install for this Tool to work.    
  
* After cloning the repository, run npm install to install dependencies.  
* A 'children.json' file is needed, which contains the children data in a formatted way. The file should be in the same directory as the tool.  
* A config file will have to be made that contains all database information (URI, username, password). An example config file is included.  
* Once the above is complete, run 'node JSONtoMongo' and the tool will add all the data to a Childrens collection on the database.
