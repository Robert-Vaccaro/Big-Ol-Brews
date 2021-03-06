# Big Ol' Brews

The back-end is built with **Node.js** using a **Postgres** database.

See it live [here](https://lit-spire-67447.herokuapp.com/).

## Local Installation

Follow the instructions below if you prefer to install the application on your local machine:

1. Install the latest version of [Node.js](https://nodejs.org). This application requires Node.js 4+.

1. Install [Postgres](http://www.postgresql.org/) locally 

1. Start Postgres and create a database called **belgianbeers**.

1. Clone [this repository](https://github.com/Robert-Vaccaro/Big-Ol-Brews).

1. Navigate to the directory the app is in and install the project dependencies:

    ```
    npm install
    ```

1. Open **server/config.js** and make sure the **databaseURL** matches your configuration (use your user name)

1. Type the following command to build the client application:

    ```
    npm run webpack
    ```

1. Type the following command to start the server:
    
    ```
    npm start
    ```
    
    The database is automatically populated
    
1. Open a browser and access [http://localhost:5000](http://localhost:5000)
