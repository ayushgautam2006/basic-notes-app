
# 📝 Basic Notes App (Node.js + Express + EJS)

A simple file-based note-taking web app built using **Node.js**, **Express.js**, and **EJS**.  
Users can create, view, and manage `.txt` notes stored on the server.

---

## 🚀 Features

- 📁 View a list of all notes (files) stored in the `/files` folder
- 🔍 View the content of any note
- ➕ Create a new note via a form
- 💾 Automatically saves notes as `.txt` files
- 🧱 Built with Express.js and EJS for templating

---

## 📁 Folder Structure

```
project/
├── index.js              # Main server file
├── files/                # Stores all note .txt files
├── public/               # Static files (CSS, JS, images)
├── views/                # EJS templates
│   ├── index.ejs         # Homepage to list and add notes
│   └── show.ejs          # Display a single note
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/basic-notes-app.git
   cd basic-notes-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the app:**
   ```bash
   node index.js
   ```

4. **Visit in browser:**
   ```
   http://localhost:3000
   ```

---

## 📌 Requirements

- Node.js (v14 or above)
- NPM

---

## ✨ Example Usage

1. Go to the homepage (`/`) to see a list of notes.
2. Submit a title and content to create a new `.txt` file.
3. Click on any note to view its content.

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **EJS (Embedded JavaScript Templates)**
- **File System (fs module)**

---

## 📄 License

This project is open source and free to use under the [MIT License](LICENSE).

---

## 🙌 Contributing

Feel free to open issues or pull requests to improve this project!
