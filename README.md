# Student API with Gin

## How to Run
```bash
go run main.go

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