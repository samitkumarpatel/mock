### Mock

- To know more details , click [wiremock](https://wiremock.org/)

- To run the mock server by using `docker` , run below command.

```sh
docker run -it --rm \
  -p 8080:8080 \
  --name wiremock \
  -v $PWD:/home/wiremock \
  wiremock/wiremock:2.35.0
```

To mock admin console

```sh 
http://localhost:8080/__admin/

```