# 🎥 Virtual Event Management System

A web-based **Virtual Event Management System** developed using Laravel and modern frontend technologies. The project aims to provide a platform for managing virtual event-related activities through a web application.

## 📌 Project Overview

The Virtual Event Management System is designed to simplify the process of organizing and managing virtual events. It is developed using the Laravel framework, with frontend technologies integrated to create a responsive and interactive user experience.

This project demonstrates practical application of web development concepts, backend development, database management, and modern frontend tooling.

## 🛠️ Technologies Used

### Backend
- **PHP** – Server-side programming language
- **Laravel 9** – PHP web application framework
- **MySQL** – Database (configure according to your environment)

### Frontend
- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Alpine.js
- Vite

### Additional Packages
- Laravel Sanctum
- Spatie Laravel Permission
- Stripe PHP SDK
- Axios

## ✨ Key Project Areas

- Virtual event management
- Web-based application development
- Backend development using Laravel
- Database integration
- Frontend and backend integration
- Authentication and authorization support

*Note: Update this section with the specific features implemented in your application.*

## 📂 Project Structure

```text
Virtual-Event-Management/
│
├── app/
│   ├── Http/
│   ├── Models/
│   └── Providers/
│
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   ├── factories/
│   └── seeders/
│
├── public/
├── resources/
│   ├── css/
│   ├── js/
│   └── views/
│
├── routes/
├── storage/
├── tests/
│
├── .env.example
├── artisan
├── composer.json
├── package.json
├── tailwind.config.js
└── vite.config.js
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### Prerequisites

Make sure you have installed:

- PHP 8.0.2 or later
- Composer
- Node.js and npm
- MySQL or another supported database
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/gsimon1720/Virtual-Event-Management.git
```

### 2. Navigate to the Project Directory

```bash
cd Virtual-Event-Management
```

### 3. Install PHP Dependencies

```bash
composer install
```

### 4. Install Frontend Dependencies

```bash
npm install
```

### 5. Configure Environment Variables

Create your environment configuration file:

```bash
cp .env.example .env
```

Configure your database credentials in the `.env` file:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
```

Update the values according to your local database configuration.

### 6. Generate Application Key

```bash
php artisan key:generate
```

### 7. Run Database Migrations

```bash
php artisan migrate
```

### 8. Build Frontend Assets

For development:

```bash
npm run dev
```

Alternatively, build production assets:

```bash
npm run build
```

### 9. Start the Laravel Development Server

```bash
php artisan serve
```

Open your browser and visit:

```text
http://127.0.0.1:8000
```

## 🧪 Testing

Run the Laravel test suite using:

```bash
php artisan test
```

## 🔐 Environment Variables

Do not upload your `.env` file or expose sensitive credentials.

Keep API keys, database credentials, and other secrets in your local environment configuration.

## 🚀 Future Improvements

- Enhance virtual event management functionalities.
- Improve user experience and responsive design.
- Expand event-related workflows.
- Improve application security.
- Add additional features based on user requirements.

## 👨‍💻 Author

**Gavesh Fernando**

Software Engineering Undergraduate

- GitHub: [@gsimon1720](https://github.com/gsimon1720)
- Project Repository: [Virtual Event Management System](https://github.com/gsimon1720/Virtual-Event-Management)

## 📄 License

This project is distributed under the MIT License, as specified in the project configuration.
