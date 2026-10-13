# Visitor Tracker System

A web application to register visitors and view their records, built with Java, Spring Boot MVC and MySQL.

## Features

- Register a new visitor entry (<<FILL: fields, e.g. name, phone, purpose, host, in-time>>)
- View and retrieve stored visitor records (<<FILL: e.g. list all, search by name/date>>)
- <<FILL: any other feature you built, e.g. check-out time, edit/delete. Delete this line if none>>

## Tech Stack

| Layer | Technology |
|---|---|
| Language | Java |
| Framework | Spring Boot (MVC) |
| Database | MySQL |
| View | <<FILL: e.g. Thymeleaf / JSP / HTML + CSS>> |
| Build tool | <<FILL: Maven or Gradle>> |

## Project Structure

The code is organised in layers:

- `controller` - handles web requests and returns views
- `service` - business logic
- `repository` / DAO - database access with MySQL
- `model` / entity - visitor data class

<<FILL: check these package names match your project and edit them>>

## How to Run

1. Install Java <<FILL: version>>, Maven/Gradle and MySQL.
2. Clone the repository:
   ```
   git clone <<FILL: your repo URL>>
   cd <<FILL: project folder>>
   ```
3. Create the database in MySQL:
   ```
   CREATE DATABASE <<FILL: database name>>;
   ```
4. Update `src/main/resources/application.properties` with your MySQL URL, username and password.
5. Run the application:
   ```
   mvn spring-boot:run
   ```
   <<FILL: use `./gradlew bootRun` if you use Gradle>>
6. Open `http://localhost:8080` in your browser.

## Testing

Backend flow was tested and debugged across the controller, service and database layers.

## Author

Himaja Pogiri
GitHub: [Himaja-23110](https://github.com/Himaja-23110)
