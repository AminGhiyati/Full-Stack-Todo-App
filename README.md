# 📝 To-Do App (My First Full Stack Project – PERN)

This is my **first full stack app** using **PostgreSQL, Express, React, and Node**. It's a basic to-do list with full CRUD functionality.

## ⚙️ Setup

1. **Clone & Install (Backend)**

```
npm install  
npm run dev
```

2. **Frontend**

```
cd client  
npm install  
npm start
```

3. **.env (in root folder)**
   Create a file called `.env`:

```
DB_USER=postgres  
DB_PASSWORD=your_password  
DB_HOST=localhost  
DB_PORT=5432  
DB_NAME=todo_db  
PORT=5000
```

> ✅ The backend automatically creates the `todos` table if it doesn't exist.

