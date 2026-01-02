<p align="center">
<a href="https://laravel.com" target="_blank">
<img src="https://github.com/Ryandra-TI01/Aplikasi-HealthTrack/blob/main/public/images/LOGO%20-%20HealthTrack%202.png?raw=true" alt="Logo HealthTrack">
</a>
</p>

---

# HealthTrack

HealthTrack is a web-based health monitoring application that helps users manage medical appointments, record health conditions, and interact through a community forum. Developed using Laravel and the Filament Admin Panel.

---

## Key Features

- **User Authentication**
- **Medical Schedule Management & Reminders**
- **Health Condition Recording & Monitoring**
(Body temperature, blood pressure, oxygen saturation, weight)
- **PDF Export of Health Monitoring Results**
- **Community Discussion & Sharing Group**
- **Management of User Feedback, Suggestions, and Messages**
- **Application Issue & Bug Reporting**
- **User Data Statistics for Admins**
- **User Activity Log**
- **Application Performance Monitoring**

---

## Technology

- **Laravel 12**
- **Filament Admin Panel**
- **Spatie Activity Log**
- **z3d0x/filament-logger**
- **Firebase Cloud Messaging**
- **Laravel DomPDF**
- **PostgreSQL / MySQL**

---

## Installation

```bash
git clone https://github.com/username/healthtrack.git
healthtrack cd

composer install
cp .env.example .env
php artisan key:generate

# Customize the database connection in the .env file
php artisan migrate --seed

composer run dev
