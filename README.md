# Dockerizing node js apps

## Setting up Enviromental variables
Create an ```config.env``` file in the root directory and add the folloing in
```javascript
PORT=5000
MONGO_URI= <Your mongo db uri>
NODE_ENV=development
```
## Testing the connection
To test the application you can use the temporary data provided in ```utils``` folder 
To upload the data 
```bash
node utils/importData.js --import
```
This will test the database and create an post collection in the database
## Running the api 
In the root directory 
``` Bash
yarn install && yarn start
```
## Running the api 
``` Bash
cd client
yarn install && yarn start
```




