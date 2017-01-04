# The 2016 Bostonhacks Site

### Todos (Nico)
* Create a proper errorHandler function

### Process for installing and running

* Clone git, and type `npm install`
* Install MongoDB (if not already installed) https://docs.mongodb.com/manual/administration/install-community/
  * Create directory `/data/db`. Note directory for following step. Other directory names may be used, but `/data/db` is the default for mongo.
  * Change permissions for `/data/db` to read/write for user which will run mongo. Example: ```sudo chown -R `id -u` /data/db``` on Mac.
  * Run mongo with `mongod`. 
* Duplicate SAMPLE-.env file, and rename to `.env`. See SAMPLE file for details on fields
* Run with `node server.js`
