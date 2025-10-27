Contacts Full-Stack Application (MERN)

A full-stack Contacts Management Application built using the MERN stack — MongoDB, Express.js, React.js, and Node.js.
This project allows users to manage their contact information (add, edit, delete, and view contacts) efficiently with a responsive front-end and secure back-end.

Project inspired and learned from Dipesh Malvia’s YouTube tutorials.

------------------------------------------------------------
Repository Structure
------------------------------------------------------------
contacts-fullstack/
│
├── contacts-backend/      # Backend (Node.js + Express + MongoDB)
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── config/
│
├── contacts-frontend/     # Frontend (React.js)
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md              # Project documentation

------------------------------------------------------------
Tech Stack
------------------------------------------------------------
Frontend:
- React.js
- Axios
- React Router DOM
- Tailwind CSS / Bootstrap (if used)

Backend:
- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- CORS, Dotenv

------------------------------------------------------------
Features
------------------------------------------------------------
- Add new contacts
- View all saved contacts
- Edit contact details
- Delete a contact
- RESTful API integration between front-end and back-end
- Responsive and clean UI

------------------------------------------------------------
Setup Instructions
------------------------------------------------------------
1. Clone the repository
   git clone https://github.com/your-username/contacts-fullstack.git
   cd contacts-fullstack

2. Setup Backend
   cd contacts-backend
   npm install

   Create a .env file inside contacts-backend with:
   PORT=5000
   MONGO_URI=your_mongodb_connection_string

   Run backend server:
   npm start

3. Setup Frontend
   cd ../contacts-frontend
   npm install
   npm start

   Frontend will typically run on http://localhost:3000
   Backend will run on http://localhost:5000

------------------------------------------------------------
Learning Source
------------------------------------------------------------
This project was created as part of learning from
Dipesh Malvia’s YouTube Channel (MERN Stack tutorials).

------------------------------------------------------------
Preview (Optional)
------------------------------------------------------------
Add screenshots or demo GIFs here to show how the app looks.

------------------------------------------------------------
Contributing
------------------------------------------------------------
Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

------------------------------------------------------------
License
------------------------------------------------------------
This project is open-source and available under the MIT License.

------------------------------------------------------------
If you found this project helpful, consider giving it a star!
