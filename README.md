1) download the project
2) Install the dependencies using npm install command (package.json is there in source folder)
2) start mongod process
3) Import the "item" collection: mongoimport --drop -d mongomart -c item data/items.json
4) Import the "cart" collection: mongoimport --drop -d mongomart -c cart data/cart.json
5) 
Run the application by typing "node mongomart.js" in the mongomart directory.
In browser, visit http://localhost:3000
