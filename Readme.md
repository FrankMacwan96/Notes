# Notes Application

Build a Restful CRUD API for a simple Note-Taking application using Node.js, Express and MongoDB.

## Steps to Setup

1. Install dependencies

```bash
npm install
```

2. Run Server

```bash
node server.js
```

3. Routes / API Paths:

```bash
1. Create a note

POST /notes
Payload : { title: " ", content: " " }

2. Retrieve all note

GET /notes

3. Retrieve a single note

GET /notes/:noteID

Where noteID is the ID of note your are looking for

4. Update a note

POST /notes/noteID
Payload : { title: "updated title" ,  content : "updated title" }

5. Delete a note

DELETE /notes/noteID

```

You can browse the apis at <http://localhost:3000>
