# Spring-Boot-Spring-Security-jwt
An application with Spring Boot and Spring Security with JWT Authentication and Authorization

add a user, check if the user is in the datbasing using Postman

register a user:
post
http://localhost:8080/api/v1/auth/register

{
    "firstname":"Sven",
    "lastname":"Eriksson",
    "email":"Sven@google.com",
    "password":"1234"
}

check if the user is in the database:

post
http://localhost:8080/api/v1/auth/authenticate

{
    "email":"Sven@google.com",
    "password":"1234"
 }


