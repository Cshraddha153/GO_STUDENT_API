# 📘 GO_STUDENT_API

A RESTful API built using **Golang** to manage student records. This project demonstrates how to structure a basic Go-based web API with modular architecture and clean code practices.

## 🚀 Features

- ✅ Create a new student record  
- ✅ Get a student record by ID  
- ✅ List all student records  

## 🧱 Project Structure

**GO_STUDENT_API/**
│
├── **cmd/** # Entry point for the application
│ └── **Students-API/** # Main.go file with routing and config loading
│
├── **internal/** # Core logic and business layers
│ ├── **config/** # Configuration loading
│ ├── **db/** # Database initialization (if applicable)
│ ├── **student/** # Handlers for student operations
│ └── **types/** # Struct definitions
│
├── go.mod # Go module file
└── **config/** # YAML or JSON config files

## Run the API: 
go run cmd/Students-API/main.go -config config/local.yaml


## 🔄 API Endpoints

| Method | Endpoint             | Description          |
| ------ | -------------------- | -------------------- |
| POST   | `/api/students`      | Create a new student |
| GET    | `/api/students/{id}` | Get student by ID    |
| GET    | `/api/students`      | List all students    |

