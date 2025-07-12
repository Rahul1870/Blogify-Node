# Blogify-Node
📌 Project Overview
Blogify is a full-stack blogging platform where users can sign up, log in, and publish blog posts. It features secure authentication using JSON Web Tokens (JWT), user session handling, and CRUD functionality for blog content. The platform is built using Node.js, Express.js, and MongoDB, with server-rendered views using EJS.

🛠️ Tech Stack
Backend: Node.js, Express.js

Frontend: HTML, CSS, EJS (Templating Engine)

Database: MongoDB with Mongoose ODM

Authentication: JWT (JSON Web Token), bcrypt for password hashing

Others: dotenv, express-validator, cookie-parser, method-override

🚀 Features
🔐 User Authentication

Secure signup and login system with JWT

Passwords hashed using bcrypt

Protected routes for authenticated users only

📝 Blog Management

Create, read, update, and delete (CRUD) blog posts

Rich text blog entries with titles and body content

Timestamped posts with sorting

📄 User Dashboard

View and manage your own blog posts

Edit or delete posts you've authored

🌐 Public Blog Feed

Read all blogs posted by different users

📂 Project Structure
bash
Copy
Edit
Blogify/
├── public/               # Static assets (CSS, images)
├── routes/               # Route files for blogs and auth
├── models/               # Mongoose schemas (User, Blog)
├── views/                # EJS view templates
├── middlewares/          # Auth middleware
├── .env                  # Environment variables
├── app.js                # Entry point (Express app)
└── package.json
⚙️ Installation and Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/Rahul1870/Blogify-App.git
cd Blogify-App
Install dependencies

bash
Copy
Edit
npm install
Set up MongoDB

Create a database on MongoDB Atlas or use local MongoDB.

Add your MongoDB URI in the .env file:

ini
Copy
Edit
MONGODB_URI=mongodb://localhost:27017/blogify
JWT_SECRET=your_jwt_secret_key
PORT=8006
Run the server

bash
Copy
Edit
npm start
Visit in browser

arduino
Copy
Edit
http://localhost:8006
🧪 Sample Credentials
You can use the signup form to create new accounts.

📸 Screenshots (Optional)
Add UI screenshots here (e.g., home page, dashboard, post editor).

📈 Future Enhancements
Add WYSIWYG rich text editor (e.g., Quill.js)

Role-based admin panel for managing all blogs

Comment and like functionality

Deploy to Vercel/Render with MongoDB Atlas

🙋‍♂️ Author
Rahul Kumar
Final Year B.Tech – CSE
Ambalika Institute of Management and Technology
