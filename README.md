🎓 Alumni Networking Platform
📌 Overview
The Alumni Networking Platform is a SaaS-based web application that connects students with alumni for career guidance, networking, and mentorship. Key features include:
✅ Real-time chat
✅ Event management & scheduling
✅ Knowledge sharing & career guidance
✅ AI-powered chatbot for career assistance

🚀 Features
🔹 User Authentication
✔ Separate Student and Alumni logins
✔ Secure authentication using JWT & Multi-Factor Authentication (MFA)

🔹 Chat System
✔ Real-time messaging using WebSockets
✔ Career-based alumni search to find relevant mentors
✔ No video calls inside chat for privacy

🔹 Events & Scheduling
✔ Alumni-hosted career guidance sessions & webinars
✔ Students receive notifications & RSVP options
✔ Scheduled Video Calls: Students request a call, alumni approve & schedule

🔹 Knowledge Hub
✔ Alumni post industry insights & learning resources
✔ Students can browse blogs, articles, and career guides

🔹 Alumni Recognition
✔ Badging system & leaderboard for top contributors
✔ Colleges can offer rewards for active alumni engagement

🔹 AI-Powered Chatbot
✔ Integrated Gemini API chatbot for career advice
✔ Floating chatbot window for easy access

🛠 Tech Stack
Component	Technology
Frontend	React.js, Tailwind CSS
Backend	Node.js (Express.js)
Database	MongoDB / PostgreSQL
Authentication	JWT, Multi-Factor Authentication
Hosting	Vercel (Frontend), Render/Railway (Backend)
🔧 Installation & Setup
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/Niks-TheCoder/Alumni-connect.git
cd Alumni-connect
2️⃣ Install Dependencies
sh
Copy
Edit
npm install  # Install backend dependencies
cd frontend && npm install  # Install frontend dependencies (if using React)
3️⃣ Configure Environment Variables
Create a .env file in the backend folder:

ini
Copy
Edit
MONGODB_URI=your_database_url
JWT_SECRET=your_secret_key
4️⃣ Run the Application
For Backend:
sh
Copy
Edit
npm start
For Frontend (React):
sh
Copy
Edit
npm run dev
🚀 Deployment
Component	Deployment Service
Frontend	Vercel or Netlify
Backend	Render or Railway
📜 License
This project is open-source. Feel free to modify, distribute, and contribute.

🔥 Future Enhancements
✅ LinkedIn Integration
✅ Mobile App (Flutter)
✅ AI Resume Review System

📢 Contributions are welcome! Fork the repo, make changes, and submit a pull request. 😊

