# Mars Mission CRUD Application 🚀

A simple full-stack CRUD application to manage space station resources, built with Java Spring Boot, H2 in-memory database, and a lightweight HTML/JS frontend. The app is fully containerized and CI/CD enabled using GitHub Actions.

---

## 🌍 Features

- View, add, update, and delete products
- Each product has a unique `id`, `name`, and `quantity`
- Frontend and backend run together via Docker Compose
- CI/CD pipeline with:
  - Code linting using Checkstyle
  - Unit testing with JUnit
  - Maven build + Docker packaging
  - GitHub Actions automation

---

## 📦 Tech Stack

- **Backend**: Java 21, Spring Boot
- **Database**: H2 (in-memory)
- **Frontend**: HTML, CSS, JavaScript
- **CI/CD**: GitHub Actions
- **Build Tool**: Maven
- **Containerization**: Docker, Docker Compose

---

## 🚀 How to Run the App

### Run everything with Docker Compose

1. **Install Docker** if you don't already have it:  
   https://docs.docker.com/get-docker/

2. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/mars-mission-crud.git
   cd mars-mission-crud
   
3. **Run the entire stack (frontend + backend + database):**
   ```bash
   docker-compose up --build

4. **Open the app in your browser:**

    👉 http://localhost:8080
