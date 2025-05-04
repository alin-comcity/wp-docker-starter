# WP Docker Starter 🐳📝

A simple, production-ready WordPress + Docker starter template.

A minimal and ready-to-use Docker-based WordPress development environment. This setup includes WordPress, MySQL, and phpMyAdmin, making it ideal for local development, testing, or quick prototyping.

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

DB Host: db
DB User: user
DB Password: password
DB Name: WordPress

### 5. Stop & Clean

docker-compose down -v

# Requirements

Docker

Docker Compose

# Customization

Modify docker-compose.yml for custom port, DB config, etc.

Add themes/plugins inside html/wp-content/

To persist DB data, Docker volumes are already configured.

# Created By

Md. Rezwan Saki Alin
https://alinsworld.com/

# Created Date

04-May-2025

# License

MIT License
