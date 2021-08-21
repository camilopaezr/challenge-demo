# Live example
Check out a running example in this URL: http://dev.devopschallenge.link/

# Running the app

_Required Node version: 12.*_

## Update the subdomain
You need to replace `http://dev.devopschallenge.link` for your subdomain URL in 
+ `app/views/static/js/main.2cd554a3.chunk.js` 
+ `app/views/static/js/main.2cd554a3.chunk.js.map`

## Set database environment variables
The database engine used is MySQL tested against version 5.7. Port is set as default (3306).

Set the following environment variables with the proper values according to your database instance:
+ `DB_HOST`
+ `DB_USER`
+ `DB_PASS`
+ `DB_NAME`


## Run the app

Use the following commands for running the application:

```
npm install
```

```
npm start
```

---

Find more detailed information for this application at https://github.com/bezkoder/react-express-mysql.

Good luck!
