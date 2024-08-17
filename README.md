<<<<<<< HEAD
# Library Management System

## screenshots
### Admin login Page
![adminhomepage](https://github.com/user-attachments/assets/73b58080-f1a2-43fa-80df-836882f444d4)
### Student Page
![viewstudentpage](https://github.com/user-attachments/assets/78af51a5-385c-4647-9215-97ed213251e8)
### Available Book
![availablebook](https://github.com/user-attachments/assets/ffba48f9-58eb-459c-a949-4f74835d2444)
### Contact Page
![contactpage](https://github.com/user-attachments/assets/f981c7be-962b-4c81-8419-f518b2e62a74)
### Message Sent Page
![MessageSentPage](https://github.com/user-attachments/assets/0f5955ea-2790-414a-ac9b-e5b4065f6e0a)

---

## Functions
### Admin
- Create Admin account and Login.
- Can Add, View, Book
- Can Issue Book (added by Admin) to registered student.
- Can view Issued book with issued date and expiry date.
- Can view Fine (10 rupees for each day after expiry date).
- Can View Students that are registered into system.

### Student
- Create account and Login.
- Can view their issued book only with expiry date and fine(if there any otherwise 0)
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
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```

## Drawbacks/LoopHoles
- Anyone can be Admin.

