# Pocket-Ride: Ride Booking Web App (MERN Stack)

This is a full-stack web application for booking rides, built using the MERN (MongoDB, Express.js, React, Node.js) stack.

## Features

*   **User Authentication:** Secure user registration and login with password hashing.
*   **Ride Booking:** Users can request rides by specifying pickup and drop-off locations.
*   **Real-time Tracking (Future):** Planned implementation of real-time tracking of drivers on a map.
*   **Payment Integration (Future):** Planned integration with a payment gateway for seamless transactions.
*   **Driver Management (Future):** Features for driver registration, verification, and ride management.
*   **Admin Dashboard (Future):** An admin panel to manage users, rides, and other aspects of the application.

## Technologies Used

*   **Frontend:** React, Redux (for state management - optional but recommended), HTML, CSS, JavaScript
*   **Backend:** Node.js, Express.js
*   **Database:** MongoDB
*   **Other:** JWT (JSON Web Tokens) for authentication, potentially Socket.IO for real-time features, Mapbox/Google Maps API for maps.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Node.js (LTS version recommended)
*   npm or yarn
*   MongoDB (local installation or MongoDB Atlas)

### Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd <your-repo-name>
    ```

3.  Install server dependencies:

    ```bash
    cd server
    npm install  # or yarn install
    ```

4.  Install client dependencies:

    ```bash
    cd client
    npm install  # or yarn install
    ```

5.  Create a `.env` file in the `server` directory and add the following environment variables:

    ```.env
    PORT=5000 # or any other port
    MONGODB_URI=<your-mongodb-connection-string>
    JWT_SECRET=<your-secret-key> # Generate a strong secret key
    ```

6.  Start the development servers:

    ```bash
    # In separate terminal windows:
    # Server:
    cd server
    npm run dev # or yarn dev

    # Client:
    cd client
    npm start # or yarn start
    ```

The application should now be running at `http://localhost:3000` (client) and the server at `http://localhost:5000` (or the port you specified).

## Project Structure
