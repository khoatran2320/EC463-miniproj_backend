This is the server code for EC463 Mini Project. The server is hosted live on Heroku. 

## APIs
- `/`: returns a greeting.
- `/search_keyword`: searches the FDC data base for foods based on `query` parameter.

Other storage and authentication routines were performed directly through Firebase client API. 

## To run locally
1. Download code from repo
2. Run `sudo npm install`
3. Run `node index.js`

The server will run on `localhost:3000`