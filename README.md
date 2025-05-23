# How to setup?

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

# Architecture

1. Backend

  Main file on server part, main.ts, is located in src folder. 
  Responsibilities of other folders in src: 
    * Auth and openai-requests: auth and ai routes
    * db: connection to Mongo database
    * validation: responsible for validation of incoming data
    * middlewares: have middleware that validates access token

2. Frontend 

  Main file is main.tsx, that is located in src folder too.
  Responsibilities of other folders and files in src: 
    * App.tsx: responsible for route management
    * index.css: imports tailwind, which i use in my project to add styles
    * pages: contains all pages
    * components: contains other small components
    * contexts: contains context providers
    * types: contains exported types
    * api: responsible for requests to server

# AI API 

I chose OpenAI. That's an easy and effective choice for simple tasks like that.

# Plans 

To improve my project, at first, i'd like to add better styles. Additionally i want to add  user profile page and abilities to have avatar and change password.  