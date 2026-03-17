Student Management API

Project Overview  
I developed this project using Django REST Framework to implement a Student Management system. This API allows users to perform complete CRUD operations on student data following RESTful principles.

Objective  
The objective of this project is to build a backend system that can create, retrieve, update, and delete student records efficiently.

Features  
- I implemented CRUD operations using ModelViewSet  
- I used ModelSerializer for handling data  
- I configured routers for clean API endpoints  
- I added validation to ensure:  
  Email is unique  
  Age is greater than 16  
- I implemented pagination with a limit of 5 records per page  
- I added search functionality based on student name  
- I added filtering based on age  

Technologies Used  
- Python  
- Django  
- Django REST Framework  
- SQLite  

API Endpoints  

GET    /students/         Retrieve all students  
POST   /students/         Create a new student  
GET    /students/<id>/    Retrieve a single student  
PUT    /students/<id>/    Update student details  
DELETE /students/<id>/    Delete a student  

Setup Instructions  

1. Clone the repository  
git clone https://github.com/your-username/Student-Management-API.git  

2. Navigate to the project folder  
cd student_management  

3. Create a virtual environment  
python -m venv venv  

4. Activate the environment  
Windows:  
venv\Scripts\activate  

5. Install dependencies  
pip install -r requirements.txt  

6. Run the server  
python manage.py runserver  

Project Structure  
students/ - contains models, serializers, views, and URLs  
student_management/ - project settings and configuration  
manage.py - main entry point  

What I Learned  
Through this project, I learned how to build REST APIs using Django REST Framework, implement validation, use ViewSets and routers, and structure backend applications properly.

Author  
Suvathi
