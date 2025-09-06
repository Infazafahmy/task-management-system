Laravel Developer Assessment (72 Hours)

**Objective:**
Evaluate your ability to plan, develop, document, and share a Laravel-based web application using best practices, Git workflows, and clean code.


## Task

Build a **Task Management Web Application** with the following core features:

1. **Authentication (Laravel Breeze or Jetstream)**

   * Users can register and log in.

2. **Task CRUD**

   * Users can create, edit, mark as completed, and delete tasks.
   * Each task has: Title, Description, Due Date, and Status.

3. **Dashboard**

   * Display tasks grouped by status: Pending, In Progress, Completed.
   * Use Blade templates with responsive, clean UI design (Tailwind preferred).

4. **System Planning Document (PDF)**

   * Include Tech Stack, Database schema (ER diagram or table structure), App flow overview.

5. **Git & Documentation**

   * Upload the complete project to a GitHub repository.
   * Commit frequently with clear commit messages.
   * Add a detailed README.md with project overview, installation instructions, features, and screenshots (optional).


## Technical Requirements

* Framework: Laravel 10+
* Database: MySQL or SQLite
* Front-end: Blade templates with TailwindCSS
* Authentication: Laravel Breeze or Jetstream
* Version Control: GitHub (public or private repo with access)

## Installation Instructions

1. **Download the project**

   * Extract the ZIP folder `task-manager.zip` to your web server root (e.g., `C:\xampp\htdocs`).

2. **Install PHP dependencies**

   * Open terminal/cmd in the project folder:

     ```bash
     composer install
     ```

3. **Install Node.js dependencies**

   * Ensure Node.js and NPM are installed.

     ```bash
     npm install
     npm run dev
     ```

4. **Set up environment file**

   * Copy `.env.example` to `.env`

     ```bash
     cp .env.example .env
     ```
   * Set database credentials in `.env` file:

     ```env
     DB_CONNECTION=mysql
     DB_HOST=127.0.0.1
     DB_PORT=3306
     DB_DATABASE=task_manager_db
     DB_USERNAME=root
     DB_PASSWORD=
     ```

5. **Generate application key**

   ```bash
   php artisan key:generate
   ```

6. **Run migrations**

   ```bash
   php artisan migrate
   ```

7. **Run the development server**

   ```bash
   php artisan serve
   ```

   * Access the app at `http://127.0.0.1:8000`



## Features

* Add, edit, delete, and mark tasks as completed
* Search and filter tasks by keyword and status
* Dashboard with tasks grouped by status (Pending, In Progress, Completed)
* SweetAlert confirmation pop-ups for deletions and task completion
* Responsive UI with TailwindCSS

## System Planning Document

* Tech stack overview
* Database schema & ER diagram
* Application flow
* Security & best practices



* Additional features & future enhancements

