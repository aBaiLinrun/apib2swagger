# Group Users

## A user [/user]

### Get one user [GET]
+ Response 200 (application/json)
  + Attributes (User)
+ Response 500 (application/json)

## Some users [/users]

### Get a collection of users [GET]
+ Response 200 (application/json)
  + Attributes (array[User])
+ Response 500 (application/json)

# Data Structures

## User (object)
+ id: `12345678` (string, required)
+ name: `john` (string, nullable, required)

## Users (object)
+ users(array[User], nullable, required)
