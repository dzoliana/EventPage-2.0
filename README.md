# Event Page 2.0

## Project summary

Event page is a web application that represents an exercise in learning Tanstack Query.
Tanstack Query is a library that makes it easier to send HTTP requests and maintain synchronization between frontend user interface and backend data.

<h4 align="center">Home page</h4>

<p align="center">
 <img src="/src/assets/Home.png" alt="drawing" width="500"/>
</p>

<h4 align="center">Add New Event</h4>

<p align="center">
 <img src="/src/assets/AddEvent.png" alt="drawing" width="500"/>
</p>

<h4 align="center">Event Details</h4>

<p align="center">
 <img src="/src/assets/EventDetails.png" alt="drawing" width="500"/>
</p>

<h4 align="center">Delete Event</h4>

<p align="center">
 <img src="/src/assets/DeleteEvent.png" alt="drawing" width="500"/>
</p>

<h4 align="center">Search Events</h4>

<p align="center">
 <img src="/src/assets/SearchEvents.png" alt="drawing" width="500"/>
</p>

## Getting started

_React + Vite_

This project actually contains two projects:

- A React application (i.e., the frontend SPA)
- A dummy backend API to which the React app can "talk" (to send + fetch data)

You must run "npm install" in both project folders.

Thereafter, you can start the dummy backend API server via "npm start" (inside the "backend" folder).
The React app dev server is started via "npm run dev".

You MUST have both servers (backend + frontend) up and running for the projects to work.

The dummy backend API does not use any external database - instead the dummy data is saved to an "events.json" file inside the project folder.
