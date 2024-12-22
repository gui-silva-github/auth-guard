# AuthGuard  

AuthGuard is a secure authentication system built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). It provides a robust login and sign-up functionality using JSON Web Tokens (JWT) for authentication and cookies for secure token management.  

<hr>

## Recursos

- **JWT-based Authentication:** Secure login and session management.  
- **Client-Server Architecture:** Clear separation of concerns with React.js handling the client-side and Express.js managing the server-side API.  
- **Secure API:** Middleware for token validation and request security.  
- **Responsive UI:** Built with React.js for a seamless user experience.  

<hr>

## Tecnologias

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

<hr>

## Instalação  

### Pré-requisitos
Ensure you have the following installed:  
- [Node.js](https://nodejs.org/)

<hr>

### Instruções de inicialização

1. Clone the repository
   ```bash
   git clone https://github.com/gui-silva-github/auth-guard.git
   cd auth-guard

2. Install dependencies

   For the client:

   <ul>
     <li>cd client</li>
     <li>npm install</li>
   </ul>
  
    For the server:

    <ul>
     <li>cd server</li>
     <li>npm install</li>
   </ul>

3. Configure Environment Variables

In the server directory, create a .env file with the following content:

<ul>
  <li>MONGODB_URL='...'</li>
  <li>JWT_SECRET='secret#text'</li>
  <li>NODE_ENV='development'</li>
  <li>SMTP_USER="..."</li>
  <li>SMTP_PASS="..."</li>
  <li>SENDER_EMAIL="guilhermeviniciusbispodasilva@gmail.com"</li>
</ul>

4. Running the Project

This project requires two terminals to run the client and server simultaneously.

Open a terminal and navigate to the client folder:

<ul>
  <li>cd client</li>
  <li>npm run dev</li>
</ul>

Open a second terminal and navigate to the server folder:

<ul>
  <li>cd server</li>
  <li>npm run server</li>
</ul>

The API server will run on http://localhost:4000.

