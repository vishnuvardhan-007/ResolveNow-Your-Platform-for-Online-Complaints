ResolveNow

Your Platform for Online Complaints
Built with the MERN stack to simplify how users register, track and manage complaints — with transparency, efficiency and ease.

🚀 Overview

ResolveNow is a full-stack web application designed to streamline the grievance redressal process. Whether you're a user filing a complaint, an agent responding, or an admin overseeing the flow, ResolveNow provides an intuitive, end-to-end solution:

Users can register complaints, monitor status, receive notifications and interact with agents.

Support agents can manage complaints, update statuses, log responses and escalate where necessary.

Admins gain centralized control over users, agents, complaints, and system settings.

Built using MongoDB, Express.js, React.js and Node.js (the MERN stack) for modern, scalable web architecture.

📌 Why ResolveNow?

Transparent workflow – Everyone involved can see complaint progress in real time.

User-friendly interface – Clean React UI + Axios for seamless front-end/back-end interaction.

Scalable architecture – MongoDB for flexible storage, Express + Node for API logic, React for dynamic UI.

Notifications & tracking – Keeps all stakeholders in the loop.

Separation of concerns – Clean client-server split ensures maintainability and extensibility.

🎯 Key Features

Complaint Registration – Users submit complaints with details, category, attachments.

Complaint Tracking – Live view of status changes, resolution history.

User-Agent Interaction – Message/chat (or comment) support between complainant and agent.

Admin Dashboard – Overview of complaints, users, agents, analytics.

Secure Authentication & Authorization – Role-based access control: users, agents, admins.

Responsive Design – Built for desktop and mobile using Material-UI, Bootstrap.

Notifications – Email or in-app alerts when a status changes or a message arrives.

🧩 Tech Stack
Layer	Technology
Database	MongoDB
Backend	Node.js + Express.js
Frontend	React.js
HTTP/Client	Axios
UI Frameworks	Material UI, Bootstrap
Architecture	Client-Server (REST API)
🗂️ Project Structure (High-Level)
/client              # React front-end  
  /public  
  /src  
    /components  
    /pages  
    /utils  
    ...
/server              # Node/Express back-end  
  /config  
  /controllers  
  /models  
  /routes  
  /middlewares  
  ...
README.md

🛠️ Setup & Installation

Prerequisites: Node.js, npm (or yarn), MongoDB instance.

Clone the repository:

git clone https://github.com/vishnuvardhan-007/ResolveNow-Your-Platform-for-Online-Complaints.git


Navigate into project directories and install dependencies:

cd ResolveNow-Your-Platform-for-Online-Complaints/server  
npm install  

cd ../client  
npm install  


Set up environment variables in the /server/.env file, for example:

MONGO_URI=<your mongo connection string>
JWT_SECRET=<your jwt secret>
CLIENT_URL=http://localhost:3000


Run the backend server:

cd ../server
npm run dev


Run the frontend client:

cd ../client
npm start


Open your browser to http://localhost:3000 and you’re ready to go!

✅ How to Use

Sign up as a user (or register as an agent/admin, depending on your role).

Submit a complaint – fill out the form, choose category, add description/attachment.

Track your complaint – view status updates, read/respond to messages.

Agents/Admin – log in to your respective dashboard, view new complaints, take action, update statuses.

Admin – manage users and agents, view reports/analytics, system settings.

🧪 Testing

Manual testing of complaint workflows (submit → assign → update → resolve).

Role-based access verification (user vs agent vs admin).

Cross-browser and mobile responsiveness tests.

For future scope: integrate automated test suite (e.g., Jest, Mocha, Cypress).

📈 Results & Impact

By implementing this platform:

Complaints can be documented, tracked and resolved in a structured manner.

Users feel empowered when they see their issues addressed transparently.

Organizations can streamline grievance handling, reduce manual overhead and improve response times.

Admins gain valuable insights into complaint trends and performance metrics.

👍 Advantages & 👎 Limitations

Advantages:

User-friendly, role-based system.

End-to-end transparency.

Scalable, modern tech stack.

Responsive across devices.

Limitations:

Currently lacks built-in automated notifications (e.g., SMS) — may be added later.

No deep analytics or dashboards beyond basic reporting — scope for enhancement.

Attachment storage/security setup may need maturity for production-grade deployment.

🔭 Future Scope

Add SMS/Push notifications for real-time alerts.

Integrate analytics dashboards with charts showing complaint categories, resolution times, agent performance.

Introduce AI-powered category suggestions or sentiment analysis on complaint descriptions.

Optimize for high-availability and deployment as SaaS (multi-tenant).

Incorporate role-based workflow customisation, so different organisations can adopt the platform with their own rules and hierarchies.

🤝 Contributing

Feel free to fork the project, open issues, submit pull requests — all contributions are welcome. Please ensure you follow standard PR etiquette: run tests, document changes, keep code clean.

