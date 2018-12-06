# Grocery Store
Web application of an ecommerce store.

### Deployment

### Mac Instructions
1. clone the repo
`git clone https://github.com/amukhwana/grocery-.git`

2. install app dependencies
``cd grocery_store && npm install``

3. start app
`node server.js`

Backend Setup:

4. install mysql
`brew update && brew install mysql`

5. start mysql
`mysql.server start`

6. create database
`mysql -u root -e 'create database grocery_store_database'`

7. migrate tables
`knex migrate:latest`

### Windows instructions

1. clone repo
`git clone https://github.com/amukhwana/grocery-.git`

2. install node
`https://nodejs.org/en/`

3. go to directory grocery_store and install dependencies
`cd grocery_store && npm install`

4. start server
`npm start`

Backend Setup:

5. install mysql via Windows installer
`use Developer Settings`

6. take care of any dependencies required by mysql
`Could include microsoft visual c++ distributables or .net frameworks`

7. Using MySQL Notifier, start instance

8. Using MySQL WorkBench, create new SCHEMA called grocery_store_database

9. migrate tables
`knex migrate:latest`


### Configuration
- **Platform:** node
- **Framework**: express
- **Template Engine**: angularjs
- **CSS Framework**: bootstrap
- **CSS Preprocessor**: css
- **JavaScript Framework**: angularjs
- **Build Tool**: none
- **Database**: mysql
- **Authentication**: email
- **Deployment**: heroku
