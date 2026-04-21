# Job Portal 🚀

A full-stack Job Portal web application built using modern web technologies.
This platform allows users to register, login, browse jobs, and apply for opportunities with a clean and responsive UI.

---

## 🚀 Tech Stack

**Frontend:**

* React.js (Vite)
* Tailwind CSS
* PostCSS

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

**Authentication:**

* JWT (JSON Web Token)

**Other Tools:**

* Cloudinary (Image Upload & Storage)

---

## ✨ Features

### 👨‍💼 User Module

* User Signup & Login
* Browse jobs
* Apply for jobs
* Resume usage anytime

---

### 🔐 Authentication & Authorization

* Secure login/signup using JWT
* Protected routes

---

### ⚡ Other Features

* Image upload using Cloudinary
* RESTful API structure
* Fully responsive UI
* Clean frontend & backend separation

---

## 📂 Project Structure

```id="finalstruct01"
jobportal/
│
├── frontend/                     # React frontend (Vite + Tailwind)
│   ├── src/
│   │   ├── components/           # UI components
│   │   ├── assets/               # Images & static files
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── public/
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   ├── tailwind.config.js
│   └── postcss.config.js
│
├── backend/                      # Node.js backend (Express + MongoDB)
│   ├── controllers/              # Business logic
│   ├── models/                   # Database schemas
│   ├── routes/                   # API routes
│   ├── middlewares/              # Auth middleware
│   ├── utils/                    # Helper functions
│   ├── index.js                  # Entry point
│   ├── package.json
│   └── package-lock.json
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside backend folder:

```id="envfinal01"
MONGO_URI=your_mongodb_connection  
JWT_SECRET=your_secret_key  
CLOUDINARY_CLOUD_NAME=your_cloud_name  
CLOUDINARY_API_KEY=your_api_key  
CLOUDINARY_API_SECRET=your_api_secret  
PORT=5000
```

---

## 🛠️ Installation & Setup

### Clone the repository

```id="clonefinal01"
git clone https://github.com/abhishekSingh930/jobportal12.git  
cd jobportal
```

---

### Backend Setup

```id="backendfinal01"
cd backend  
npm install  
npm start
```

---

### Frontend Setup

```id="frontendfinal01"
cd frontend  
npm install  
npm run dev
```

---

## 🚀 Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway

---

## 📡 API Endpoints

Base URL:

```id="apifinal01"
/api
```

### Example routes:

* POST `/auth/signup` → Register user
* POST `/auth/login` → Login user
* GET `/jobs` → Get all jobs
* POST `/apply` → Apply for job

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a new branch
* Commit your changes
* Push to your branch
* Open a Pull Request

---

## 👨‍💻 Author

**Abhishek Singh**

---

## 📄 License

This project is built for learning and practice purposes.
