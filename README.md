# Poker_Equity_Api
## Summary

- Setup :rocket:
  - Node.js
  - MongoDB
  - Project

- Data Model :file_folder:
  - Equity model
  - Result model

## Setup

### Node.js

Node.js is a prerequisite, to get it on your system: https://nodejs.org/en/

### MongoDB

MongoDB Server (Community Edition) is also a prerequisite, to get it on your system : https://docs.mongodb.com/manual/installation/

  - `sudo service mongod start` to start your MongoDB server
  - `mongo` to start the mongo shell and get your mongodb url
    - example : mongodb://127.0.0.1:27017/

### Project

  - `git clone` the repo :octocat:
  - `npm install express`
    - to see more documentation about express : https://www.npmjs.com/package/express
  - `npm install mongoose`
    - to see more documentation about mongoose : https://www.npmjs.com/package/mongoose
  - `npm install body-parser`
    - to see more documentation about body-parser : https://www.npmjs.com/package/body-parser
  - Edit the config.js file with your mongodb url
  - `node index.js` to start the API
    - The output should be `Server is listening on port 3000` and `Successfully connected to the database`

## Data

### Equity model

  - title (String)
  - heroHand (String)
  - vilainHand (String)
  - heroEquity (String)
  - vilainEquity (String)
  - splitEquity (String)

### Result model

  - heroHand (String)
  - ev (String)
  - callingRange (Object)
  - gameConfiguration (Object)
