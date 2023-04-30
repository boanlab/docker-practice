# docker-practice

## dockerfile-flask

  ```
  docker build -t hello-flask .
  docker run -d -p 5000:5000 hello-flask
  curl http://localhost:5000
  ```

## dockerfile-node

  ```
  docker build -t hello-node .
  docker run -d -p 80:8080 hello-node
  curl http://localhost
  ```

## dockerfile-java

  ```
  docker build -t pingpong .
  docker run -d -p 8080:8080 hello-node
  curl http://localhost:8080/ping
  ```
