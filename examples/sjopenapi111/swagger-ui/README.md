# Example: Swagger UI

## Prerequisites

- HTTP Server (All http server can be used for example: Apache, Nginx, http-server, etc)
    - http-server ([how to install](https://www.npmjs.com/package/http-server))

## Running example

- Copy openapi spec to swagger location.
```bash
    $ cd <example sjopenapi111 swagger-ui path>
    $ cp ../../../sjopenapi111/openapi.json openapi/
```

- Running `http-server`

```bash
    $ http-server
    Starting up http-server, serving ./
    Available on:
        http:127.0.0.1:8080
```

- Open http-server URL with your favorite browser: [http://127.0.0.1:8080](http://127.0.0.1:8080)

<p align="center">
  <img src="assets/img/swagger-ui-sample.png"  width=750>
</p>
