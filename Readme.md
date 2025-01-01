# YouMatter
## A mental health chat assistant

#### Deploy Link : [YouMatter](https://youmatter-1.vercel.app/)

YouMatter is a mental health **AI** powered chat assistant which guides and helps you to improve your mental health.
YouMatter website provides a user friendly UI to learn about mental health.

## Features

- AI chat assistant to take guidance about mental health
- Analyse your mental health over the period of time
- Get Indication about your mental health condition with graphical visualisation
- Editor's compiled articles to read and educate about mental health problems
- Get Email time to time with suggestion to improve your mental health



## Tech

#### System Design
YouMatter application runs on 3 server
- Frontend
- Backend
- WebSocket Server
  
![sysyou](https://github.com/nikhilgb0110/Youmatter/assets/126336384/f6a75541-20f1-435a-bb6d-023b747288ed)


#### Tech stack
- Frontend
  - React JS
  - Tailwind
- Backend
  - Node Js
  - Express Js
  - Gemini (Gen AI)
  - Web Sockets
  - Node Mailer
- Tools
  - Vercel
  - Render
  - Mongo DB
  - Firebase

## How to Setup
- clone the project using `git clone <project_url>`
- create a new firebase project and obtain key as per `Backend/.env.example`
- create a new gemini key as per `Backend/.env.example`
- add `.env` in `Backend, Frontend, WebSockerServer` folders as per `.env.example` in respective folders.
- open each of 3 folders in terminal, and run `npm i`
- goto `Backend/` in terminal and run `npm run dev`
- goto `Frontend/` in terminal and run `npm start`
- goto `WebSockerServer` in terminal and run `node index.js`
- goto browser and open the url where `Frontend` is running ...
