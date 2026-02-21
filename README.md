# Student API with Gin

## How to Run
```bash
go run main.go

Server runs at:
http://localhost:8080

# Available Endpoints
GET /students
GET /students/:id
POST /students
PUT /students/:id
DELETE /students/:id

## Example: Create Student
POST /students

```json
{
  "id": "S003",
  "name": "Luke",
  "major": "Computer Science",
  "gpa": 4.0
}

## Example: Update Student
PUT /students/S003

```json
{
  "name": "Luke Skywalker",
  "major": "Computer Science",
  "gpa": 3.50
}