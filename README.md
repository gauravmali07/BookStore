**Book Store CRUD App (MERN Stack)**

A modern full-stack Book Store Management application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The application allows users to manage books through complete CRUD operations with a responsive and user-friendly interface.

**Features**
📖 View all books
➕ Add new books
✏️ Update existing books
🗑️ Delete books
🔍 View detailed book information
🌐 RESTful API integration
💾 MongoDB Atlas database connectivity
🎨 Responsive UI with Tailwind CSS
⚡ Fast frontend powered by Vite
🔔 User notifications using Notistack

**Tech Stack**
Frontend
React.js
Vite
Tailwind CSS
Axios
React Router DOM
React Icons
Notistack
Node.js
Express.js
Mongoose
CORS
Database
MongoDB Atlas

**📂 Project Structure**
book-store-crud-mern/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── config.js
│   ├── index.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md

**Installation**
1️⃣ Clone Repository
git clone https://github.com/your-username/book-store-crud-mern.git
cd book-store-crud-mern
2️⃣ Setup Backend
cd backend
npm install

Create a .env file:

PORT=5555
MONGODB_URI=your_mongodb_atlas_connection_string

Start backend server:

npm run dev
3️⃣ Setup Frontend

Open a new terminal:

cd frontend
npm install
npm run dev

Frontend runs on:

http://localhost:5173

Backend runs on:

http://localhost:5555

**API Endpoints**
Method	Endpoint	Description
GET	/books	Fetch all books
GET	/books/:id	Fetch single book
POST	/books	Create new book
PUT	/books/:id	Update book
DELETE	/books/:id	Delete book

**Future Enhancements**
User Authentication
JWT Authorization
Search & Filter Books
Pagination
Book Categories
Dark Mode
Image Upload Support
Deployment on Render/Vercel

**Author**

Gaurav Mali

MCA Student | MERN Stack Developer | Full Stack Enthusiast

**Connect With Me**
LinkedIn: https://www.linkedin.com/in/gaurav-mali78/

**Support**
If you found this project useful, please consider giving it a ⭐ on GitHub.
Built with ❤️ using MongoDB, Express.js, React.js, Node.js, and Tailwind CSS.
