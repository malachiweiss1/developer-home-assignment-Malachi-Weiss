Task Manager Web Application


Welcome to the Task Manager Web Application! 


This full-stack project provides a convenient way to manage your tasks with a user-friendly interface. 
You can easily add, edit, and delete tasks, and view them all at a glance.

Features

Task Management: Add, edit, and delete tasks seamlessly.
User Interface: Intuitive interface for easy task management.
Backend Server: Utilizes a backend server to handle data operations.
MySQL Database: Stores task data efficiently in a MySQL database.
Data Generation: Includes a script to generate sample data for testing purposes.
Getting Started
Follow these steps to get the project up and running on your local machine:

Prerequisites


Node.js and npm installed on your system.


Python installed on your system.


Installation


Clone this repository to your local machine:


git clone https://github.com/malachiweiss1/developer-home-assignment-Malachi-Weiss.git


Navigate to the project directory:


cd developer-home-assignment-Malachi-Weiss


Install dependencies for the backend:



cd backend
python -m venv myvenv
source myvenv/Scripts/activate  # For Windows
pip install -r requirements.txt

Configure the MySQL database:


Open the backend/config.yaml file and enter your MySQL database credentials (and Hugchat details - Optional).


Run the data generation script (optional):


python generate_data.py


Start the backend server:


python server.py


Install dependencies for the frontend:


cd ../frontend/frontend-app


npm install


Start the frontend development server:


npm start


Open your browser and visit http://localhost:3000 to view the application.


Usage


Once the application is running, you can start managing your tasks immediately. 
Use the interface to add, edit, and delete tasks as needed. 
All changes will be reflected in real-time.