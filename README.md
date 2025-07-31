# 🍽️ Maakitchen

**Maakitchen** is a modern, full-stack food-tech web application that blends culinary creativity with powerful technology. From personalized recipes to secure user authentication, Maakitchen is built for performance, security, and beautiful design.

---

## ✨ Features

- 🍔 **Smart Recipe Generation** (using Google Generative AI)
- 🔐 Secure Authentication with **JWT** and **bcryptjs**
- 📦 Robust backend using **Express** + **MongoDB/Mongoose**
- 💳 Seamless Payment Integration via **Razorpay**
- 🌐 Realtime Data with **Firebase**
- 🎨 Stunning UI with **Chakra UI**, **TailwindCSS**, and **Framer Motion**
- 🔁 Client-Side Routing using **React Router**
- 🧠 Form Validation with **Joi**
- 📦 Modular Architecture for Scalable Development

---

## 🛠️ Tech Stack

### 🧩 Frontend
- **React 19**, **Next.js**
- **TailwindCSS**, **Chakra UI**, **Emotion**
- **Framer Motion** & **Motion** for animations
- **Typed.js** for dynamic typing effects
- **React Icons**, **Tabler Icons**
- **React Router DOM**

### 🚀 Backend
- **Node.js**, **Express.js**
- **MongoDB** with **Mongoose**
- **JWT** for authentication
- **bcryptjs** for password hashing
- **Joi** for schema validation
- **Razorpay** for payments
- **Firebase** for realtime features

---

## 📦 Dependencies

> All major dependencies used in the app:

### Backend

```json
{
  "bcryptjs": "^3.0.2",
  "body-parser": "^2.2.0",
  "cors": "^2.8.5",
  "dotenv": "^17.2.0",
  "express": "^5.1.0",
  "joi": "^17.13.3",
  "jsonwebtoken": "^9.0.2",
  "mongodb": "^6.17.0",
  "mongoose": "^8.16.3",
  "razorpay": "^2.9.6"
}
Frontend
json
Copy
Edit
{
  "@chakra-ui/react": "^3.22.0",
  "@emotion/react": "^11.14.0",
  "@google/generative-ai": "^0.24.1",
  "@radix-ui/react-label": "^2.1.7",
  "@tabler/icons-react": "^3.34.0",
  "@tailwindcss/vite": "^4.1.11",
  "axios": "^1.10.0",
  "clsx": "^2.1.1",
  "firebase": "^12.0.0",
  "framer-motion": "^12.23.3",
  "motion": "^12.23.3",
  "next": "^15.4.5",
  "react": "^19.1.0",
  "react-dom": "^19.1.0",
  "react-icons": "^5.5.0",
  "react-router-dom": "^7.6.3",
  "tailwind-merge": "^3.3.1",
  "typed.js": "^2.1.0"
}
🧪 Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/maakitchen.git
cd maakitchen
2. Install Backend & Frontend Dependencies
bash
Copy
Edit
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
3. Setup Environment Variables
Create .env files in both backend/ and frontend/ folders.

Example .env for backend:

env
Copy
Edit
PORT=5000
MONGODB_URI=mongodb://localhost:27017/maakitchen
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
🚀 Run the App
Start Backend Server
bash
Copy
Edit
cd backend
npm start
Start Frontend Dev Server
bash
Copy
Edit
cd frontend
npm run dev
📸 Screenshots
