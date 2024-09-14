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

### Create All Task
- **URL:** `/tasks/`
- **Method:** `GET`
- **Query Parameters:** `status, priority, ordering`

### Get Task by ID
- **URL:** `/tasks/{id}/`
- **Method:** `GET`

### Update Task
- **URL**: `/tasks/{id}/`
- **Method:** `PUT`
- **Body:**
  ```json
  {
    "title": "Updated Title",
    " description": "Updated Description",
    "status": "Done",
    "due_date": "2024-12-31",
    "priority": "High"
  }
### Delete Task
- **URL:** `/tasks/{id}/`
- **Method:** `DELETE`
