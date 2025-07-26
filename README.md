# 🏨 PHP Hotel Booking System

A simple hotel booking system built using **PHP**, **MySQL**, and **HTML/CSS**. This project allows users to view available hotels and rooms and make bookings.

---

## 🚀 Features

- List available hotels
- View rooms per hotel
- Book a room
- Basic admin panel 
- Simple and clean UI
- Data stored in MySQL database

---

## 🛠️ Technologies Used

- PHP 
- MySQL
- HTML/CSS
- Bootstrap (for styling)

---
## 2. Prerequisites

Before you begin, ensure that you have the following software and tools installed on your machine:

- **XAMPP**: This is a web server package that includes Apache, MySQL, and PHP. You can download it from: https://www.apachefriends.org/index.html  
- **MySQL**: The project uses MySQL for database management. If not using XAMPP’s built-in MySQL, you can download from: https://dev.mysql.com/downloads/installer/.  

Make sure your MySQL root password is ready before proceeding.

## 3. Installation

Follow these steps to install the Hotel Booking System on your machine:

1. Download the project ZIP file from the GitHub repository.

2. Install XAMPP and make sure it's up and running (Apache & MySQL).

3. Extract the project ZIP contents into the `htdocs` folder of your XAMPP installation. It should contain:
   - `hotel_db.sql`
   - A folder named `project` with PHP, CSS, and JS files.

## 4. Configuration

Now, let's configure the database:

1. Open Command Prompt and enter the MySQL shell:
mysql -u root -p

markdown
Copy
Edit

2. Create the database:
CREATE DATABASE hotel_db;

markdown
Copy
Edit

3. Exit:
exit;

r
Copy
Edit

4. Use the full file path of your `hotel_db.sql` (e.g., `D:\xampp\htdocs\hotel_db.sql`).

5. Import the database using:
mysql -u root -p hotel_db < D:\xampp\htdocs\hotel_db.sql

typescript
Copy
Edit

6. Open the file: `htdocs/project/components/connect.php` in any text editor.

7. Find this line:
```php
$db_user_pass = 'dummyname';
Replace 'dummyname' with your own MySQL root password.

5. Usage
Once setup is complete:

Start Apache and MySQL via XAMPP.

Open your browser and go to:

User Interface: http://localhost/project

Admin Panel: http://localhost/project/admin

You can now explore hotel listings, book rooms, and manage bookings.


<img width="569" height="320" alt="image" src="https://github.com/user-attachments/assets/c666aec0-760d-4cd0-9889-7e9a51f50e07" />
<img width="620" height="349" alt="image" src="https://github.com/user-attachments/assets/e732d8d7-b1ca-4367-8f5f-a4a51c1ba910" />
<img width="1057" height="292" alt="image" src="https://github.com/user-attachments/assets/4302fd41-9d1c-4ba2-975f-fd7e2c25af04" />
<img width="1074" height="295" alt="image" src="https://github.com/user-attachments/assets/df718755-7c99-4a60-8d3d-f73acb646634" />
<img width="620" height="349" alt="image" src="https://github.com/user-attachments/assets/edfd5b90-b7b8-4ed6-8c8c-05f6dec2e711" />
<img width="1035" height="280" alt="image" src="https://github.com/user-attachments/assets/87e3f99f-de65-4d8b-8e17-eb48f6bbc304" />







