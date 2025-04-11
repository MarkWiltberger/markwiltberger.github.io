---
title: Realtor App Backend Project
layout: page
---
---

<br />  
<div  style="text-align: center;"><img src="/assets/realtor-app-concept.png"  alt="Realtor App concept" style="width: 480px; height: auto;"></div>

## Quick Links

- **[GitHub Repository](https://github.com/MarkWiltberger/vue-nest-web-app__realtor-app){:target="_blank"}:** See the code at the GitHub repository.
- **[Application Documentation](https://www.postman.com/science-meteorologist-84254413/realtor-app-online/documentation/gu1pgpa/realtor-app-online){:target="_blank"}:** See the API documentation on Postman.
- **[Application Demo](https://www.postman.com/science-meteorologist-84254413/realtor-app-online/overview){:target="_blank"}:** Try out the application using Postman.

<br>

---

## Project Overview

**Brief Description:**  
The app is a REST API built in the Node.js framework Nest.js, which queries and updates a Postgres database. The app allows a user to make http requests to a set of endpoints which query available realty properties.
- The user can request a full list of available properties.
- The user can also filter the list of properties based on the various attributes of the properties, such as price, city, and property type.
- Users with a REALTOR role can create, update, and delete realty listings.
- Users can message the realtor for the property with inquiries.

**Technology Stack:**
- **Frontend:** directory reserved for building a Vue.js frontend
- **Backend:** Node.js, Express.js, Nest.js, Prisma ORM
- **Database:** Postgres
- **Other Tools:** JWT for authentication
  
---

## Features

**Core Features:**
- User authentication and authorization
- CRUD operations for primary resources.
- Data Validation and Exceptions

**Code & Architecture Features:**
- Modular architecture
- Automated unit tests
- Middleware: guards, interceptors, pipes.
- Dependency inversion by using decorators
- Separation of Concerns
- MVC design pattern: Model-View-Controller
  
---

## Architecture

**High-Level Architecture Diagram:**
- The backend application is part of a three-layer stack consisting of a web application frontend, the backend, and a Postgres database:
<br />  
<div  style="text-align: center;"><a href="/assets/tech-stack-diagram.png"><img src="/assets/tech-stack-diagram.png"  alt="Tech Stack Diagram" style="width: 480px; height: auto;" /></a></div><br>


---

## Usage Examples

**Using within Postman:**
<br>
<div  style="text-align: center;"><a href="/assets/postman-getHomes-screenshot.png"><img src="/assets/postman-getHomes-screenshot.png"  alt="Postman get homes screenshot" style="width: 600px; height: auto;" /></a></div>
<br>
The application may be tested using Postman. Above is an example of a request to get a listing of all homes.
<br>

**Using within JavaScript**

<div  style="text-align: center;"><a href="/assets/javascript-get-homes-screenshot.png"><img src="/assets/javascript-get-homes-screenshot.png"  alt="JavaScript get homes screenshot" style="width: 600px; height: auto;" /></a></div>
<br>
The application may be called from within a frontend app such as a Vue.js application using the JavaScript `axios` package.
<br>

**Using with command line**

`curl -X GET https://vue-nest-realtor-app-2.vercel.app/home`

Sample API response:

&nbsp;&nbsp;&nbsp;&nbsp;An array of objects, each with the properties of one realty listing


---

## Testing

Testing Strategy:
- Manual testing using Postman.
- Unit and integration testing using @nestjs/testing package.
- End-to-end testing using Supertest package for testing http requests and responses.

---

## Challenges & Solutions

Major challenges encountered during development:
- A major challenge was deploying the app to the cloud. Nest.js was not a pre-configured framework in the settings for Vercel.

Solution Implemented:
- Trial and error and research in order to set up a configuration for Nest.js running as a Node.js application.