# 🧠 Laravel Headless CMS (API-First)

### 📄 Project Description  
This is a clean and extensible Laravel-based headless CMS. It provides a RESTful API to manage content like blog posts, articles, and pages. Ideal for projects where the backend and frontend are decoupled — use React, Vue, or even mobile apps to consume the content.

## 🚀 Features
- 🧩 Full RESTful CRUD API (posts endpoint)
- 🔐 Laravel validation and clean structure
- 🌐 Use with any frontend: React, Vue, Next.js, etc.
- 📦 Easily extendable to categories, users, media, etc.

## ⚙️ How to Run

### 1. 📥 Clone & Install
```bash
git clone https://github.com/yourusername/laravel-headless-cms.git
cd laravel-headless-cms
composer install
cp .env.example .env
php artisan key:generate
```

### 2. 🗄️ Database Setup
Update `.env` with your DB credentials, then run:
```bash
php artisan migrate
```

### 3. ▶️ Start the App
```bash
php artisan serve
```

API is now available at: [http://localhost:8000/api/posts](http://localhost:8000/api/posts)

## 🔌 Example Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | `/api/posts` | List all posts |
| POST | `/api/posts` | Create a new post |
| GET | `/api/posts/{id}` | Fetch single post |
| PUT | `/api/posts/{id}` | Update post |
| DELETE | `/api/posts/{id}` | Delete post |

## 🧰 Tech Stack
- Laravel 10+
- RESTful API
- MySQL or PostgreSQL
- Vue or React frontend (optional)
