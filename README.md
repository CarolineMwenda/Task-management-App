
The Task Management App is a web application built using Python Django framework. It allows users to manage and track their tasks efficiently.

## Features

- User Registration and Authentication: Users can create an account, log in, and log out to access the app's features.
- Task Creation: Users can create new tasks by providing a title, description, due date, and other relevant details.
- Task Listing: Users can view a list of all their tasks, including task details such as title, due date, and status.
- Task Filtering and Sorting: Users can filter and sort tasks based on different criteria, such as status and due dates
- Task Update and Deletion: Users can update or delete existing tasks as needed.
- Task Assignments: Users can assign tasks to other users and track task ownership.
- Task Status Tracking: Users can mark tasks as completed or in progress to track their progress.


## Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/task-management-app.git
   ```

1. Navigate to the project directory:

   ```
   cd task-management-app
   ```

1. Create a virtual environment:

   ```
   python -m venv env
   ```

1. Activate the virtual environment:

   - For Windows:
     ```
     .\env\Scripts\activate
     ```
   - For macOS and Linux:
     ```
     source env/bin/activate
     ```

1. Install the project dependencies:

   ```
   pip install -r requirements.txt
   ```

1. Set up the database:

   ```
   python manage.py migrate
   ```

1. Start the development server:

   ```
   python manage.py runserver
   ```

1. Access the app in your web browser at `http://localhost:8000`.

