# Laravel Projects

A curated collection of Laravel projects showcasing **progressive learning and real-world application development** — starting from basic authentication with **Laravel Breeze**, moving to more advanced features with **Laravel Jetstream**, and evolving into **advanced, production-style Laravel systems**.

This repository also serves as a **portfolio and learning archive**, developed using **WSL2 with Ubuntu** for a fast, stable, and Linux-native development workflow on Windows.

---

## Purpose of This Repository

The main goals of this repository are to:

* Learn and apply Laravel fundamentals and best practices
* Implement official Laravel starter kits (Breeze and Jetstream)
* Gradually move toward advanced Laravel architectures
* Build scalable, maintainable, and clean Laravel applications
* Track personal growth from beginner to advanced Laravel development

Each project represents a **specific stage of Laravel proficiency**.

---

## Project Levels

### Beginner Projects

* Laravel installation and configuration
* Routing, controllers, and Blade templates
* Form validation and request handling
* Authentication using Laravel Breeze

### Intermediate Projects

* Authentication and authorization
* Role-based access control
* Jetstream features (profile management, teams)
* Database relationships and migrations
* CRUD systems and RESTful controllers

### Advanced Projects

* Modular and scalable architecture
* Inertia.js or Livewire integration
* API-based Laravel applications
* Notifications, queues, and background jobs
* Activity logs and auditing
* Performance and security optimizations

---

## Repository Structure

```text
laravel-projects/
│
├── breeze-auth/
│   └── Basic authentication using Laravel Breeze
│
├── jetstream-app/
│   └── Advanced authentication and team features using Laravel Jetstream
│
├── advanced-projects/
│   └── Full-featured and production-style Laravel systems
│
└── README.md
```

Each folder is an **independent Laravel project** with its own configuration and setup.

---

## Development Environment

This repository is developed using:

* Windows with WSL2
* Ubuntu 24.04 LTS
* PHP 8 or later
* Composer
* Laravel Framework
* MySQL or MariaDB
* Node.js and npm
* Visual Studio Code with Remote - WSL extension

### Why WSL2 with Ubuntu?

* Linux-native performance without dual booting
* Faster Composer and npm operations
* Better compatibility with Laravel tooling
* Cleaner Git and SSH workflows
* Closer to real production server environments

---

## Getting Started

### Clone the Repository

```bash
git clone git@github.com:your-username/laravel-projects.git
cd laravel-projects
```

### Open in VS Code (WSL)

```bash
code .
```

Make sure the **Remote - WSL** extension is installed.

---

### Run Any Project

```bash
cd breeze-auth   # or any project folder
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm run dev
php artisan serve
```

---

## Notes

* Each project uses its own `.env` file
* Database credentials are never committed
* Additional setup steps may exist inside individual project folders
* Intended for learning, experimentation, and portfolio demonstration

---

## Future Plans

* Add more real-world Laravel applications
* API-first and backend-focused Laravel projects
* Improved testing and code quality
* Deployment-ready project configurations

---

## License

This repository is open-source and available under the MIT License.

---

## Author

JMDevStack
Aspiring Full Stack Web Developer

GitHub: [https://github.com/your-username](https://github.com/your-username)
