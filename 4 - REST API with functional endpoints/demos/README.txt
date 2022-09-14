BUILDING A REST API WITH FUNCTIONAL ENDPOINTS
Hi. Thanks for watching this course. Here you can find some notes and resources related to the content shown in this module.


Links:
Spring WebFlux documentation for Functional Endpoints
https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html#webflux-fn

Reactive Spring Article
https://github.com/joshlong/reactive-spring-article


cURL commands
curl -v http://localhost:8080/products
curl -v -H "Content-Type: application/json" -d "{\"name\":\"Black Tea\", \"price\":1.99}" http://localhost:8080/products/
curl -v -H "Content-Type: application/json" -d "{\"name\":\"Black Tea\", \"price\":2.99}" -X PUT http://localhost:8080/products/[ID]
curl -v http://localhost:8080/products
curl -X DELETE http://localhost:8080/products