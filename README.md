# Cinemania

Cinemania is a modern movie browsing web application built with Angular and Vite.
The application allows users to register and log in, browse and filter movies, explore detailed movie information, and simulate a cinema reservation experience. 
It integrates with an external REST API for movie data, while screenings, reservations and reviews are implemented using mocked data to simulate real-world backend behavior.


## Features

- Browse and search movies by various criteria
- View detailed movie information
- Make ticket reservations
- Manage user profile
- Track reservation history
- Rate watched movies


## Tech Stack

- Angular
- Vite
- TypeScript
- Axios
- REST API integration
- Local Storage for authentication
- Mocked data for reservation and review simulation


## API

Movie data is fetched from:
https://movie.pequla.com/api

Screenings, reservations and reviews are simulated on the client side.


## Run Locally

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm start
```

Application runs on:
http://localhost:4200


## Project Purpose

This project demonstrates frontend architecture, API integration, client-side state management, user handling, and simulation of a reservation system without a backend implementation.

## Possible Future Improvements

- Backend integration for real reservation persistence
- Payment gateway integration
- JWT-based authentication with backend validation
- Role-based authorization
