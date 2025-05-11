Mini CRM App 🚀
MERN Stack | React • Node.js • Express • MongoDB

A sleek, scalable Customer Relationship Management app built with the MERN stack.

🔥 Features
Customer & Order Data Ingestion

Audience Builder with custom rules (AND/OR logic)

Campaign Manager to send & track personalized messages

Google Auth via Passport.js

Performance Boost with optional RabbitMQ/Kafka for pub/sub + batch DB operations

🛠️ Tech Stack
Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

Auth: Google (Passport.js)

Optional: RabbitMQ / Apache Kafka

🚀 Getting Started
bash
Copy
Edit
# Clone the repo
git clone https://github.com/kumarshivams/xeno-mini-crm.git

# Install server
cd mini-crm-app/server && npm install

# Install client
cd ../client && npm install
📁 Create a .env in /server:
ini
Copy
Edit
MONGODB_URI=your_mongodb_uri
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_secret
SESSION_SECRET=your_session_secret
▶️ Run the App
bash
Copy
Edit
# Start server
cd ../server && npm start

# Start client
cd ../client && npm start
Visit http://localhost:3000 — Login with Google and start managing your audience & campaigns!
