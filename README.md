# Task Manager API

## Endpoints

### Create a Task
- **URL:** `/tasks/`
- **Method:** `POST`
- **Body:**
  ```json
  {
    "title": "Task Title",
    "description": "Task Description",
    "status": "Pending",
    "due_date": "2024-12-31",
    "priority": "Medium"
  }
