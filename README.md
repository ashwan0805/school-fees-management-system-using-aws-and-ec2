School Management System – Multi-User Dashboard (Admin | Teacher | Student)
This is a PHP-based school management system that supports Admin, Teacher, and Student logins. Each user type has its own dashboard and functionalities. Admins manage records, teachers access their dashboard, and students can log in to view their information.

🚀 Features
👨‍💼 Admin:
Login Authentication

Dashboard with overview

Add, Edit, and View Student Information

Add and View Teacher Information

Insert and View Fee Details

Handle Manual Payments

👩‍🏫 Teacher:
Login Portal

Personalized Dashboard (static or extendable)

Can be expanded to show assigned students or schedule

👨‍🎓 Student:
Login Portal

Personalized Dashboard with student-specific details (like fee status, profile, etc.)

🗂️ File Descriptions
File Name	Description
admin_login.php	Admin login form with credential verification.
admin_dashboard.php	Admin dashboard page with links to manage students, teachers, and fees.
home.php	Admin landing page post-login.
db.php	Shared database connection script.
insert_student.php	Form and logic to insert new student records.
edit_student.php	Allows editing of existing student information.
insert_teacher.php	Form and logic to insert new teacher records.
insert_fee_details.php	Allows the insertion of student fee payment details.
fee_details.php	Displays a list of all student fee details.
manual_payment.php	Manual entry of payments by admin (offline methods).
🧑‍🏫 Teacher-Specific Files
File Name	Description
teacher_login.php	Login form for teacher accounts.
teacher_dashboard.php	Basic teacher dashboard post-login. Can be expanded.
🎓 Student-Specific Files
File Name	Description
student_login.php	Login form for student accounts.
student_dashboard.php	Student dashboard showing personalized details.
🛠️ Technologies Used
PHP (Server-side scripting)

MySQL (Database)

HTML/CSS (Frontend layout)

Sessions (Login state management)

📦 Setup Instructions
Clone or download the project files.

Database Setup:

Create a MySQL database.

Add required tables: admins, students, teachers, fees, etc.

Update db.php with your DB credentials.

Deploy Locally:

Place the project folder in htdocs (XAMPP) or your local server root.

Run localhost/your_project_folder/student_login.php, etc. in a browser.

Accounts Setup:

Manually create entries in the admins, students, and teachers tables for login purposes.

🔐 Access Points
Admin Login: /admin_login.php

Student Login: /student_login.php

Teacher Login: /teacher_login.php

Each login directs to its respective dashboard after successful authentication.

📝 Notes
No third-party frameworks used – this is pure PHP.

User input validation and security can be enhanced (e.g., with prepared statements).

You can build on this to include password hashing, user registration, reports, and messaging features.
