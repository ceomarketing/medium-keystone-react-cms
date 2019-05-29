# Building A Node CMS With KeystoneJS, Mongo DB, React and Redux

Read the full article on [Medium](https://itnext.io/building-a-node-cms-with-keystonejs-mongo-db-react-and-redux-part-i-ae5958496df2)

*Important Note*: This is just an example and it's not meant to be used in production.

### Installing

Clone or download the GitHub repository. Navigate to the folder and 

```
npm install
```

Once all node modules are installed 

```
npm start
``` 

The project should be running on http://localhost:3000

You can access the admin panel at http://localhost:3000/keystone/ (email: admin@keystonejs.com / password: admin)


### Build steps
Clone the repo

run npm i or yarn

In another shell window, run mongod command to start the MongoDB

run npm run compile or yarn run compile to compile the client code

run npm run start or yarn run start to start the server

At this point, you will be able to see LOADING screen when you go to locahost:3000/index.html. To see a recipe,

go to localhost:3000/keystone/signin

sign in with credentials as admin@keystonejs.com and admin

click on Recipes to add a dummy recipe

after adding a dummy recipe, go back to localhost:3000/index.html and you will see your recipe after LOADING
