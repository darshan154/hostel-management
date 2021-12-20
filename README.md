# Hostel-Management
Manage Your Hostel 

## Development and Installation

### Install Backend Dependencies
- `npm install`

### Install Frontend Dependencies
- `cd client`
- `npm install`

### Setup up dev_keys for database
- Either run local MongoServer or,
- Setup Mongo Server at online platform like mlab and Create a keys_dev.js file in [config](https://github.com/starkblaze01/Hostel-Management/tree/master/config) folder and set up:-
``` 
module.exports = {
  mongoURI: YOUR_LOCAL_MONGO_SERVER_URI,
	secretOrKey: YOUR_SECRET
}; 
```
### Run the application
- `npm run dev`

### For testing
- `npm run test`
