# 📚 Book REST API (Node.js + Express)

This is a simple REST API to manage a list of books using **Node.js** and **Express**. It performs CRUD operations entirely in-memory (no database needed). Useful for learning and practicing RESTful API development.

---

## ✅ Features

- `GET /books` – Retrieve all books
- `POST /books` – Add a new book
- `PUT /books/:id` – Update a book by ID
- `DELETE /books/:id` – Delete a book by ID

---

## 🛠 Tech Stack

- Node.js
- Express.js
- Postman (for testing)

---

## 🚀 How to Run

1. Clone/download this repository.
2. Open terminal in the project folder.
3. Run `npm install` to install dependencies.
4. Run `node index.js` to start the server.
5. Open Postman and use `http://localhost:3000` to test endpoints.

---

## 🔁 Example JSON Body (for POST & PUT)

```
{
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}
```

---

## 📬 Sample Endpoints

| Method | Endpoint        | Description             |
|--------|------------------|--------------------------|
| GET    | `/books`         | Get all books            |
| POST   | `/books`         | Add new book             |
| PUT    | `/books/:id`     | Update book by ID        |
| DELETE | `/books/:id`     | Delete book by ID        |

---

## 📄 Notes

- All books are stored in an in-memory array.
- Data resets when the server restarts.
- Ideal for learning how APIs work without needing a database.

---

## 👨‍💻 Author

Created by **Prakhar Solanki** for educational purposes.
