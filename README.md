# STORE API

## For locally run the API
1. create a `.env` file.
2. add `MONGO_URI` variable and store your mongoDB collection url to it.
3. run command `npm install`.
4. run command `npm start` or `nodemon app.js`.
5. go to `local host` port `3000`.

## What this API do
- create new product on your database by using `createProduct`.
- get all the products you have by using `getAllProduct`.
- get a single product you have by their id by using `getProduct`.
- update your product detail by using `updateProduct`.
- delete your product by using `deleteProduct`.
