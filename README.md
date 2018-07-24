# REST Switch
This application handle all request incoming from third application and forward all request to core application.

## Built With

* [node.js](https://nodejs.org/en/docs/) - Framework
* [express.js](https://expressjs.com/) - REST
* [mysql.js](https://github.com/mysqljs/mysql) - Database mysql
* [connect-db2.js](https://www.npmjs.com/package/connect-db2) - Database db2
* [log4j.js](https://log4js-node.github.io/log4js-node/) - Logger

### Installing

Go to your workspace directory and create package.json
```
npm init
```

Express
```
npm install express --save
```

Database (Choose which one your database)
```
npm install mysql --save
npm install connect-db2 --save
```

Logger
```
npm install log4js --save
```

### Configuration
File configuration
```
cd $GOPATH/build/cfg
``` 
Here some example of configuration
```
## Application PORT
app.port=8080
app.user=aplikasi
app.pass=aplikasi123
## Database
db.url=127.0.0.1
db.port=3306
db.driver=mysql
db.dbname=api
db.user=api
db.pass=api123
``` 

### Running

Running applicaion
```
npm start
``` 

## Authors

* **Ivan Aribanilia** - *Developer* - [Githubs](https://github.com/ivanj4u)

## License

Copyright 2018 [Ivan Aribanilia](mailto:angko.j4u@gmail.com).
Please tell me if you interested with this project