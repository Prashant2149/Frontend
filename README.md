# Frontend (Vue.js)

This is the **frontend** for the My-Account project, built using **Vue 3 + Vite**. It fetches and displays users from the backend API.

## 📌 Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [Backend API](https://github.com/Prashant2149/Backend)

## 📂 Folder Structure
```
frontend/
│── src/
│   ├── components/
│   │   ├── UserList.vue
│   ├── App.vue
│── public/
│── package.json
│── vite.config.js
│── .env
│── README.md
```

## 📌 Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/Prashant2149/Frontend
cd frontend
npm install
```

## ⚙️ Environment Variables (.env)
Create a `.env` file in the root directory:
```ini
VITE_API_URL=http://localhost:3000
```

## 🚀 Running the Frontend
```sh
npm run dev
```

Then open:
```
http://localhost:5173
```

## 🖥️ Features
- Fetch users from the backend API
- Display users in a simple list

## 📜 License
This project is licensed under [MIT](LICENSE).

