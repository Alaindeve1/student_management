# Midterm Project: Student & Course Management App

This Android application is a comprehensive management system for students, courses, and enrollments, built as a midterm project. It features a clean, modern user interface and leverages a local SQLite database for persistent data storage.

---

## ✨ Features

- **Student Management**: Perform full CRUD (Create, Read, Update, Delete) operations for student records.
- **Course Management**: Perform full CRUD operations for courses, including details like course code and credits.
- **Enrollment System**: Seamlessly enroll and unenroll students in various courses.
- **View Enrollments**: A dedicated screen to view all courses a specific student is enrolled in.
- **CSV Export**: Export a student's list of enrolled courses to a CSV file for reporting and external use.
- **Local Data Persistence**: All data is stored locally in a robust SQLite database.
- **Modern UI**: The app uses Material Design components for a clean, intuitive, and responsive user experience.

---

## 🛠️ Project Structure

The project follows modern Android development architecture patterns to ensure a scalable and maintainable codebase.

- `java/com/example/ndizeyealain26442_midterm/`
    - **`activities`**: Contains the UI controllers (Activities) for each screen of the application (e.g., `MainActivity`, `StudentActivity`).
    - **`adapter`**: Holds custom adapters, like `EnrollmentAdapter`, which bind data to complex UI components like `ListView`s.
    - **`dao`**: The Data Access Object package. `MyDbHelper.java` resides here, managing all SQLite database operations, from table creation to CRUD queries.
    - **`model`**: Contains the Plain Old Java Objects (POJOs) like `Student` and `Course` that represent the application's data structure.
    - **`utils`**: A package for reusable utility classes, such as the `CsvExporter`.

- `res/`
    - **`layout`**: XML files defining the UI for each activity.
    - **`values`**: Contains resource files for strings, colors, and application themes.

---

## 🚀 Getting Started

1.  Clone the repository.
2.  Open the project in Android Studio.
3.  Allow Gradle to sync and build the project.
4.  Run the application on an Android emulator or a physical device.
