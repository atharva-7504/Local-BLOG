# Local-BLOG
CRUD operation implementations

📝 Blog API Project (Express + EJS)

A simple Blog Application built using Node.js, Express, REST APIs, and EJS.
This project demonstrates how a frontend server communicates with a backend REST API to perform CRUD operations (Create, Read, Update, Delete) on blog posts.

---

🚀 Features

* View all blog posts

* Create a new blog post

* Edit an existing post (PATCH)

* Delete a post

* REST API built using Express

* Clean UI using EJS & CSS

* Axios used for API communication

* In-memory data storage (no database)

---

🛠️ Tech Stack

* Backend API: Node.js, Express

* Frontend Server: Express, EJS

* HTTP Client: Axios

* Styling: CSS

* Data Storage: In-memory JavaScript array

---

🔌 API Endpoints

GET /posts

GET /posts/:id

POST /posts

PATCH /posts/:id

DELETE /posts/:id

--- 

▶️ How to Run the Project

1️⃣ Install dependencies
npm install

2️⃣ Start the API server
node index.js

* Runs on: http://localhost:4000

3️⃣ Start the frontend server
node server.js

* Runs on: http://localhost:3000

---

⚠️ Limitations

No database (data resets on server restart)

No authentication or authorization

No validation layer

---

🌟 Future Improvements

Add MongoDB / PostgreSQL

Add user authentication

Add timestamps formatting

Add comments & likes

Convert to full MVC structure

---

Blog View : 

<img width="1914" height="956" alt="Screenshot 2026-01-06 165414" src="https://github.com/user-attachments/assets/d16b7d73-4456-454a-b19a-a29e3da81a28" />

Create new blog : 

<img width="1912" height="963" alt="Screenshot 2026-01-06 165425" src="https://github.com/user-attachments/assets/e2057416-1574-497b-8407-bd401336aa54" />

Edit Blog : 

<img width="1916" height="962" alt="Screenshot 2026-01-06 165437" src="https://github.com/user-attachments/assets/d65d1e52-d9dd-412a-8595-a64d3002b3ef" />
