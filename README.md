# creating database

- give database and collection name for creating

# network access

- Add IP Adress : 0.0.0.0./0 for allowing access from any IP...

- If you want to give Ip Adresss, you must have a static IP Adress.(not dinamic)

# Connecting with mongosh or compass

- click Connect --

mongosh "mongodb+srv://cluster0.aaas.mongodb.net/appbookstore" --apiVersion 1 --username appuserbookapi

cluster0-shar-01-01.2.aaas.mongodb.net:27017

mongoimport --host cluster0-shar-01-01.2.aaas.mongodb.net:27017 --db appbookstore --collection employees --type json --file employees.json --jsonArray --authenticationDatabase admin --ssl --username appuserbookapi

mongodb+srv://appuserbookapi:\***\*\*\*\*\*\*\***@cluster0.aaas.mongodb.net/test
