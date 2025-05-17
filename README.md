
# 📘 Quora Post - RESTful API App

A lightweight Node.js + Express.js CRUD application for managing Quora-like posts. It uses **EJS** for rendering views and **in-memory storage** (no database), ideal for learning REST principles.

---
## 🚀 Live Demo (Local)

After running, open:  
```
http://localhost:8080/post
```

---

## ✨ Features

- 📄 View all posts
- ➕ Add new post
- 🔍 View single post
- ✏️ Edit a post
- ❌ Delete a post
- 🖥️ Clean UI using EJS templates

---

## 🛠️ Built With

- **Node.js** – Backend JavaScript runtime
- **Express.js** – Web framework
- **EJS** – Template engine
- **HTML/CSS** – UI and styling

---

## 📁 Project Structure

```
Restfull-API-Project-main/
│
├── index.js             # Main Express app
├── style.css            # Basic CSS styling
├── index.ejs            # All posts listing
├── new.ejs              # Form to add post
├── show.ejs             # Post detail view
├── edit.ejs             # Edit form
└── README.md            # Documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Restfull-API-Project.git
cd Restfull-API-Project-main
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the app

```bash
node index.js
```

Open your browser and go to `http://localhost:8080/post`

---

## 🔁 Routes Overview

| Route              | Method | Description            |
|-------------------|--------|------------------------|
| `/post`           | GET    | Show all posts         |
| `/post/new`       | GET    | Show create form       |
| `/post`           | POST   | Create a new post      |
| `/post/:id`       | GET    | Show single post       |
| `/post/:id/edit`  | GET    | Edit post form         |
| `/post/:id`       | POST   | Update post            |
| `/post/:id/delete`| POST   | Delete post            |

---

## 🚫 Note

🧠 **No database** is used. Posts are stored in memory and will reset when the server restarts.

---

## 👤 Author

**Abhishek Chauhan**  
🔗 [GitHub](https://github.com/ChauhanAbhishek8)

---

## 📄 License

MIT License

---

