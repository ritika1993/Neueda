## Project title
An application exposing API for URL shortening and persisting them.

## Motivation
Code devlepoment and design assignment.

## Build status
Build status of continus integration i.e. travis, appveyor etc. Ex. - 

[![Build Status](https://travis-ci.org/akashnimare/foco.svg?branch=master)](https://travis-ci.org/akashnimare/foco)
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/akashnimare/foco?branch=master&svg=true)](https://ci.appveyor.com/project/akashnimare/foco/branch/master)

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



## Code style
If you're using any code style like xo, standard etc. That will help others while contributing to your project. Ex. -

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
 
## Screenshots

```
Give examples
```
Include logo/demo screenshot etc.

## Features
 ```
 Shorten URL and Persists it
 Recover orignal URl from short URL
 Fetch Statistic of shorten URL by Id
 Fetch all saved URL statistics
 Delete Shorten URL by Id
 Delet all saved shorten URL
 ```

## Code Example
Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Installation
 ```
This application can be run using Eclipse or the docker image and Redis database setup.
To setup Redis database download the zip file from this link (http://download.redis.io/redis-stable.tar.gz) and then run redis-server.exe, now the application can be eassily made to run fully functional.
 ```
## API Reference


## Tests
Describe and show how to run the tests with code examples.

## How to use?
If people like your project they’ll want to learn how they can use it. To do so include step by step guide to use your project.

## Contribute
A fron-end can eassily be made either using Thymleaf in the same application doing AJAX call to the exposed Rest end-points,
or a seperate fromt-end application can be made which can consume the given rest end points.


## License
Anybody can use this project for learning purpose.
