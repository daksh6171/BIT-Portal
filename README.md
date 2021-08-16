# BIT-Portal

A College Management System built using Python's Django framework. It is designed for interactions between students and teachers. 

Features (Basic):
* Attendance
* Marks
* Time Table

Class Diagram:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Class_diagram.png)

ER-Diagram:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/ER_diagram.png)

## Installation
Install the Django framework of python using:

```bash
pip install django
```

## Run the Program
Open the BIT Portal folder and run the command in the terminal:

```bash
python manage.py runserver
```
Then go to the browser and run **https://127.0.0.1/8000**

## Log In
The Log In page is common for both teachers and students.
Username is different for each user, password for each user is "project123"

Some Username examples:    

Teacher: {'deepaknair', 'sheela', 'trisila'}   
Student: {'shubham', 'samarth', 'renu'}

Landing page:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Logout_page.png)

Log In page:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/login_page.png)

Logout Alert:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Logout_card.png)

## Admin Console
To access the admin console go to **https://127.0.0.1/8000/admin**  
Username: admin   
Password: admin

To create a super user (Another admin), type the command:
```bash
python manage.py createsuperuser
```
## Create New User
* New user can be created only by the admin. Log In to the admin panel and add user.   
* Admin is able to change tables like, Teacher, Students, User, Marks, Attendance etc.    
* It can create and delete entries from the above tables.

## Functions of Admin
* Create User
* Create Course
* Create Class
* Add/Remove Marks
* Mark Attendance
* Add/Remove Department

**Screenshots:**

Admin Homepage:   

![adminpage](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Home_page_admin.png)

Add User:

![alt_text](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_user.png)

Assign Class to Teacher:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Assign_Class_to_teacher.png)

Add Attendance:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_attendance_admin.png)

Add Class:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_class_admin.png)

Add Course:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_course.png)

Add Department:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_dept.png)

Add Marks:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_marks.png)

Add Student:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_student.png)

Add Teacher:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Add_teacher.png)


## Functions of Teacher
* Attendance
  * Change Attendance
* Marks
  * Add/Edit Marks
* View Timetable
* Generate Reports
  * If attendance < 75% color the cell red else green
  * If marks < 25% color the cell red else green

**Screenshots:**   

Teacher Homepage:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_homepage.png)

Teacher Attendance:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_attendance.png)

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_attendance(2).png)

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/teacher_present_absent.png)

Teacher Marks:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_marks(0).png)

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_marks.png)

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_marks_enter.png)

Teacher Timetable:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_timetable.png)

Free Teachers:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_free_teachers.png)

Teacher Reports:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_generatereport.png)

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Teacher_marks_report.png)

## Functions of Student
* View Attendance of each class
* View Marks of each subject
* View Timetable

**Screenshots:**  

Student Homepage:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Student_homepage.png)

Student Attendance:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Student_attendance.png)

Student Marks:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Student_marks.png)

Student Timetable:

![alt](https://github.com/daksh6171/BIT-Portal/blob/main/Images/Student_timetable.png)

## Scope of Advancement
This Web-App addresses major functionalities needed for an ERP, but one can always add various other functionalities, like teacher's attendance, cumulative grade reports, fee reports etc.
