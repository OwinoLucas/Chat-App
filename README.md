# Realtime Chat
A realtime, scalable chat app that supports group chats, 1-on-1 chats, realtime messaging, image and file support, read receipts and more!

App uses passwordless authentication. User simply enters their username and the authenticate API creates and/or logs in the user depending on if the user was already created or if he/she is a new user.

### Screenshots
#### Home Page
![Screenshot from 2023-08-01 14-49-17](https://github.com/OwinoLucas/Chat-App/assets/60548928/7e382e5b-8abf-4ce6-ad5f-18ea0c1536d1)

#### Chat Section
![Screenshot from 2023-08-01 14-49-05](https://github.com/OwinoLucas/Chat-App/assets/60548928/1a2eaa18-c18f-44f6-88b8-0428ff9d393b)

## Installation

#### Tech Stack
- [Node.js]
- [Reactjs]

#### Backend Installations
Clone application 
```sh
cd /app/backend
npm init
npm install

npm run start
```

#### To test API
```sh
Navigate to request.rest
Run send request
```

#### Frontend Installations

```sh
npm create vite@latest
✔ Project name: … frontend
✔ Select a framework: › React
✔ Select a variant: › JavaScript

npm install

npm run dev
```

## Usage
```sh
Web interface `http://localhost:3001` for backend

Web interface `http://localhost:5173/` for frontend

```