# 🔒 PassOp
A secure and efficient password manager that allows users to store, manage, and retrieve their passwords safely. Built with React, Node.js, Express, and MongoDB, PassOp ensures strong encryption and user authentication to keep your credentials protected.

# 🌟 Features
1. **Secure Storage –** Encrypts passwords before storing them in the database.
2. **User Authentication –** Login/signup with JWT-based authentication.
3. **Add & Manage Passwords –** Store and retrieve passwords easily.
4. **Search Functionality –** Quickly find stored passwords.
5. **Strong Encryption –** Uses hashing and encryption techniques for security.
6. **Copy to Clipboard –** Copy stored credentials with a single click.

# 🛠️ Tech Stack

| 🌐 Technology     | 📖 Documentation                                   |
|-------------------|----------------------------------------------------|
| **React**         | [React Docs](https://react.dev/)                   |
| **Node.js**       | [Node.js Docs](https://nodejs.org/)                |
| **Express**       | [Express Docs](https://expressjs.com/)             |
| **MongoDB**       | [MongoDB Docs](https://www.mongodb.com/docs/)      |


# 🚀 Getting Started

1️⃣ Clone the Repository
<pre> <code> git clone https://github.com/Manan-Joshi750/Password_Manager.git cd Password_Manager </code> </pre>

2️⃣ Install Dependencies
In both the passop, passop-mongo, and backend folders, install the required dependencies.

<pre> <code> npm install cd frontend && npm install cd backend && npm install cd passop-mongo && npm install </code> </pre>

3️⃣ Configure .env File
Go to the backend/passop-mongo folder.

Create a .env file with the following settings :

<pre>
<code>
NODE_ENV=development/production  
PORT=5000 or 3000  
MONGO_URI=<Your MongoDB URI>  
DB_NAME=<Your Database Name> 
JWT_SECRET=<Your JWT Secret>  
</code>
</pre>
  
4️⃣ Start the Development Server
Run the application using one of the following :

<pre> <code> npm run dev # or yarn dev # or pnpm dev # or bun dev </code> </pre>

5️⃣ Open in Browser
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
