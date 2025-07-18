# 🎓 Student Course Registration System (Linux Shell Script)

A terminal-based student course registration and payment system using Bash scripting. This system simulates course enrollments, payments, and admin/student panel functionalities — all through simple `.txt` files.

---

## ✨ Features

### 👨‍🎓 Student Panel
- Login via username/password
- Enroll in available courses (max credit limit enforced)
- Submit payment (trx ID)
- View enrolled courses (only verified payments shown)
- Drop enrolled courses

### 🛠️ Admin Panel
- Add/Remove Students
- Add/Remove Courses
- View all students and courses
- View all enrollments
- Verify or reject payments (auto-email simulated)

---

## 🗂️ File Structure

student-course-registration/
<│
├── main.sh # Entry point for the system
├── users.txt # Stores user info (id, username, password, role)
├── courses.txt # Stores course info (id, name, price, credit)
├── enrollments.txt # Tracks student enrollments (sid, cid)
├── payments.txt # Stores payment info (sid, cid, trx_id, status)
├── README.md # Project documentation>

---

## 🚀 How to Run

### 1. Make the script executable:

```bash
chmod +x main.sh

