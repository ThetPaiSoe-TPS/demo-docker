# Task Manager

A full-stack task management application built with **React** (frontend) and **Laravel 12** (backend), containerized with **Docker**.


![Image](https://github.com/user-attachments/assets/0b26ba89-6750-4aec-ac16-6d1a4079f465)
[Uploading "docker-demo.mp4"


](https://github.com/user-attachments/assets/0099d648-0044-43ae-aaef-74fd62acdfc1)
---

## Features

- Task CRUD (Create, Read, Update, Delete) via REST API
- Modern React frontend (Create React App)
- Laravel 12 backend API
- Dockerized for easy local development
- MySQL database (via Docker Compose)

---

## Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed

---

## Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/yourusername/task-manager.git
cd task-manager
```

### 2. Environment Setup

- Copy `.env.example` to `.env` in `laravel-12-rest-api` and adjust DB credentials if needed.

### 3. Build and Run with Docker Compose

From the project root, run:

```sh
docker compose up --build
```

- The **backend API** will be available at [http://localhost:8000](http://localhost:8000)
- The **frontend** will be available at [http://localhost:3000](http://localhost:3000) (if using the provided frontend Docker Compose)

### 4. Database

- MySQL runs in a Docker container.
- Default credentials are set in `docker-compose.yml` and `.env`.

---

## Project Structure

```
task-manager/
│
├── frontend/                # React app
│   ├── Dockerfile
│   └── ...
│
├── laravel-12-rest-api/     # Laravel backend
│   ├── Dockerfile
│   ├── docker-compose.yml
│   └── ...
│
└── README.md
```

---

## Useful Commands

### Laravel

- Install dependencies: `composer install`
- Run migrations: `php artisan migrate`
- Run tests: `php artisan test`

### React

- Install dependencies: `npm install`
- Start dev server: `npm start`
- Build for production: `npm run build`

---

## License

MIT

---

## Author
Thet Pai Soe
