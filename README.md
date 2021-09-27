# navigus_ass
Quiz_Generator

## Screenshots
### Homepage
![image](https://user-images.githubusercontent.com/45147323/134894526-2a2511e4-b827-4ff2-9bf3-27a4c9d69a6b.png)
### Admin Dashboard
![image](https://user-images.githubusercontent.com/45147323/134894177-b79811df-3b58-4461-9740-330f5c12cd70.png)
### Exam Rules
![image](https://user-images.githubusercontent.com/45147323/134894607-bf3d0524-fe23-4f55-a275-46d2a38555f6.png)
### Exam 
![image](https://user-images.githubusercontent.com/45147323/134895026-ed98af94-0f0a-4d61-9896-37f2577f04aa.png)
### Teacher Dashboard
![image](https://user-images.githubusercontent.com/45147323/134895081-440892a2-6793-441d-b337-7c83173ef57c.png)

## Functions
### Admin
- Create Admin account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Teacher
- Apply for job in System. Then Login (Approval required by system admin, Then only teacher can login).
- After Login, can see Total Number Of Student, Course, Questions are there in system on Dashboard.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
