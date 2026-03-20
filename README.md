# Online Examination Website 📝

A robust, full-stack web application designed for conducting online quizzes and examinations. This platform provides a seamless interface for students to take tests and an administrative dashboard for educators to manage content, track results, and monitor student performance.

---

## 🌟 Key Features

* **Dual Portal System:** Separate interfaces for **Students** (Examination) and **Admins** (Management).
* **Real-time Quiz Engine:** Dynamic question loading with automatic scoring and instant result generation.
* **Admin Dashboard:**
    * Create, update, and delete quizzes.
    * Manage student accounts and monitor feedback.
    * View comprehensive ranking and leaderboard statistics.
* **Account Management:** Secure user registration and login system.
* **Leaderboard:** Global ranking system to foster healthy competition among students.
* **Feedback System:** Integrated communication channel for students to provide input to administrators.

---

## 🛠 Tech Stack

| Category | Technology |
| :--- | :--- |
| **Backend** | PHP |
| **Database** | MySQL |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Styling** | Bootstrap (via custom CSS) |
| **Server** | XAMPP / WAMP / Apache |

---

## 🏗 Project Structure

```text
.
├── css/              # External stylesheets and Bootstrap components
├── js/               # Client-side logic for quizzes and validation
├── images/           # Assets and UI icons
├── dbConnection.php  # Centralized MySQL database configuration
├── admin.php         # Administrator login and control portal
├── account.php       # Student dashboard and quiz list
├── dash.php          # Main administrative dashboard
└── update.php        # Logic for processing quiz submissions and score updates
````

-----

## 🚀 Getting Started

### Prerequisites

  * **XAMPP** or **WAMP** server installed.
  * A modern web browser.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/shubham230523/OnlineExaminationWebsite.git
    ```
2.  **Move to local server:**
    Copy the project folder to your `htdocs` (XAMPP) or `www` (WAMP) directory.
3.  **Database Setup:**
      * Open `phpMyAdmin`.
      * Create a new database named `project`.
      * Import the provided SQL file (if available) or manually configure tables as defined in `dbConnection.php`.
4.  **Configuration:**
    Check `dbConnection.php` to ensure your database credentials (host, username, password) match your local environment.
5.  **Run:**
    Open `localhost/OnlineExaminationWebsite` in your browser.

-----

## 💡 Improvements & Roadmap

  * **Proctoring Features:** Implement tab-switching detection to prevent cheating.
  * **Timed Exams:** Add a countdown timer for individual quizzes.
  * **Certificate Generation:** Automatically generate PDF certificates for students who pass.
  * **Responsive Redesign:** Fully optimize the UI for mobile and tablet users.

-----

## 🤝 Contributing

Contributions are welcome\! If you have suggestions for new features or bug fixes, feel free to open an issue or submit a pull request.

-----

### 👨‍💻 Author

**Shubham**

  * [GitHub](https://github.com/shubham230523)
