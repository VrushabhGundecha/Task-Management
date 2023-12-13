# Task-Management Web Application

This is a simple Laravel web application for task management.

## Getting Started

### Prerequisites

Make sure you have the following software installed on your machine:

- PHP
- Composer
- MySQL

### Installation

1. Clone the repository:

   git clone https://github.com/VrushabhGundecha/task-management.git

   1. Navigate to the project directory:
          cd task-management
   
   2. Install dependencies:
          composer install
   
  3. Create a copy of the .env file:
          cp .env.example .env
     
  5. Update the database configuration in the .env file with your MySQL credentials.
    
  6. Generate the application key:
          php artisan key:generate

  7. Run database migrations and seed:
          php artisan migrate --seed

  7. Start the development server:
          php artisan serve
     
     The application will be available at http://127.0.0.1:8000.

  ### Usage

  Access the application in your web browser.
  Create tasks, edit tasks, delete tasks, and reorder tasks with drag-and-drop functionality.
  To filter tasks by project, use the project dropdown on the tasks page.

  ### Deployment
  
  For production deployment, follow these additional steps:

    1. Update the .env file with production settings.

    2. Configure your web server (e.g., Apache, Nginx) to point to the public directory.

    3. Set proper file permissions.


  ### Built With
  
  Laravel - The PHP framework used
  
  MySQL - Database management


  ### License



