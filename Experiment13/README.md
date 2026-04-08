# EXPERIMENT 13 - 23BIS70052 (Student CRUD API)

Flask + MySQL REST API for managing student records.

## Setup
1. Clone repo and install: `pip install -r requirements.txt`
2. Create `.env` from `.env.example` and fill in your DB credentials
3. Run MySQL setup SQL from `schema.sql`
4. Start server: `python app.py`


### Render Link: https://two3bis70047experiment13-fsd2.onrender.com

## Screenshots

### 1. Server/DB Connection Running
![Server Running](SERVERRUN.png)

### 2. Create User
![Crete Users](CREATE.png)

### 4. Read User
![GET All Order](READ_ALL.png)

### 5. Read One User
![GET One User](READ_ONE.png)

### 6. Update User
![PUT User](UPDATE.png)

### 7. Validation Procedure
![Verification](VALIDATION.png)

### 8. Delete User
![Delete Service](DELETE.png)

### 9. Database Show
![Database Showcasing](DATABASE.png)

### 10. Server Running
![Server Running](SERVERRUN.png)



## Endpoints

| Method | Endpoint              | Description        |
|--------|-----------------------|--------------------|
| POST   | /api/students         | Create student     |
| GET    | /api/students         | Get all students   |
| GET    | /api/students/<id>    | Get one student    |
| PUT    | /api/students/<id>    | Update student     |
| DELETE | /api/students/<id>    | Delete student     |

## Validations
- Name: min 2 characters
- Email: valid format, must be unique
- Age: number between 1–120
- Course: min 2 characters


## Learning Outcomes

### 1. Understanding REST API Architecture
### 2. Flask Backend Development
### 3. Database Connectivity
### 4. CRUD Operations
### 5. Input Validation
### 6. Environment Variable Management
### 7. Cloud Database Integration
### 8. API Deployment on Cloud
### 9. API Testing with Postman
### 10. Error Handling
