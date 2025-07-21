# 📘 GO_STUDENT_API

A RESTful API built using **Golang** and **SQLite** to manage student records. This project demonstrates how to structure a basic Go-based web API with modular architecture and clean code practices.

## 🚀 Features

- ✅ Create a new student record  
- ✅ Get a student record by ID  
- ✅ List all student records  

## 📦 Requirements

- Go 1.22+
- SQLite3
- Postman for testing

  
## Run the API: 
go run cmd/Students-API/main.go -config config/local.yaml


## 🔄 API Endpoints

| Method | Endpoint             | Description          |
| ------ | -------------------- | -------------------- |
| POST   | `/api/students`      | Create a new student |
| GET    | `/api/students/{id}` | Get student by ID    |
| GET    | `/api/students`      | List all students    |

