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

---

## 🚀 How to Run

### 1. Make the script executable:

```bash
chmod +x main.sh

### 2. Run the script
./main.sh

🛡️ Role-Based Login
Admin and student roles are distinguished in the users.txt file.

Format per line: ID,username,password,role

Admin credentials are hardcoded or preloaded.

Students can sign up (admin adds them) and then log in.

🤝 Contributions
Feel free to fork and submit pull requests. Open to improvements!

---

### 🔄 Summary

- If you already have the File Structure section, just **paste the new sections directly below it** in the same file.
- Don't worry about GitHub Pages, YAML, or other config files unless you're doing CI/CD or deployment — for now, the README is just a Markdown `.md` file meant to document your script.


