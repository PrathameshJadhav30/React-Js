# React JS Setup Using Vite 🚀

## 📌 Project Title
React Installation and Setup using Vite

---

## 📖 Project Description
This project demonstrates how to set up a React JS application using Vite.  
Vite is a modern frontend build tool that provides fast development server startup and optimized production builds.

---

## 🛠️ Prerequisites

Make sure the following software is installed:

- Node.js (LTS version recommended)
- npm (comes with Node.js)

Check versions using:

```bash
node -v
npm -v
```

---

## 📥 Installation Steps

### 1️⃣ Create React App using Vite

```bash
npm create vite@latest
```

Select the following options:

- Project Name: react-first-app
- Framework: React
- Variant: JavaScript

---

### 2️⃣ Navigate to Project Folder

```bash
cd react-first-app
```

---

### 3️⃣ Install Dependencies

```bash
npm install
```

---

### 4️⃣ Start Development Server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173/
```

---

## 📁 Project Structure

```
react-first-app/
│
├── node_modules/
├── public/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── assets/
├── index.html
├── package.json
└── vite.config.js
```

---

## 📌 Important Files

### main.jsx
Entry point of the React application. It renders the App component into the root div.

### App.jsx
Main component where UI content is written.

### index.html
Contains the root div where React application loads.

---

## 🔨 Production Build

To create production-ready files:

```bash
npm run build
```

The build output will be generated inside:

```
dist/
```

---

## 🎯 Key Commands Summary

| Command | Purpose |
|---------|----------|
| npm create vite@latest | Create new React project |
| npm install | Install dependencies |
| npm run dev | Start development server |
| npm run build | Build for production |

---

## 🎓 Learning Outcomes

- Understanding React project setup
- Using Vite for faster development
- Running development server
- Creating production build

---

## 👨‍💻 Author

Prathamesh Jadhav  
Artificial Intelligence and Data Science Engineering

---

## ✅ Conclusion

This practical successfully demonstrates the installation and setup of a React JS application using Vite.