# Family-Legal-Rights-Awareness-Platform
Family Legal Rights Awareness Platform
Overview
The Family Legal Rights Awareness Platform is a web application that provides families with essential legal resources, articles, and consultations on family rights, marriage, children, and property. It empowers families by educating them about their legal rights and connects them with legal support when needed.

Project Description
This platform serves as a central hub for legal awareness, helping families:

Learn about their legal rights in various family matters.
Access legal consultations.
Understand their legal protections, such as divorce, custody, and property rights.
Connect with legal professionals for support and assistance.
Technologies Used
Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
Libraries:
Axios (for making HTTP requests)
React Router (for page navigation)
Mongoose (for MongoDB object modeling)
Features
Legal Awareness: Displays legal articles that educate families on their rights.
Consultation Requests: Allows users to request a legal consultation through a form.
Legal Protections: Provides information on divorce, child custody, and property rights.
Empowerment: Offers tools to empower families with knowledge of their rights.
Legal Support: Lists contact information for legal support and law firms.
How to Use

1. Install Dependencies
Navigate to the project directory:

bash
Copy code
cd family-legal-rights-awareness
Backend (Node.js): In the backend directory, install dependencies using npm:

bash
Copy code
cd backend
npm install
Frontend (React.js): In the frontend directory, install dependencies using npm:

bash
Copy code
cd frontend
npm install
2. Start the Backend Server
In the backend directory, start the server:

bash
Copy code
npm start
The backend server will start at http://localhost:5000.

3. Start the Frontend React Application
In the frontend directory, start the React app:

bash
Copy code
npm start
The React application will start at http://localhost:3000.

API Endpoints
GET /api/legal/articles: Retrieve a list of legal articles to educate families about their rights.
POST /api/legal/consultations: Submit a request for a legal consultation.
GET /api/legal/protections: Retrieve information on legal protections such as divorce and custody rights.
Folder Structure
plaintext
Copy code
family-legal-rights-awareness/
├── backend/
│   ├── models/             # MongoDB models for articles and consultations
│   ├── routes/             # API routes
│   └── server.js           # Express server setup
│
├── frontend/
│   ├── src/
│   │   ├── components/     # React components for different pages
│   │   └── App.js          # Main React app file
│   └── public/
│       └── index.html      # HTML file for the React app
│
├── .gitignore              # List of files to be ignored by git
├── README.md               # Project documentation
└── package.json            # Project dependencies and scripts
Contributing
Contributions to the project are welcome! 
