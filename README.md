# Learnix-s-Apps
e-learning Information System
It is an online learning based on CodeIgniter 3 Framework for schools/madrasas with discussion, assignment, schedule, and class management features.

## 🚀 Main Features

- **Admin Dashboard**: Teacher, student, class, and schedule management
- Teacher Dashboard**: Upload materials, create assignments, and manage classes
- **Student Dashboard**: Access materials, submit assignments, and view schedules
- Discussion System**: Discussion forum between students and teachers
- File Management**: Upload and download learning materials
- Notification System**: Notification of assignments and announcements

## 📋 System Requirements

- PHP 8.0 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- CodeIgniter 3.x

## 🛠️ Installation

1. **Clone repository**
 ```bash
 [git clone https://github.com/Aryaa0112-A/Learnix-s-Apps.git]
 ```

2. **Database Configuration**
   - Create a new MySQL database
   - Import the file `database/technology-pillar-nation.sql`
   - Copy `application/config/database.php.example` to `application/config/database.php`
   - Customize the database configuration in the file

3. **Application Configuration**
   - Copy `application/config/config.php.example` to `application/config/config.php`
   - Customize base_url and other configurations

4. **Set Permissions**
 ``bash
 chmod 755 application/cache/
 chmod 755 application/logs/
 chmod 755 uploads/
 ``

5. **Access Application**
   - Open a browser and access `http://localhost/`



## 📁 Struktur Project

```
Learnixs/
├── application/
│ ├── controllers/ # Controller aplikasi
│ ├── models/ # Model database
│ ├── views/ # View/template
│ └── config/ # Konfigurasi
├── assets/ # Asset statis (CSS, JS, Images)
├── system/ # Core CodeIgniter
├── uploads/ # File upload
└── database/ # File database
````

## 🔧── Konfigurasi

### Database
Edit file `application/config/database.php`:
```php
$db['default'] = array(
 'hostname' => 'localhost',
 'username' => 'your_username',
 'password' => 'your_password',
 'database' => 'your_database',
 'dbdriver' => 'mysqli',
 'dbprefix' => '',
 'pconnect' => FALSE,
 'db_debug' => (ENVIRONMENT ! == 'production'),
 'cache_on' => FALSE,
 'cachedir' => '',
 'char_set' => 'utf8',
 'dbcollat' => 'utf8_general_ci',
 'swap_pre' => '',
 'encrypt' => FALSE,
 'compress' => FALSE,
 'stricton' => FALSE,
 'failover' => array(),
 'save_queries' => TRUE
);
````

## 🚀 Deployment

1. Upload semua file ke server web
2. Set permission folder yang diperlukan
3. Import database
4. Konfigurasi database dan aplikasi
5. Akses aplikasi melalui domain

## 📝 Changelog

### v1.0.0
- Fitur dasar sistem pembelajaran
- Dashboard admin, guru, dan siswa
- Sistem diskusi dan tugas
- Manajemen file upload

## 🤝 Contributions

1. Fork project
2. Create a new feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m ‘Add some AmazingFeature’`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Create Pull Request

## 👨‍💻 Developer aryadillah.vercel.app

Developed with ❤️ for the advancement of Indonesian education.
Member of **The Debuggers** Team

---

**Learnix's** - Trusted Online Learning System

