# StackAPI

This is a full stack web application made with spring boot and ReactJs in the frontend. Relevant blog articles on this are


## Setting up Locally

* Install [docker](https://www.docker.com) and docker-compose on your system.
* Install `psql` for your system which is a client for the Postgresql database.
* Go the root directory of the system
* Run `docker-compose up --build`
* After the containers are up and running , run `psql -h 127.0.0.1 -d flamup -p 5432 -U postgres -c "\copy clothes FROM 'data2.csv' DELIMITER ',' CSV";`.

Now continue to https://localhost:8443, the application should be up and running.

### Caveats

* In case you are using chrome, go to chrome://flags/#allow-insecure-localhost and Enable the option that says "Allow invalid certificates for resources loaded from localhost".

