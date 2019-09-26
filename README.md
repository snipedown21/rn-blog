## Available Scripts
This project was created using expo and react native, json-server for API serving and ngrok for publishing the APIs to the internet.
Once in the project directory, you will require to run the following set of commands on 3 different terminals:

Terminal tab 1
---------------
### `cd blog`
### `npm install`
### `npm start`

Terminal tab 2
---------------
### `cd ../jsonServer`
### `npm run db`

Terminal tab 3
---------------
### `npm run tunnel`

Make sure to have Xcode installed, expo-cli to be installed globally and if you're on windows, you will need android studio.
The ngrok base URL will have to updated in the jsonServer axios instance creator file, with the new ngrok URL that is visible on your terminal.

The application should normally reload if you make edits. If it does not reload, please try command + R on Mac / Ctrl + R on windows.<br>
Happy Coding!!!

