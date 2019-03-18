## Project title
An application exposing API for URL shortening and persisting them.

## Motivation
Code devlepoment and design assignment.

## Tech/framework used

<b>Built with</b>
- JDK 8 or later (https://www.oracle.com/technetwork/java/javase/overview/java8-2100321.html)
- Spring Boot(https://spring.io/projects/spring-boot)
- Spring Rest (https://spring.io/guides/gs/rest-service/)
- Spring Data Redis(https://spring.io/projects/spring-data-redis)
- Redis (https://redis.io/)
- Spring HATEOAS (https://spring.io/projects/spring-hateoas)
- Swagger UI (https://swagger.io/tools/swagger-ui/)
- Docker (https://www.docker.com/)


## Installation
 ```
This application can be run using Eclipse or the docker image and Redis database setup.
To setup Redis database download the zip file from this link (http://download.redis.io/redis-stable.tar.gz) and then run redis-server.exe, now the application can be eassily made to run fully functional.
 ```
 
## Project Structure
```
all the packages and intention behind the architecture.
And brief explanation for selecting above technology stack
```
 
## Screenshots

```
Actuator screen shots
```
```
Swagger screenshots
```
```
Postman Screenshots
```

Include logo/demo screenshot etc.

## API Features
 ```
 Shorten URL and Persists it
 Recover orignal URl from short URL
 Fetch Statistic of shorten URL by Id
 Fetch all saved URL statistics
 Delete Shorten URL by Id
 Delet all saved shorten URL
 ```

##Few Code Example
```
 Screenshot for logic code snippet and explanation
 ```

 ```
 Screenshot for hateoas code snippet and explanation
 ```

```
 Screenshot for swagger ui code snippet and explanation
 ```
 
## Tests
```
Unit test cases have been wriiten using JUnit in Spring Boot and the test methods perform the following tasks:
Test for shortening URL and then retreiving the orignal URL based on the shortened URl and than matching them both.
Testing for statistics check(number of request, number of redirects) of the shortened URL>
```

## Contribute
A fron-end can eassily be made either using Thymleaf in the same application doing AJAX call to the exposed Rest end-points,
or a seperate fromt-end application can be made which can consume the given rest end points.


## License
Anybody can use this project for learning purpose.
