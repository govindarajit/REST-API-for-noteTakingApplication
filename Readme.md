# REST API Note taking Application

Build a Restful CRUD API for a Note taking application using Node.js, Express and MongoDB.

## Steps to Setup

Testing our APIs
Let’s now test all the APIs one by one using postman.
Creating a new Note using POST /notes API

![Alt text]( C:\Users\HP\Music\ReactJS\REST-API-for-noteTakingApplication\config\Output\POST.png?raw=true "Title")


Retrieving all Notes using GET /notes API
![Alt text]( C:\Users\HP\Music\ReactJS\REST-API-for-noteTakingApplication\config\Output\GET.png?raw=true "Title")

Retrieving a single Note using GET /notes/:noteId API
![Alt text]( C:\Users\HP\Music\ReactJS\REST-API-for-noteTakingApplication\config\Output\GET-Specific-ID.png?raw=true "Title")

Updating a Note using PUT /notes/:noteId API
![Alt text]( C:\Users\HP\Music\ReactJS\REST-API-for-noteTakingApplication\config\Output\PUT.png?raw=true "Title")

Deleting a Note using DELETE /notes/:noteId API
![Alt text]( C:\Users\HP\Music\ReactJS\REST-API-for-noteTakingApplication\config\Output\delete.png?raw=true "Title")


1. Install dependencies

```bash
npm install
```

2. Run Server

```bash
node server.js
```
You can browse the apis at <http://localhost:3000>

