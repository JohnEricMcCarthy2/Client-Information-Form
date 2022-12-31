# Google Sheets + Node.js/Express

Simple Node.js/Express app (with EJS frontend) that integrates with Google Sheets to read/update data. This application demos the functionality with a simple "Video Request" app that uses a form to add a new row to a Google Sheet.

# Tutorial

Watch the first 5 minutes of this [video](https://www.youtube.com/watch?v=PFJNJQCU_lo]) to learn how to set up the google api and necessary service account.

# Setup

You need to add a file to the root of this project called "credentials.json" and add your spreadsheet's id to an env file.

Then run npm install to install dependencies.

# Run locally (port 1337)

Run `nodemon index.js` or `npm start`