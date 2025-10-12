<h1 align="center">🛍️ Ardina Store</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-developing-blue?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/ardinastore/Ardina_Store?style=for-the-badge" />
  <img src="https://img.shields.io/github/languages/top/ardinastore/Ardina_Store?style=for-the-badge" />
</p>

<p align="center">
  <b>A modern e-commerce web application</b><br />
  Built with ❤️ using Laravel (Back-End) and React (Front-End)
</p>

---

## 📸 Preview

<p align="center">
  <img src="https://via.placeholder.com/1000x500.png?text=Homepage+Preview" alt="Homepage Screenshot" />
</p>

---

## 🚀 Features

✅ Full-featured Product Catalog  
✅ Shopping Cart & Checkout  
✅ User Authentication (Login/Register)  
✅ Admin Dashboard (Manage Products, Orders, Users)  
✅ RESTful API Integration  
✅ Payment Gateway Ready  
✅ Mobile Responsive Design  
✅ Dark Mode Support 🌙  

---

## 🛠️ Tech Stack

**Frontend:**  
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" /> 
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white" />

**Backend:**  
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white" />

**Database:**  
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" />

**Tools:**  
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white" />

---

## ⚙️ Installation Guide

```bash
# 1. Clone the repository
git clone https://github.com/ardinastore/Ardina_Store.git
cd Ardina_Store

# 2. Install backend dependencies
composer install

# 3. Setup environment
cp .env.example .env
php artisan key:generate

# 4. Run migrations
php artisan migrate --seed

# 5. Start Laravel server
php artisan serve
