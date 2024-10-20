# Notes

## Create Firebase project

register react native project

DO NOT share firebaseConfig

### env variables

create `.env` -> rename `app.js` as `app.config.js`

create folder `config`, create `firebase.js`



## firestorage db



## Creat Screens

create folder: `screens`

├── Chat.js
├── Home.js
├── Login.js
└── Signup.js







# Problems

1.   ERROR  TypeError: Cannot read property 'style' of undefined, js engine: hermes

   Sol: https://github.com/FaridSafi/react-native-gifted-chat expo install dependencies

2. Fail to configure env var

   Constants.manifest2.extra. -> `undefined`

   Sol: use manifest (deprecated)

   Then Error: TypeError: Cannot read property 'extra' of null, js engine: hermes

   In `app.config.js`: `extra` should be placed inside the expo 
