## How to setup?

1. Backend setup:
  1.1 Change directory to /server folder:
    cd ./server

  1.2 Install packages: 
    npm i / yarn

  1.3 Add environment variables from .env.example file to .env

  1.4 To run server:
    npm run start / yarn start



2. Frontend setup 
  2.1 Change directory to /client folder:
    cd ./client (or cd ../client if you are in /server folder)

  2.2 Install packages: 
    npm i / yarn

  2.3 To run:
    npm run preview / yarn preview

## Architecture

1. Backend

  Main file on server part, main.ts, is located in src folder. 
  Responsibilities of other folders in src: 

    1.1 Auth and openai-requests: auth and ai routes

    1.2 db: connection to Mongo database

    1.3 validation: responsible for validation of incoming data

    1.4 middlewares: have middleware that validates access token

2. Frontend 

  Main file is main.tsx, that is located in src folder too.
  Responsibilities of other folders and files in src: 

    2.1 App.tsx: responsible for route management

    2.2 index.css: imports tailwind, which i use in my project to add styles

    2.3 pages: contains all pages

    2.4 components: contains other small components

    2.5 contexts: contains context providers

    2.6 types: contains exported types
    
    2.7 api: responsible for requests to server

## AI API 

I chose OpenAI. That's an easy and effective choice for simple tasks like that.

## Plans 

To improve my project, at first, i'd like to add better styles. Additionally i want to add  user profile page and abilities to have avatar and change password.  



# Preliminary Questions

  1. It was fullstack project. I used Node.js with Express.js on backend and React on frontend. I used lots of libraries such as axios, redux with redux-toolkit and so on. Additionally i used MongoDB as database, Cloudinary as storage for images.

  2. To be honest i have no experience in python.

  3. Yes

  4. No experience

  5. No, don't know about this protocol.

  6. 