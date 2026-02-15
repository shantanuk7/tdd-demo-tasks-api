# Learning Test Driven Development in Spring Boot
- This is a simple task management API project
- The focus is on learning Test driven development practices in REST API project in Spring boot

---

## Getting Started

### Prerequisites
* **Java:** JDK 17 or higher
* **Database:** PostgreSQL
* **Build Tool:** Gradle

### Database Setup

1. Create a database named `tasks-db` in your PostgreSQL instance.
2. The application requires an environment variable for the database password to run securely.

**Set the environment variable:**

* **macOS/Linux:** `export DB_PASSWORD=your_password`
* **Windows (PowerShell):** `$env:DB_PASSWORD="your_password"`

---

## Installation & Run

1. **Clone the repository:**
```bash
git clone https://github.com/shantanuk7/tdd-demo-tasks-api.git
cd tdd-demo-task-api
```

2. **Build the project:**
```bash
./gradlew build
```


3. **Run the app:**
```bash
./gradlew bootRun
```

---

## Testing

This project follows the **TDD** workflow. We prioritize writing unit tests before implementation to ensure high code coverage and reliability.

**To run all tests:**

```bash
./gradlew test
```

---

## Dependencies

* **Spring Web:** For building RESTful endpoints.
* **Spring Data JPA:** For database communication.
* **PostgreSQL Driver:** To connect to the SQL database.
* **Lombok:** To minimize boilerplate code.

---