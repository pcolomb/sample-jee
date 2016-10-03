# Sample Java EE application

## Hello World

curl http:/location/ws/hello

## Todo List

List Todos
curl http:/location/ws/todo

Add Todo

curl -X POST -d text="My Todo" http://localhost:8080/sample-javaee-1.0-SNAPSHOT/ws/todo

Delete Todo

curl -X DELETE http://localhost:8080/sample-javaee-1.0-SNAPSHOT/ws/todo/{id}

Check Todo

curl -X PUT -d done="true" http://localhost:8080/sample-javaee-1.0-SNAPSHOT/ws/todo/{id}

Uncheck Todo

curl -X PUT -d done="true" http://localhost:8080/sample-javaee-1.0-SNAPSHOT/ws/todo/{id}