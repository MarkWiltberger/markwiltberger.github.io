---
title: Realtor App Backend Project
layout: page
---
---

<br />  
<div  style="text-align: center;"><img src="/assets/realtor-app-concept.png"  alt="Realtor App concept" style="width: 480px; height: auto;"></div>

## Quick Links

- **GitHub Repository:** See the code at the GitHub repository [**here**](https://github.com/MarkWiltberger/vue-nest-web-app__realtor-app){:target="_blank"}.


- **Application Demo:** Try out the application using Postman [**here**](https://www.postman.com/science-meteorologist-84254413/realtor-app-online/overview){:target="_blank"}.


- **Application Documentation:** See the API documentation on Postman [**here**](https://www.postman.com/science-meteorologist-84254413/realtor-app-online/documentation/gu1pgpa/realtor-app-online){:target="_blank"}.

<br>

---

## Project Overview

**Brief Description:**  
The app allows a user to make http requests for a set of endpoints related to querying available realty properties.
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
- CRUD operations for primary resources
  
---

## Architecture

**High-Level Architecture Diagram:**
- Diagram of the frontend, backend, and database layers
<br />  
<div  style="text-align: center;"><a href="/assets/tech-stack-diagram.png"><img src="/assets/tech-stack-diagram.png"  alt="Tech Stack Diagram" style="width: 480px; height: auto;" /></a></div>


---

## Using/Operation

**Using within Postman:**
<br>
<div  style="text-align: center;"><a href="/assets/postman-getHomes-screenshot.png"><img src="/assets/postman-getHomes-screenshot.png"  alt="Postman get homes screenshot" style="width: 600px; height: auto;" /></a></div>
<br>
The application may be tested using Postman. Above is an example of a request to get a listing of all homes.
<br>

**Using within JavaScript**

<div  style="text-align: center;"><a href="/assets/javascript-get-homes-screenshot.png"><img src="/assets/javascript-get-homes-screenshot.png"  alt="JavaScript get homes screenshot" style="width: 600px; height: auto;" /></a></div>
<br>

