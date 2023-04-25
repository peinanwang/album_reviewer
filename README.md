<div align="center">
  <h1>Album Reviewer</h1>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white&style=for-the-badge" alt="React logo">
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node-dot-js&logoColor=white&style=for-the-badge" alt="Node.js logo">
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=for-the-badge" alt="MySQL logo">
  <img src="https://img.shields.io/badge/Spotify-1ED760?logo=spotify&logoColor=white&style=for-the-badge" alt="Spotify logo">
  <img src="https://img.shields.io/badge/Auth0-EB5424?logo=auth0&logoColor=white&style=for-the-badge" alt="Auth0 logo">
</div>

Welcome to Album Reviewer, a full-stack web application for reviewing albums from Spotify and sharing your ratings with other users. This repository contains the source code for the application, which is built using React for the frontend, Node.js for the backend API, and a MySQL database for storing album and user data. The application also uses the Spotify API for accessing album information and Auth0 for managing user registration, login, and authentication.

The Spotify Album Review App provides the following features:

* Review new albums from Spotify
* View album details and all reviews associated with the album
* Rate albums with a 1-5 star rating and leave comment (login needed)
* Edit and delete your own reviews as needed (login needed)
* Manage personal profile (login needed)

The app uses the following technologies:

* Frontend: React, Bootstrap
* Backend: Node.js, Express, MySQL, Prisma
* External API: Spotify API
* Authentication: Auth0

## Deployment
The application is already deployed and can be accessed at https://album-reviewer.vercel.app/home. The frontend is deployed on Vercel, the API is hosted on Google Cloud, and the database is hosted by PScale.

## Getting Started

To get started with the application, you'll need to do the following:

Clone this repository to your local machine using git clone.
Install the necessary dependencies by running npm install in both the client and server directories.
Create two .env files in the client and server directories, respectively, and populate them with the appropriate variables (see below).
Start the application by running npm start in both the client and server directories.
Environment Variables
The application requires several environment variables to be set in order to function properly. Here are the variables you'll need to set:

### Backend API .env Variables

* DATABASE_URL: The connection string for the MySQL database where album and user data is stored.
* SPOTIFY_CLIENT_ID: The client ID for the Spotify API, used to authenticate requests to the API.
* SPOTIFY_CLIENT_SECRET: The client secret for the Spotify API, used to authenticate requests to the API.
* AUTH0_DOMAIN: The domain for your Auth0 account, used to authenticate and authorize users.
* AUTH0_AUDIENCE: The audience for your Auth0 account, used to authenticate and authorize users.
* AUTH0_ISSUER: The issuer for your Auth0 account, used to authenticate and authorize users.

### Frontend .env Variables

* REACT_APP_API_URL: The URL for the backend API, used to make requests to the API.
* REACT_APP_AUTH0_DOMAIN: The domain for your Auth0 account, used to authenticate and authorize users.
* REACT_APP_AUTH0_CLIENT_ID: The client ID for your Auth0 account, used to authenticate and authorize users.
* REACT_APP_AUTH0_AUDIENCE: The audience for your Auth0 account, used to authenticate and authorize users.
* REACT_APP_JWT_NAMESPACE: The namespace for the JSON Web Tokens (JWTs) used to authenticate and authorize users.

## Contributing

If you'd like to contribute to the development of Album Reviewer, please follow these steps:

* Fork this repository to your own GitHub account.
* Clone the forked repository to your local machine.
* Make your changes and commit them to your local repository.
* Push your changes to your forked repository on GitHub.
* Submit a pull request to this repository.

## License

This project is licensed under the MIT License.
