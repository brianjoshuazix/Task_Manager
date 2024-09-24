##   Task Manager Project

## Installation
Clone the repository: git clone https://github.com/brianjoshuazix/task_manager.git

## Install the dependencies: 
composer install

## Create a copy of the .env.example file and rename it to .env
Configure the database settings in the .env file

## Run the migrations: 
php artisan migrate --seed

## Generate Application Key
php artisan key:generate

Running the Application
Start the development server: php artisan serve
Open a web browser and navigate to http://localhost:8000

## Using the Task Manager
Create a new task: Click on the "Create Task" button and fill in the task details
View tasks: Click on the "Tasks" link to view all tasks
Edit a task: Click on the "Edit" button next to a task to edit its details
Delete a task: Click on the "Delete" button next to a task to delete it
Update task priority: Drag and drop tasks to update their priority
