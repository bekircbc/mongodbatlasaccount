# creating database

- give database and collection name for creating

- write this code on terminal in dataImport folder..

        mongoimport --host <cluster0-shar-01-01.2.aaas.mongodb.net:27017>--db
        <appbookstore> --collection <employees> --type json --file <employees.json> --jsonArray --authenticationDatabase admin --ssl --username <appuserbookapi>

        take this from cluster>primary

        cluster0-shar-01-01.2.aaas.mongodb.net:27017

# network access

- Add IP Adress : 0.0.0.0./0 for allowing access from any IP...

- If you want to give Ip Adresss, you must have a static IP Adress.(not dinamic)

# Connecting with mongosh or compass

- click Connect -- connect with MongodbShell -- write code to terminal

        mongosh "mongodb+srv://cluster0.aaas.mongodb.net/appbookstore" --apiVersion 1 --username appuserbookapi

- click Connect -- connect with Mongodb Compass -- write code to terminal

        mongodb+srv://appuserbookapi:thisispassword@cluster0.aaas.mongodb.net

# Connecting with NoSQLBooster

- click connect - create in NOSqlBooster -- Authentication - password

- click Connect -- connect with Mongodb Compass -- write code to terminal

        mongodb+srv://appuserbookapi:thisispassword@cluster0.aaas.mongodb.net
