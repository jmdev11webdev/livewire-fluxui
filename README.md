---

````md
# 🚀 Laravel Projects Collection

A curated repository of **Laravel projects** built to demonstrate **progressive learning and real-world application development** — from **basic authentication using Laravel Breeze**, to **full-featured applications with Jetstream**, and eventually **advanced Laravel system implementations**.

This repository serves both as a **learning archive** and a **portfolio showcase**, developed using **WSL2 with Ubuntu** for an efficient, Linux-native workflow on Windows.

---

## 🎯 Purpose of This Repository

This repository is created to:

- Practice Laravel fundamentals and best practices
- Apply official Laravel starter kits (**Breeze & Jetstream**)
- Progress toward **advanced Laravel features**
- Build **scalable, maintainable, and production-ready systems**
- Document growth from beginner to advanced Laravel development

Each project reflects a **specific stage of Laravel mastery**.

---

## 📈 Project Progression

### 🟢 Beginner Level
- Laravel installation & project structure
- Routing, controllers, views
- Blade templating
- Form handling & validation
- Authentication using **Laravel Breeze**

### 🔵 Intermediate Level
- Authentication & authorization
- Role-based access control
- Jetstream features (Teams, Profile Management)
- Database relationships & migrations
- CRUD systems
- RESTful controllers

### 🔴 Advanced Level
- Modular architecture
- Inertia.js / Livewire integrations
- API development
- Notifications & queues
- Activity logs & auditing
- Performance optimization
- Security best practices

---

## 📁 Repository Structure

```text
laravel-projects/
│
├── breeze-auth/
│   └── Basic authentication using Laravel Breeze
│
├── jetstream-app/
│   └── Advanced auth & team features using Jetstream
│
├── landseek/
│   └── Real-world Laravel system (property listing & messaging)
│
├── experimental/
│   └── Testing advanced Laravel concepts
│
└── README.md
````

Each folder represents an **independent Laravel project** with its own configuration.

---

## 🧑‍💻 Development Environment

This repository is developed using:

* **Windows + WSL2**
* **Ubuntu 24.04 LTS**
* **PHP 8+**
* **Composer**
* **Laravel Framework**
* **MySQL / MariaDB**
* **Node.js & npm**
* **Visual Studio Code (WSL Extension)**

### ⚡ Why WSL2 + Ubuntu?

* Linux-native performance on Windows
* Faster Composer & npm operations
* Cleaner Laravel tooling experience
* Seamless Git & SSH integration
* Ideal for production-like environments

---

## 🚀 Getting Started (WSL2 + Ubuntu)

### 1️⃣ Clone the repository

```bash
git clone git@github.com:your-username/laravel-projects.git
cd laravel-projects
```

### 2️⃣ Open in VS Code (WSL)

```bash
code .
```

Make sure **Remote - WSL** extension is installed.

---

### 3️⃣ Run a project

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

## 📌 Notes

* Each project has its own `.env` configuration
* Database credentials are not committed
* Some projects may require additional setup (documented per folder)
* Designed for **learning, experimentation, and portfolio use**

---

## 🧪 Future Plans

* Add more real-world Laravel systems
* API-first Laravel applications
* Microservice-oriented Laravel structure
* Improved test coverage
* Deployment-ready configurations

---

## 🤝 Contributions

This repository is primarily for **learning and showcasing progress**, but contributions are welcome.

You may:

* Suggest improvements
* Add refactoring ideas
* Share Laravel best practices

---

## 📄 License

This repository is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

**JMDevStack**
Aspiring Full Stack Web Developer

* GitHub: [https://github.com/your-username](https://github.com/your-username)
* Portfolio: *(optional)*

---

⭐ If this repository helps you, consider giving it a star!
