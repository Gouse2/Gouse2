# 👋 Hi, I'm Shaik Gouse

🎓 Computer Science Engineering Graduate (2024)  
💻 Aspiring Java Backend / Full Stack Developer  
📍 India

---

## 🚀 About Me
I am a motivated Computer Science graduate with a strong interest in **Java Backend and Full Stack Development**. I focus on building **real-world, production-style applications** using Java and modern backend frameworks.

I also have **7–8 months of HR internship experience**, which helped me understand real hiring needs, business workflows, and how software solutions are evaluated in companies. This combination allows me to design applications with a strong business and technical perspective.

---

## 🛠️ Tech Stack

### Backend & Programming
- Java (Core Java, OOPs)
- Spring Boot
- RESTful APIs
- Hibernate / JPA
- JDBC

### Database
- MySQL

### Frontend
- HTML
- CSS
- JavaScript

### Tools & Platforms
- Git & GitHub
- Postman
- Eclipse / IntelliJ IDEA
- VS Code

---

## 📌 Featured Projects

### 🔹 Student Management System (Java + Spring Boot)
A full-stack application designed to manage student data efficiently with role-based access.

**Key Features:**

## Key Features

- **🚀 Add Student**  
  - **What it does**: Enter student details (name, email, marks, type) and save instantly to MySQL.  
  - **Backend Magic**: Uses `StudentDAO.add()` with Hibernate's `persist()` for secure insertion.  
  - **Frontend Flow**: Simple form with input validation + POST API call to `/students`.  
  - **Why cool?**: Auto-generates ID and shows success message – no duplicates!

- **🔍 Get Student by ID**  
  - **What it does**: Input an ID to fetch and display full student profile (name, email, marks, type).  
  - **Backend Magic**: `StudentDAO.get(id)` queries the database directly.  
  - **Frontend Flow**: ID field + GET API to `/students/{id}` + clean card display.  
  - **Why cool?**: Handles "not found" gracefully with user-friendly error messages.

- **✏️ Update Student by ID**  
  - **What it does**: Load a student by ID, edit any field, and update the record.  
  - **Backend Magic**: `StudentDAO.update()` merges changes with Hibernate.  
  - **Frontend Flow**: Load via GET, editable form + PUT API to `/students/{id}`.  
  - **Why cool?**: Partial updates only (e.g., change marks without touching name).

- **🗑️ Delete Student by ID**  
  - **What it does**: Enter ID to permanently remove a student from the database.  
  - **Backend Magic**: `StudentDAO.delete(id)` with safe "if exists" check.  
  - **Frontend Flow**: ID input + confirmation dialog + DELETE API to `/students/{id}`.  
  - **Why cool?**: Prevents accidental deletes with a "Are you sure?" popup.

- **📊 View All Students**  
  - **What it does**: Loads and displays the entire student list in a searchable table.  
  - **Backend Magic**: `StudentDAO.getAll()` fetches via HQL query.  
  - **Frontend Flow**: Dynamic table from GET API to `/students` + sort/filter options.  
  - **Why cool?**: Responsive design – works on mobile, with hover effects for better UX.

**Tech Stack:**  

**Backend:** Java 17, Hibernate 5.6.9, MySQL Connector 8.0.28, SparkJava 2.9.4 (REST), Jackson 2.15.2 (JSON)
**Frontend:** Vanilla HTML/CSS/JS (no frameworks – pure and lightweight)
**Database:** MySQL table "student" (id, name, email, marks, type)
**Tools:** Eclipse (IDE), VS Code (frontend), Maven (dependencies)

👉 Source Code: *((https://github.com/Gouse2/Student-Management-System))*

### 🔹 Mini-Event-platform (MongoDB, Express.js, React.js, Node.js)
A full-stack MERN application designed to manage event data efficiently. 

**Key Features:**

**User Authentication:** Register/login with email/password validation (Gmail only, min 6-char password). JWT tokens for protected routes. Forgot Password link.
**Event Management (CRUD):** Create events with title, description, date, location, capacity. View list on dashboard. Edit/delete (only by owner)."
**RSVP System:** Join/leave events with real-time attendee count. Strict capacity enforcement (can't join if full).
**Concurrency Handling:** Atomic MongoDB operations to prevent overbooking (e.g., check attendees < capacity before adding user).
**Ownership Protection:** Users can only edit/delete their own events.
**Responsive UI:** Bootstrap for mobile/desktop compatibility. Party-style gradient background.
**Bonus Animations:** Confetti explosion on event creation and join for engaging UX.
**Error Handling:** Frontend validation, backend error messages, loading states.

👉 Source Code: *(https://github.com/Gouse2/Mini-Event-Platform)*

---

### 🔹 Java Practice & Mini Projects
A collection of Java programs demonstrating strong fundamentals in:
- OOP concepts
- Collections Framework
- Exception Handling
- JDBC & database connectivity

👉 Source Code: *(https://github.com/Gouse2/Fourth-Hibernate)*

---

## 🧠 Currently Learning
- Advanced Spring Boot
- Data Structures & Algorithms (Java)
- Basics of System Design

---

## 📊 Coding Profiles
- **LeetCode:** *(https://leetcode.com/u/Shaikgouse_5/)*
- **GitHub:** https://github.com/Gouse2

---

## 📫 Contact Me
- **LinkedIn:** *(https://www.linkedin.com/in/gouse-shaik-11b015258/)*
- **Email:** *(gouseshaik4573@gmail.com)*

---

⭐ I am actively seeking **entry-level opportunities** as a  
**Java Developer / Backend Developer / Software Engineer**.

Thank you for visiting my GitHub profile!
