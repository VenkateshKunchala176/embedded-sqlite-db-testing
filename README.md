# 🗃️ Embedded SQLite DB Testing with Java

## 📌 Project Summary
A lightweight test automation project for embedded SQLite databases using Java and JDBC. It validates schema creation and CRUD operations through simple automation scripts.

## 🔧 Tech Stack
- Java
- JDBC
- SQLite (embedded DB)
- JUnit (optional, for test orchestration)

## 🧪 Features
- Automated DB initialization and schema validation
- Insert, read, update, delete operation checks
- Java-based test runner using JDBC

## 🚀 How to Run
1. Ensure `sqlite-jdbc` dependency is added
2. Compile and run:
   ```bash
   javac -cp .:sqlite-jdbc-3.36.0.3.jar src/main/java/db/DatabaseManager.java
   java -cp .:sqlite-jdbc-3.36.0.3.jar db.DatabaseManager
   ```

## 📂 Folder Structure
```
src/main/java/db        # DB connection + logic
src/test/java/tests     # Automation test scripts
```
