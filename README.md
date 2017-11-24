[![Build Status](https://semaphoreci.com/api/v1/ayoo/go-mux-postgres-rest/branches/master/shields_badge.svg)](https://semaphoreci.com/ayoo/go-mux-postgres-rest)


Simple RESTful API using Golang and Postgres

##### to run the serve locally
$ export APP_DB_NAME=db_name APP_DB_USERNAME=username APP_DB_PASSWORD=password
$ go install
$ bin/mux-postgres-rest

Open web browser and type http://localhost:8000