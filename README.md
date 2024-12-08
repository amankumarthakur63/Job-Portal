# Job Portal

A web-based job portal application developed using PHP, MySQL, HTML, CSS, and JavaScript. This platform connects employers and job seekers, allowing them to post jobs and apply for available positions. The portal includes a user-friendly interface for browsing jobs, creating profiles, and managing job applications.

## Features

- **User Authentication**: Login and registration system for both job seekers and employers.
- **Job Posting**: Employers can post job openings with relevant details such as job title, description, and location.
- **Job Search**: Job seekers can search for jobs based on keywords, categories, and location.
- **Profile Management**: Job seekers can create and update their profiles, upload resumes, and manage job applications.
- **Job Applications**: Job seekers can apply to posted jobs and track the status of their applications.
- **Responsive Design**: Mobile-friendly and accessible on all devices.

## Tech Stack

- **Backend**: PHP (Hypertext Preprocessor)
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript

## Installation

### Prerequisites

Before running the project, ensure that you have the following installed:

- **XAMPP**: A free and open-source cross-platform web server solution that includes Apache, MySQL, and PHP. You can download XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).

### Setup Instructions

1. **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/amankumarthakur63/job-portal.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd job-portal
    ```

3. **Create a database** in MySQL:
    - Open the XAMPP Control Panel and start Apache and MySQL.
    - Open phpMyAdmin by navigating to [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
    - Create a new database named `job_portal`.

4. **Import the database schema**. You can find the SQL file in the `database` folder:
    - In phpMyAdmin, select the `job_portal` database and use the "Import" tab to upload the SQL file.

5. **Configure your database connection**:
    - Open the `config.php` file in the project and update the database settings:
    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'root');
    define('DB_PASSWORD', '');
    define('DB_NAME', 'job_portal');
    ```

6. **Start the project**:
    - Place the project folder (`job-portal`) in the `htdocs` directory of your XAMPP installation (e.g., `C:/xampp/htdocs/`).
    - Open your web browser and go to:
    ```
    http://localhost/job-portal
    ```

## Usage

- **Employer Login**: Once registered, employers can log in to the portal to post jobs.
- **Job Seeker Login**: Job seekers can register and create a profile to search and apply for jobs.
- **Admin Panel**: An admin panel is included for managing users, jobs, and the overall portal.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. We welcome improvements in the following areas:
- Bug fixes
- Code optimization
- UI/UX enhancements
- New features

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push your branch (`git push origin feature/your-feature`).
5. Open a Pull Request with a description of your changes.

## Contact

For questions or suggestions, feel free to contact us at [amankumar005562@gmail.com].

---

Thank you for using the Job Portal!
