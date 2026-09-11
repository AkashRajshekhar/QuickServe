🛠️ Local Service Marketplace

A hyperlocal service booking platform that connects users with trusted local professionals such as plumbers, electricians, beauticians, and other service providers.

The platform enables users to discover nearby professionals, book services, track bookings in real time, provide ratings and reviews, and make secure online payments.

🚀 Features
✅ User & Professional Authentication — JWT-based authentication with OTP verification.
📍 Location-Based Service Search — Find nearby professionals using Google Maps API.
📅 Booking Management — Schedule, cancel, and manage service bookings.
🚚 Real-Time Booking Tracking — Track the status of ongoing service requests.
⭐ Ratings & Reviews — Leave 5-star ratings and feedback for professionals.
💳 Secure Payments — Integration with Razorpay / Stripe for online payments.
🛡️ Admin Dashboard — Manage users, professionals, services, and bookings.
👨‍🔧 Professional Management — Professionals can manage their services and bookings.
🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
Backend
Node.js
Express.js
MongoDB
Authentication & Security
JWT
Bcrypt
OTP Verification
APIs & Services
Google Maps API
Razorpay / Stripe
Deployment
Vercel — Frontend
Render — Backend
📁 Project Structure
local-service-marketplace/
├── backend/              # Node.js & Express APIs
├── frontend/             # React.js frontend
├── README.md             # Project documentation
└── LICENSE               # License

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/AkashRajshekhar/QuickServe.git

2. Navigate to the Project
cd QuickServe

3. Install Backend Dependencies
cd backend
npm install

4. Install Frontend Dependencies
cd ../frontend
npm install

🔐 Environment Variables

Create a .env file inside the backend directory and add the required environment variables.

Example:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret


Never commit your .env file or expose API keys and secrets publicly.

▶️ Running the Application
Backend

Open a terminal in the backend directory:

npm start

Frontend

Open another terminal in the frontend directory:

npm run dev


The frontend will run using the development server, while the backend will run on the configured API port.

🌟 Core Workflow
User
  ↓
Search Nearby Services
  ↓
Select Professional
  ↓
Book Service
  ↓
Make Payment
  ↓
Professional Accepts Booking
  ↓
Track Service Status
  ↓
Service Completed
  ↓
Rate & Review

👨‍💻 Project Goal

The goal of Local Service Marketplace is to make it easier for users to find reliable local professionals while providing service providers with a platform to manage their services, bookings, customers, and earnings.

📄 License

This project is licensed under the terms of the included LICENSE file.
