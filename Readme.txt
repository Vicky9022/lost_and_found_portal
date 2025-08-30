# Lost & Found Portal

A web-based portal built with **PHP** and **MySQL** that helps users report and track lost or found items. 
The application provides an easy way to connect item owners with finders, improving the chances of recovery.

---

## 🚀 Features
- User registration & login (secure authentication).
- Report lost items with details (name, description, location, date, category, image).
- Report found items with similar details.
- Admin panel to manage users and item reports.
- Search and filter items by category, location, or date.
- Responsive design for mobile and desktop users.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** PHP (Core PHP)  
- **Database:** MySQL  
- **Server:** Apache (XAMPP/LAMP/WAMP)  

---

## 📂 Project Structure
```
Lost-Found-Portal/
│-- assets/           # CSS, JS, and images
│-- includes/         # Reusable PHP components (header, footer, DB config)
│-- modules/          # Core functionality (Lost, Found, Authentication)
│-- admin/            # Admin dashboard and management
│-- index.php         # Home page
│-- login.php         # User login
│-- register.php      # User registration
│-- report_lost.php   # Form for lost items
│-- report_found.php  # Form for found items
│-- README.md         # Documentation
```

---

## ⚙️ Installation & Setup

### Prerequisites
- Install [XAMPP](https://www.apachefriends.org/) or any PHP + MySQL server.  
- PHP version **7.2+** recommended.  

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/lost-found-portal.git
   ```

2. Move project to your web server root:
   - For XAMPP → `htdocs/`
   - For WAMP → `www/`

3. Import the database:
   - Open **phpMyAdmin** → Create a new database `lostfound_db`
   - Import the SQL file located in `/database/lostfound.sql`

4. Configure database connection:  
   - Edit `includes/config.php`  
   - Update:
     ```php
     $host = "localhost";
     $user = "root";
     $password = "";
     $dbname = "lostfound_db";
     ```

5. Run the project in browser:
   ```
   http://localhost/lost-found-portal
   ```

---
## 👨‍💻 Contributors
- vikas Rathod – Developer  
Gaurav Jadhav – Developer 
Aditya patil – Developer 
Rohit andani – Developer 

---

## 📜 License
This project is licensed under the MIT License – feel free to use and modify it.  
