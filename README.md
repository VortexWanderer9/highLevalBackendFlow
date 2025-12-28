User
 ↓
Frontend (React / HTML / App)
 ↓  HTTP Request
Backend (Server)
 ↓
Business Logic
 ↓
Database
 ↑
Response (JSON)
 ↑
Frontend
 ↑
User sees result

______
backend/
│
├── controllers/   → logic
├── routes/        → API routes
├── models/        → database structure
├── middleware/    → auth, validation
├── config/        → DB connection
└── server.js      → app start
___________________
Request → Middleware → Route → Controller → Response
______________

