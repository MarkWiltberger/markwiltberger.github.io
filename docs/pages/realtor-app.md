---
layout: page
---
# Realtor-App REST API Project
A web application built on a vue-nest scaffolding. The application has an API backend built on Nest.js and a web UI frontend built on Vue.js. Nest.js and Vue.js are JavaScript frameworks.

## GitHub Repository
[MarkWiltberger/vue-nest-web-app__realtor-app: realtor-app built on vue-nest scaffolding (github.com)](https://github.com/MarkWiltberger/vue-nest-web-app__realtor-app)
## The Backend
The backend is an API which serves requests for a realtor application. The user may create accounts and search for realty listings, and create new listings.
### The API Endpoints
The endpoints for the API are:  
 - **POST /auth/signup/{userType}**  
*Sign up a user of a designated user type.*  
 - **POST /auth/signin**  
*Sign in a user with username and password.*  
 - **POST /auth/key**  
*Generate a product key to authorize API requests.*  
 - **GET /home**  
*Get a list of realty listings.*  
 - **POST /home**  
*Create a new realty listing.*  
 - **GET /home/{id}**  
*Get a specific realty listing.*  
 - **PUT /home/{id}**  
*Update a specific realty listing.*  
 - **DELETE /home/{id}**  
*Delete a specific realty listing.*
