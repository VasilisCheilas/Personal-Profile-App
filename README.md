# Build a Personal Profile App

A simple Express.js backend application that serves personal profile information through various HTTP GET routes. This project was built to fulfill a backend development certification project for freeCodeCamp.

## Features

* Runs an HTTP server on port `3000` using Express.
* Serves static text responses for basic routing.
* Serves structured JSON data for an API route.

## Installation

1. Open your terminal in the project directory (`build-a-personal-profile-app/`).
2. Install the required dependencies (Express.js):

```bash
   npm install express

```

## Usage

Start the server by running:

```bash
node server.js

```

The server will start listening on `http://localhost:3000`.

## API Endpoints

| Method | Route | Description | Response Type |
| --- | --- | --- | --- |
| `GET` | `/` | Homepage greeting | Text |
| `GET` | `/hobbies` | Lists the user's hobbies | Text |
| `GET` | `/skills` | Lists the user's technical skills | Text |
| `GET` | `/api/profile` | Returns full profile data | JSON |

**Example JSON Response (`/api/profile`):**

```json
{
  "name": "Camper Bot",
  "hobbies": ["cycling", "boating", "guitar"],
  "skills": ["JavaScript", "Node.js", "Express.js"]
}

```

## Author

**Vasilis Cheilas**
