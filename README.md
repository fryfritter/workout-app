## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm install express`

### `npm install --save-dev jest supertest`

### `npm install --save-dev nodemon`

### `npx create-react-app client`

1. After the above - do a npm start to test backend.
2. cd into client to perform `npm run build` followed by a `npm start` - you will see a "react logo"
3. Deploy to Heroku - Add in the following in package JSON Scripts
   "heroku-postbuild": "npm run client:build"
4. In Heroku - Settings - set `SKIP_PREFLIGHT_CHECK=true` in Config Vars

---

## Installing Database "PG and Sequelize" and integrating it with Heroku-Postgres

### `npm install pg pg-hstore sequelize`

### `npm install sequelize-cli -D`

## Run `npx sequelize db:create` to create local DB

### `npm install express dotenv`

### `npm install react-router-dom`

### `npm install cookie-parser`

### `npm install jsonwebtoken`

### `npm install bcryptjs`

### Create the following Database

development: {
username: "postgres",
password: null,
database: "capstone_workout_randomiser_dev",
host: "127.0.0.1",
dialect: "postgres",
},
test: {
username: "postgres",
password: null,
database: "capstone_workout_randomiser_dev_test",
host: "127.0.0.1",
dialect: "postgres",
},
