🏋️‍♂️ Fitness App
📌 Project Description
Fitness App is a web-based application designed to help users track their fitness activities and monitor their health goals. The application provides functionalities such as logging workouts, tracking progress, and managing personal fitness data. Built with a focus on user experience and responsiveness, the app ensures seamless interaction across various devices.

🚀 Features
User Authentication: Secure login and registration system to protect user data.

Workout Logging: Users can record their daily workouts, including exercise types, durations, and calories burned.

Progress Tracking: Visual representations of user progress over time to motivate and inform.

Responsive Design: Optimized for desktops, tablets, and mobile devices.

🛠️ Tech Stack
Frontend: React.js, HTML5, CSS3

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JSON Web Tokens (JWT)

📁 Folder Structure
graphql
Copy
Edit
Fitness_App/
├── backend/             # Express.js backend with API routes
├── frontend/            # React.js frontend application
├── .gitignore
├── README.md
└── package.json
⚙️ Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v14 or higher)

npm (v6 or higher)

MongoDB (local or cloud instance)

Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/satyam17gautam/Fitness_App.git
cd Fitness_App
Set Up the Backend

bash
Copy
Edit
cd backend
npm install
Create a .env file in the backend directory and add your MongoDB connection string:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
Start the backend server:

bash
Copy
Edit
npm start
Set Up the Frontend

Open a new terminal window:

bash
Copy
Edit
cd frontend
npm install
npm start
The application will be accessible at http://localhost:3000.

🧪 Usage
User Registration & Login

Navigate to http://localhost:3000.

Register a new account or log in with existing credentials.

Logging Workouts

After logging in, access the workout logging section.

Input details such as exercise type, duration, and calories burned.

Submit to save the workout entry.

Viewing Progress

Access the progress section to view charts and summaries of your fitness activities over time.

📸 Screenshots
<img width="576" alt="Screenshot 2025-04-30 at 11 16 57 PM" src="https://github.com/user-attachments/assets/a8dcee54-af37-44ed-a746-2995d70b478e" />


Dashboard

Workout Logging

📝 License
This project is licensed under the MIT License.

🙏 Acknowledgements
React.js

Node.js

Express.js

MongoDB
