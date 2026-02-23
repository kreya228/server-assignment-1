# Student CGPA API

## 📌 About Project

This is a simple REST API made using Express.js.
It stores student CGPA data inside a JSON array (no database used).

Only GET routes are used as per assignment requirement.

---

## 🛠 Technologies Used

* Node.js
* Express.js
* CORS

---

## 📊 Student Data Format

Each student has:

```
{
  id: 1,
  name: "Aarav Sharma",
  branch: "CSE",
  semester: 8,
  cgpa: 9.3
}
```

---

## 🚀 API Routes

### 1️⃣ GET /students

Returns all students.

### 2️⃣ GET /students/topper

Returns student with highest CGPA.

### 3️⃣ GET /students/average

Returns average CGPA of all students.

Response example:

```
{
  "averageCGPA": 8.12
}
```

### 4️⃣ GET /students/count

Returns total number of students.

### 5️⃣ GET /students/:id

Returns student by ID.
If not found → 404 error.

Example:

```
/students/3
```

### 6️⃣ GET /students/branch/:branchName

Returns students of a particular branch.

Example:

```
/students/branch/CSE
```

---

## ▶️ How to Run Project

1. Clone repository

```
git clone <your-github-link>
```

2. Install dependencies

```
npm install
```

3. Run server

```
node server.js
```

4. Open in browser or Postman

```
http://localhost:5000/students
```

---

## 🌐 Deployment Link

Add your Render link here.

---

## 📄 Postman Documentation

Add your Postman public documentation link here.

---

## 👩‍💻 Author

Your Name

---

This project is made for learning REST API basics using Express.js.