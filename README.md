<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

# Offline Attendance App

A powerful, offline-first attendance management application built with Flutter, designed to be the perfect assistant for any Class Representative. This app works flawlessly without any internet connection, ensuring reliability and ease of use.


## Key Features

* **100% Offline:** All data is stored locally on the device. No internet required.
* **Full Student Management:**
    * Add, Edit, and Delete students manually.
    * Bulk import the entire student list from a CSV file.
* **Multi-Session Support:** Take attendance for multiple classes, labs, or events on the same day without overwriting data.
* **Quick Actions:**
    * Mark all students as 'Present' or 'Absent' with a single tap.
* **Smart CSV Export:**
    * Export attendance reports with multiple options:
        * Latest Session
        * Today's Sessions
        * This Week / This Month
        * Full History
* **Modern & Responsive UI:**
    * Clean, intuitive interface built with **Material 3**.
    * A beautiful dashboard with live stats.
    * Automatic **Dark Mode** support.
    * Smooth and subtle animations for a premium feel.
* **Personalized:**
    * Custom App Icon.
    * Developer credit footer with a link to your profile.


## Tech Stack

* **Framework:** Flutter
* **Language:** Dart
* **Database:** `sqflite` (for local offline storage)
* **State Management:** `setState`
* **Key Packages:**
    * `file_picker`: For importing CSV files.
    * `csv`: For parsing CSV data.
    * `permission_handler`: For handling storage permissions.
    * `share_plus`: For sharing exported reports.
    * `flutter_staggered_animations`: For list animations.
    * `url_launcher`: For opening external links.
    * `flutter_launcher_icons`: For generating the app icon.

## Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repo**
    ```sh
    git clone https://github.com/ashankgupta/attendance_app.git
    ```
2.  **Navigate to the project directory**
    ```sh
    cd attendance_app
    ```
3.  **Install dependencies**
    ```sh
    flutter pub get
    ```
4.  **Run the app**
    ```sh
    flutter run
    ```

## Screenshots
<p align="center">
  <img src="assets/home.png" width="260" />  
  <img src="assets/add_student.png" width="260" />
  <img src="assets/mark_attendance.png" width="260" />
</p>

## License

This project is licensed under MIT License.
