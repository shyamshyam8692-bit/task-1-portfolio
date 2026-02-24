# Task 1 - Full Stack Portfolio

## 👤 Developer
Shyam Krishna Sasthry  
CSE Student - GITAM University  

---

## 📌 Project Description
This is a Full Stack Portfolio Website developed as Task 1 of the internship.

The project includes:

- Frontend using HTML, CSS, and JavaScript
- Backend using PHP
- Database using MySQL
- Contact form integrated with database storage

---

## 💻 Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- MySQL
- XAMPP

---

## 📂 Project Structure

index.html  
style.css  
script.js  
contact.php  
config.php  

---

## 🗄 Database Setup

1. Create a database named:
   `shyam_portfolio_db`

2. Create table:

```sql
CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    message TEXT
);
