---
title: Realtor-App
layout: page
---

A web application built on a vue-nest scaffolding. The application has an API backend built on Nest.js and a web UI frontend built on Vue.js. Nest.js and Vue.js are JavaScript frameworks.

## GitHub Repository

[MarkWiltberger/vue-nest-web-app\_\_realtor-app: realtor-app built on vue-nest scaffolding (github.com)](https://github.com/MarkWiltberger/vue-nest-web-app__realtor-app)

## The Backend

The backend is an API which serves requests for a realtor application. The user may create accounts and search for realty listings, and create new listings.

### The API Endpoints

The endpoints for the API are:

- **POST /auth/signup/{userType}**  
  _Sign up a user of a designated user type._
- **POST /auth/signin**  
  _Sign in a user with username and password._
- **POST /auth/key**  
  _Generate a product key to authorize API requests._
- **GET /home**  
  _Get a list of realty listings._
- **POST /home**  
  _Create a new realty listing._
- **GET /home/{id}**  
  _Get a specific realty listing._
- **PUT /home/{id}**  
  _Update a specific realty listing._
- **DELETE /home/{id}**  
  _Delete a specific realty listing._
