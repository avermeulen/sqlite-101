
* queries with parameters:

    * insert
    * select

* query types:

    * update 
    * delete

* migrations

* use async/await

* using queries in an API

    * find all greetings
    * find all languages
    * greet in a selected language

* greetings for a specific user

* create Mocha Tests that's using the database

* Create an API


## Using SQLite with NodeJS steps


```
npm init es6
```

```
npm install sqlite sqlite3
```

```
const  db = await sqlite.open({
    filename:  './my_db.db',
    driver:  sqlite3.Database
});
```