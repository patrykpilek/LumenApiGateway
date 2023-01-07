# Lumen Microservices: Create Services and APIs with Lumen

## API Gateway

### Serving Your Application
To serve your project locally, you may use the built-in PHP development server:

Create string for APP_KEY:
[Random string generator](http://www.unit-conversion.info/texttools/random-string-generator/)

```shell
php -S localhost:8002 -t public
```

## Microservice for authors with Lumen

- [x] preparing Lumen for the API Gateway
- [x] creating the controllers for the authors and books Lumen microservices
- [x] unifying Lumen responses for the API Gateway
- [x] registering routes for microservices in Lumen from the Gateway
- [x] preparing the Gateway in Lumen to consume services
- [x] preparing the Lumen components to consume the internal services

## Implementing the functions of the Gateway with Lumen

- [x] obtaining the list of authors from the authors Lumen
- [x] creating an author instance with the authors service
- [x] showing an author instance using the authors lumen microservice
- [x] editing author instances using the authors service
- [x] deleting author instances using the authors Lumen service
- [x] implementing operations for books based on the authors ones
- [x] checking the existence of the author before creating a book
- [x] controlling errors obtained from services

## Implementing the security layer of the microservices architecture with Lumen

- [x] installing and enabling Lumen Passport components
- [x] preparing and configuring Lumen to use Passport
- [x] protecting the Gateway routes with Lumen Passport
- [x] obtaining and using access tokens fo the Lumen API Gateway
- [ ] preparing the API Gateway to Authenticate its requests
- [ ] authenticating direct access to the Lumen authors microservice
- [ ] authenticating direct access to the microservice of books
