# ImmerseLearn 🎓

Welcome to **ImmerseLearn**, an engaging platform designed to elevate your learning experience. Dive into interactive courses, track your progress, and connect with a community of passionate learners—all within a sleek and intuitive interface.

---

## Live Demo 🌐

Check out the live application here:  
[https://immersi-learn.vercel.app/](https://immersi-learn.vercel.app/)

Video of working AR in mobile phone:
https://drive.google.com/file/d/1EcNvgBglzdzk_SdSGAsHaUUK6VaUYhdh/view?usp=drivesdk


---

## Features ✨

- Interactive and immersive learning modules  
- User registration and secure login (including Google OAuth)  
- Progress tracking and personalized dashboards  
- Responsive design for desktop and mobile  
- Integration with third-party APIs for enhanced functionality  

---

## Technology Stack 🛠️

- **Frontend:** React.js, Vite, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB, JWT Authentication  
- **Third-party Integrations:** Google OAuth, Stripe Payments, Gemini API  
- **State Management:** React Context and custom hooks  
- **Build Tools:** Vite for fast frontend builds  

---

## Project Structure 📁

```
/immerselearn
├── backend
│ ├── src
│ │ ├── controllers # API request handlers
│ │ ├── middleware # Auth and other middleware
│ │ ├── models # Mongoose models
│ │ ├── routes # Express routes
│ │ └── server.js # Backend entry point
│ ├── package.json
│ └── package-lock.json
│
├── frontend
│ ├── public # Static assets
│ ├── src
│ │ ├── components # React UI components
│ │ ├── context # React context providers
│ │ ├── pages # Full page components
│ │ ├── App.jsx # Root component
│ │ └── main.jsx # ReactDOM render entry
│ ├── package.json
│ ├── vite.config.js
│ ├── tailwind.config.js
│ ├── postcss.config.js
│ ├── eslint.config.js
│ └── package-lock.json
│
├── .gitignore
├── LICENSE
└── README.md
```


---

## Environment Variables Setup ⚙️

Create a `.env` file in the **backend** directory with the following variables (replace placeholders):

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GEMINI_API_KEY=your_gemini_api_key
SESSION_SECRET=your_session_secret
```
Create a .env file in the frontend directory with (for development):
```env
REACT_APP_API_URL=http://localhost:5000/api/auth
```
Remember to update the frontend .env when deploying to use your live backend URL.

## Getting Started 🚀

### Prerequisites

- Node.js v14 or newer  
- npm or yarn  
- MongoDB Atlas or local MongoDB instance  

### Installation

1. Clone the repository  
```bash
git clone https://github.com/yourgithub/immerselearn.git
cd immerselearn
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

4. Setup .env files as described above.
   
5. Running the Application
Backend:
```bash
cd backend
npm run build
npm start
```

Frontend:
Open a new terminal window and run:
```bash
cd frontend
npm run dev
```
Access the frontend at http://localhost:5173 (or your configured port).

## Usage 🎯

- Register a new account or log in (email/password or Google OAuth).  
- Access immersive courses and track your progress.  
- Engage with interactive content across devices.  
- Admin users can monitor analytics and user engagement.

---

## Contributing 🤝

Contributions are welcome! Please refer to the `CONTRIBUTING.md` file for guidelines on how to participate.

---

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


