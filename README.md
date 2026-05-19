# 📚 Library Management System

A comprehensive, role-based Library Management Web Application built to streamline book tracking, dynamic fine calculations, and member issuance records. The system features separate digital dashboards for both Administrators and Registered Students.

---

## 🛠️ Tech Stack & Badges
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

---

## 📸 Project Screenshots

### 🖥️ 1. Admin Control Dashboard
The main command portal where the administrator logs in and accesses all multi-tier verification options.
![adminhomepage](https://github.com/user-attachments/assets/9b348526-a93a-4472-969e-59b29105390a)

### 👥 2. Registered Student Database View
The central panel for administrative views to monitor all student profiles actively synchronized within the system registry.
![viewstudentpage](https://github.com/user-attachments/assets/d073b134-1fd1-4b34-add7-fce5921cad4b)

### 📖 3. Available Books Catalog
A structured relational data inventory display presenting currently available resources, titles, and item metadata.
![availablebook](https://github.com/user-attachments/assets/bc5c3cdf-e1ba-4ee8-a5c6-0302ffb57f34)

### 📧 4. Contact Us Portal
A communication module letting guests or members relay inquiries via real-time backend automated message routers.
![contactpage](https://github.com/user-attachments/assets/ba9839e3-0ff8-443a-81a0-063843bc7926)

### ✅ 5. Dispatch / Message Sent Status
Success state tracking portal displaying verification flags when communication protocols dispatch successfully.
![MessageSentPage](https://github.com/user-attachments/assets/ba483ba3-8435-414f-b67e-2f1b80d51fe2)

---

## ⚙️ Core System Functions

### 👑 Admin Management
- **Security Check:** Dedicated registration, verification parameters, and operational login authentication.
- **Inventory Operations:** Add, View, Track, and Modify complete book stocks inside the repository.
- **Issuance Trackers:** Allocate cataloged elements directly to actively registered students.
- **Timeline Logs:** Track checkout dates alongside absolute expiration/due date indicators.
- **Dynamic Fine Engine:** Automatically logs a penalty metric tracking ₹10/day accumulated after a pass due stamp.
- **Account Controls:** Direct diagnostic supervision to scan and view all registered users.

### 🎓 Student Framework
- **Self Service Profile:** Dedicated credentials initialization engine along with individual sign-in paths.
- **Personal Log Panel:** Single dashboard access targeting ONLY items checked out by the user.
- **Financial Status Flags:** Live views showing expiry benchmarks, active due periods, and precise live fine totals (Defaults to 0).

---

## 🚀 Local Deployment Setup

Follow these streamlined instructions to clone, migrate, and boot up this portal on a local interface terminal:

### Prerequisites
> [!IMPORTANT]
> Install **Python (v3.7.6 or newer)** on your target architecture. Make sure to check the **"Add Python to PATH"** checkbox during the primary execution process.

### Step 1: Install Dependencies
Open your shell environment inside the directory and run:
```bash
python -m pip install -r requirements.txt
