1. npm install knex sqlite3 express helmet cors express-session bcryptjs
   - helmet: helps secure Express apps by setting various HTTP headers
   - cors: providing a connet/express middleware that can be used to enable CORS with various options
2. knex init to create knexfile.js
   2a. npm init -y to create package.json file
3. Create database with dbConfig.js to have knex functions
   - cd into database folder
   - create a migration (knex migrate:make [migration_name])
4. Create api server
   - server.js
5. create index.js to run the server (port: 7070)
6. create 'users' folder
   - users-model.js
   - users-router.js
