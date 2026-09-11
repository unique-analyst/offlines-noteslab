# Offline Notes Lab

A beginner Progressive Web App (PWA) for creating and storing notes with offline-first functionality.

Node.js Version

Node.js: "v24.20.0"

## Run Locally

Install the project dependencies:

npm install

Start the development server:

npm run dev

Open the local URL displayed in the terminal.

## Verify the Build

Run:

npm run check
npm run build
npm run preview

Deployed Application

https://unique-analyst.github.io/offlines-noteslab/

## PWA Test

1. Open the application using the preview URL.
2. Inspect the manifest using the browser Developer Tools.
3. Confirm that the service worker is registered and activated.
4. Switch the Network setting to Offline.
5. Reload the page.
6. Create a note while offline.
7. Confirm that the application remains available and the note can be created/stored while offline.
