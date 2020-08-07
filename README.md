# eBudget

Budgeting can be hard. Our app makes it easy to create a well-organized budget for all your personal financial needs.

#### [Live Demo](http://ebudget-fsa.herokuapp.com/)

![eBudget Demo](https://media.giphy.com/media/L1DlQrW4MPSrq8cGVG/giphy.gif)

## Technologies

* [Plaid API](https://plaid.com/docs/)
* Frontend – [React](https://reactjs.org/), [Redux](https://redux.js.org/)
* Backend – [Express](https://expressjs.com/), [Sequelize](https://sequelize.org/), [PostgreSQL](https://www.postgresql.org/)
* Style – [Materialize CSS](https://materializecss.com/), CSS, [Charts.js](https://www.chartjs.org/docs/latest/)

## Installing

```javascript
git clone https://github.com/Team-Orochimaru/financial-planner.git

cd financial-planner

npm install

npm run seed

createdb financial-planner

npm run start-dev
```

Visit [localhost:8080](http://localhost:8080) to view the app on your local server.

If you want to run the server and/or webpack separately, you can also run `npm run start-server` and `npm run build-client`.

## Customize

Create a file called secrets.js in the project's root directory. This file is listed in the project's .gitignore file by default, and is only required in your environment for developmental purposes. The file attaches API-specific environment variables that you need to get started as a developer. **Be sure to keep the information contained in your secrets.js file confidential (i.e. don't push it to GitHub).**

Example secrets.js file:

```
process.env.PLAID_CLIENT_ID = 'Your Plaid Client ID goes here';
process.env.PLAID_SECRET = 'Your Plaid Secret goes here';
process.env.PLAID_PUBLIC_KEY = 'Your Plaid Public Key goes here';
```

## Authors

* Rob Arcand
* Ian Gelfand
* Iskak Mantyubetov
* Vasyl Semak
