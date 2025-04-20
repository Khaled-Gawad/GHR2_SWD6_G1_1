
---

# 🔌 API Testing – Fake Store API

This branch contains the **API testing** deliverables for our graduation project using the [Fake Store API](https://fakeapi.platzi.com/en).  
We used **Postman** for request execution and test scripting, and all documentation is maintained in a shared Google Sheet.

---

## 📄 Files Included

### ✅ 1. API Test Cases & Modules  
All API test cases are documented in the same Google Sheet used for manual testing.

Includes:
- Endpoint names and methods (GET, POST, PUT, DELETE)
- Request/response details
- Expected outputs
- Tester assignments and test execution status

📎 **View API Test Cases:**  
[API Testing – Google Sheet (API Reference Tab)](https://docs.google.com/spreadsheets/d/1GIx1EMnmM7PkqJQRKwS-IF68J1EAlqWp4uMujbS1vkM/edit?gid=1734676715#gid=1734676715)

---

### 📦 2. Postman Collections  
Uploaded Postman collections contain:
- Pre-configured API calls to the Fake Store API
- Associated test scripts for automated validation
- Environment variables where applicable

✅ Collections are organized per module (e.g. Users, Auth, Products, Files).

---

## 🔍 Tested API Modules & Responsibilities

| API Module          | Endpoints & Methods                     | Tester  |
|---------------------|------------------------------------------|---------|
| Users               | `GET /users`, `GET /users/:id`, `POST /users`, `PUT /users/:id` | Khaled  |
| Auth (Login/Profile)| `POST /auth/login`, `GET /auth/profile` | Rehab   |
| Products            | `GET /products`, `POST /products`, etc. | Eman    |
| Categories          | `GET /categories`, `POST /categories`   | Eman    |
| Files               | `POST /files/upload`, `GET /files/:id`  | Mohamad |

---

## 🛠️ Tools Used
- **Postman** – For API requests and test scripts
- **Google Sheets** – For test planning and tracking

---

