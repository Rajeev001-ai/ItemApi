# Item API - Spring Boot REST Application

## Description
This is a simple RESTful backend application built using Spring Boot.
It allows users to manage items using in-memory storage (ArrayList).

---

## Tech Stack
- Java 17
- Spring Boot
- Maven
- REST API
- Validation API

---

## How to Run

### Clone Project
git clone <https://github.com/Rajeev001-ai/ItemApi.git>

### Run Project
mvn spring-boot:run

---

## API Endpoints

### Add Item
POST /api/items

Sample Body:
{
  "name": "Laptop",
  "description": "Gaming Laptop",
  "price": 75000
}

---

### Get Item By ID
GET /api/items/{id}

---

### Get All Items
GET /api/items

---

## Storage
In-memory ArrayList is used (no database).

---

## Notes
- Input validation implemented using annotations.
- RESTful structure followed.
