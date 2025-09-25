# 🛠️ Online Service Management System (OSMS)

The **Online Service Management System (OSMS)** is a web-based platform developed using **PHP**, **XAMPP**, and **MySQL**.  
It streamlines the process of handling technical service requests by allowing customers to submit complaints online, while administrators can manage, assign, and resolve them efficiently.  

This project is especially useful for organizations that provide **technical support or repair services**, ensuring a smoother communication channel between customers, admin staff, and technical teams.

---

## 📽️ Project Demo
[👉 Watch the Demo Video](PUT-YOUR-VIDEO-LINK-HERE)

---

## 🎯 Project Objectives
- Provide a **centralized platform** for handling service requests.
- Allow customers to **raise complaints** anytime, anywhere.
- Enable administrators to **assign technicians** and monitor their progress.
- Keep customers informed with **real-time complaint status**.
- Generate and print **service bills** for completed tasks.
- Maintain an organized **digital record** of all service-related activities.

---

## ✨ Features

### 👩‍💻 User Side
- **Register/Login:** Customers can create an account and log in securely.  
- **Submit Complaints:** Raise new service complaints with issue details.  
- **Track Complaints:** View the current status (Pending, Assigned, Completed).  
- **Download/Print Bills:** Once resolved, users can generate and print their service bill.  

### 🧑‍💼 Admin Side
- **Admin Login:** Secure access to admin dashboard.  
- **Complaint Management:** View all submitted complaints in one place.  
- **Assign Technicians:** Assign complaints to specific technical staff.  
- **Update Status:** Mark complaints as Pending, Assigned, or Completed.  
- **Bill Management:** Generate, review, and finalize customer bills.  
- **Reports:** View history of service requests for records and analysis.  

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP (runs on XAMPP)  
- **Database:** MySQL  
- **Server:** Apache (via XAMPP)  

---

## ⚙️ Installation & Setup Guide

Follow these steps to set up the project locally on your machine:

1. **Install XAMPP**  
   Download and install [XAMPP](https://www.apachefriends.org/index.html). Make sure **Apache** and **MySQL** services are running.

2. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/osms.git

Create the Database

Open phpMyAdmin
.

Create a new database (e.g., osms_db).

Import the provided .sql file from the project directory into this database.

Configure Database Connection

Locate the config.php or similar configuration file in the project.

Update database credentials if needed:

$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "osms_db";


Run the Project

Start Apache and MySQL from the XAMPP Control Panel.

Open your browser and visit:

http://localhost/osms/

🧑‍💻 Usage Workflow
For Customers:

Register and log in.

Submit a new complaint describing the issue.

Check complaint status anytime.

Download or print the final service bill.

For Admin:

Log in using admin credentials.

View all pending complaints.

Assign complaints to technicians.

Update status when tasks are completed.

Generate service bills for users.

📸 Screenshots:
<img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/8dd31cd5-1091-4a3f-a61b-ba5d657c0d3a" />
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/4b91dbc6-6795-4a1b-9005-8ffb3fd5a9c9" />
<img width="1920" height="1080" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/ab87f2f1-1d67-48ce-a123-4b5d8b9b6795" />
<img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/106706f8-b26b-416e-8c45-f663b13bc660" />
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/b6fc3c3a-0ca8-4615-909b-ec8ae6cace8b" />
<img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/35c46c44-0f2a-42b3-bbbf-17cc5c22aa75" />
<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/1b3369d4-9a9a-47aa-a878-0fba2649373e" />
<img width="1920" height="1080" alt="Screenshot (21)" src="https://github.com/user-attachments/assets/2cf67e1e-e7e5-46be-8c38-d674742204f2" />



