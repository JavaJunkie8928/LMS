<<<<<<< HEAD
# Library Management System

## screenshots
### Admin login Page
![adminhomepage](https://github.com/user-attachments/assets/9b348526-a93a-4472-969e-59b29105390a)
### Student Page
![viewstudentpage](https://github.com/user-attachments/assets/d073b134-1fd1-4b34-add7-fce5921cad4b)
### Available Book
![availablebook](https://github.com/user-attachments/assets/bc5c3cdf-e1ba-4ee8-a5c6-0302ffb57f34)
### Contact Page
![contactpage](https://github.com/user-attachments/assets/ba9839e3-0ff8-443a-81a0-063843bc7926)
### Message Sent Page
![MessageSentPage](https://github.com/user-attachments/assets/ba483ba3-8435-414f-b67e-2f1b80d51fe2)

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

