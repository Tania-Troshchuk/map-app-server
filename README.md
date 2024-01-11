## Map-app (backend)

## Tech Stack of implementation (backend):

- Server Environment: Node.js with Express
- Database: MongoDB
- Node version: 16.14.0

## Getting Started

To set up and run the app locally, follow these steps:

1. Clone this repository to your local machine:

    ```bash
    git clone this repo
    cd map-app-server
    ```

2. Create a new `.env` file in the `map-app-server` directory to store your environment variables:

    ```bash
    touch .env
    ```

    Open the `.env` file in a text editor and configure the necessary environment variables:

    ```env
    mongodbURL=key
    ```

    Save and close the `.env` file.

3. Install the required Node.js packages for the server:

    ```bash
    npm install
    ```

4. Start the server in development mode:

    ```bash
    npm run dev
    ```

    In the console, you should see the message "Successful connected to mongoDB 🌿" and "App is listening on port: 3000 🚀".

