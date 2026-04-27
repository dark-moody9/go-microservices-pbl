# 📚 Go Microservices Project: Article Management System

A foundational microservice built with **Go** and the **Gin Web Framework**.  
This project demonstrates clean architecture, content negotiation (HTML, JSON, XML), and unit testing.

---

## 🚀 Features

- Content Negotiation  
  - `application/json` → JSON  
  - `application/xml` → XML  
  - Default → HTML  

- Modular Architecture (models, handlers, routing)  
- Preloaded HTML templates for better performance  
- Unit testing for models and handlers  

---

## 📦 Dependencies

- github.com/gin-gonic/gin  
- go.mongodb.org/mongo-driver/v2 (optional / future use)

---

## ⚙️ Getting Started

### Prerequisites
- Go installed (v1.20+ recommended)

### Install Dependencies
```bash
go mod download

go run main.go

go test -v ./...
```
---

##📌 Example Usage
```bash

curl -H "Accept: application/json" http://localhost:8080/

curl -H "Accept: application/xml" http://localhost:8080/
```
