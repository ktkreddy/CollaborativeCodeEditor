# Sync Code: Realtime Collaborative Code Editor

## Introduction
Are you tired of sending code snippets back and forth, struggling to debug and collaborate with your team? Look no further! **Sync Code** is here to revolutionize the way you code together. This powerful and intuitive collaborative code editor is designed to empower developers, designers, and teams to work seamlessly in real-time, regardless of their location. With **Sync Code**, you can code together, debug together, and ship faster, together.

## Features
- Multiple users can join a room and edit code together
- Changes are reflected in real time
- Copy button to copy the room id to clipboard
- Leave button to leave the room
- Supports syntax highlighting (currently only for JavaScript)
- Users can leave the room and rejoin later to continue editing
- Joining & leaving of users is also reflected in real time

## Tech Stack
- React.js
- Node.js
- Express.js
- Socket.io
- CodeMirror
- React-Toastify

## Run Locally
This project is not currently live on any server. But to use the demo version, follow the steps below:
- Clone this repository and cd into it
- Run `npm install` to install the dependencies
- To start the react app client run `yarn start` in one terminal
- To start the server run `yarn server:dev` in another terminal
- Go to `http://localhost:3000` to view the app
- To join as an another user open another browser or incognito tab and go to `http://localhost:3000`
- Enter the same room id to join the same room

Now both your editor will be synced and you can see the changes in real time. Try opening the same room in multiple tabs and see the changes.

**Note:** If you find any bugs, please let me know. I will try to fix it as soon as possible :) <br>
In case you want to fix it yourself, feel free to make a pull request.

## Future Scope 
- Add syntax highlighting for multiple languages
- Add support for multiple themes (currently using Dracula theme)

## Connect with me
- [LinkedIn](https://www.linkedin.com/in/tarunkrishnareddykolli/)