
# 📒 Notes App - Back End

This is the back-end of a simple note-taking application built with a REST API concept. It supports full CRUD functionality (Create, Read, Update, Delete) and note archiving (archived & unarchived).

## ✨ Features
- Create new notes
- View all notes
- View note details
- Update notes
- Delete notes
- Archive and unarchive notes

## 🛠️ Technologies Used
- Node.js
- Express.js
- (Optional) JSON file / basic database

## 🔧 API Endpoints

| Method | Endpoint             | Description                   |
|--------|----------------------|-------------------------------|
| GET    | `/notes`             | Get all notes                 |
| GET    | `/notes/:id`         | Get note details              |
| POST   | `/notes`             | Create a new note             |
| PUT    | `/notes/:id`         | Update a note                 |
| DELETE | `/notes/:id`         | Delete a note                 |
| GET    | `/notes/archived`    | Get archived notes            |
| PATCH  | `/notes/:id/archive` | Archive / unarchive a note    |

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/notes-app-back-end.git
   cd notes-app-back-end
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

By default, the server will run at `http://localhost:3000`.

## 📂 Project Structure (optional)

```
notes-app-back-end/
├── routes/
│   └── notes.js
├── controllers/
│   └── notesController.js
├── models/
│   └── notesModel.js
├── data/
│   └── notes.json
├── app.js
└── package.json
```

---

📌 *Note*: This project is created as part of learning back-end development and simple data management during university coursework.
