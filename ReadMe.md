# WP Docker Starter 🐳📝

A simple, production-ready WordPress + Docker starter template.

A minimal Docker-based WordPress development environment with MySQL and phpMyAdmin. Easy to set up and customize for local development or rapid prototyping.

## 📦 What's Included

- **WordPress** (latest)
- **MySQL** (5.7)
- **phpMyAdmin** (for DB management)

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/alin-comcity/wp-docker-starter.git
cd wp-docker-starter
```

### 2. Move WordPress to HTML Folder

You need to download WordPress and copy everything from the root folder into the 'html' folder.

### 3. Start the containers

docker-compose up -d

### 4. Browse them

WordPress: http://localhost:8000

phpMyAdmin: http://localhost:8080
(Host: db, Username: user, Password: password)

### 5. Stop & Clean

docker-compose down -v

# Created By

Md. Rezwan Saki Alin
https://alinsworld.com/

# Created Date

04-May-2025
