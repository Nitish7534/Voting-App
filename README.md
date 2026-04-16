# 🗳️ Voting System Backend Application

## 📌 Project Overview

The Voting System Backend Application is designed to manage a secure and efficient voting process. It allows users to register, authenticate, and cast their votes while ensuring data integrity and role-based access control. The system prevents duplicate voting and maintains accurate vote records.

---

## 🎯 Features

* User Registration and Login Authentication
* Role-Based Access Control (Admin/User)
* Secure Voting Mechanism (One User = One Vote)
* Real-time Vote Count Management
* REST API for handling voting operations
* Data validation and error handling

---

## 🧪 Testing Overview

The application was tested to ensure correctness, security, and reliability of backend operations.

### ✔ Testing Performed:

* Functional Testing of login, voting, and result modules
* API Testing using Postman for response validation
* Validation of role-based access control
* Edge case testing (duplicate voting, invalid inputs)
* Database validation for data consistency

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **API Testing:** Postman
* **Version Control:** Git, GitHub

---

## 📂 Project Structure

```
Voting-App
│
├── routes
├── models
├── server.js
└── package.json
```

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/Nitish7534/voting-app.git
```

2. Navigate to the project folder:

```
cd voting-app
```

3. Install dependencies:

```
npm install
```

4. Run the server:

```
npm start
```

---

## 📬 API Testing

* Use Postman to test endpoints like:

  * `/register`
  * `/login`
  * `/vote`
  * `/results`

---

## 🚀 Future Enhancements

* Add frontend UI for better user interaction
* Implement JWT-based authentication
* Add automated testing using Selenium
* Improve security and encryption

---

## 👨‍💻 Author

Nitish Raikhola

---
