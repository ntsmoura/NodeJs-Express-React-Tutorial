# NodeJs-Express-React-Tutorial
Updated version of mfkri's fullstack Node + React Tutorial : https://mfikri.com/en/blog/node-express-react-mysql

 - Changed Switch and History imports to Routes and Navigate, since Switch and History are deprecated and don't work anymore
 - "import 'bulma/css/bulma.min.css';" Included for Bulma works properly. 

# How to run

If you have all needed dependencies:

Open 1 terminal, go to **backend** folder and run: 
```
npx nodemon index
``` 
Open another terminal, go to **frontend** folder and run:
```
npm start
```
Then access http://localhost:3000/ on your browser.

If you don't have, run ``` npm install ``` on both **backend** and **frontend** folders, before run the previous commands.

**obs**: Make sure to have a MySQL database named "mern_db", and with a table named "products" running on localhost.
