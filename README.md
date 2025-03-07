# My_To_Do_List_Project
To-Do List Manager

Description

This is a simple To-Do List application built using Python and Tkinter. It allows users to add, delete, and manage tasks. The tasks are stored in an SQLite database so that they persist even after the application is closed.

Features

Add new tasks

Delete selected tasks

Display all tasks in a list

Persistent storage using SQLite

Installation

Prerequisites

Make sure you have Python installed on your system. You also need the following libraries:

tkinter

sqlite3

These libraries are included in Python by default, so no additional installation is required.

Usage

Clone this repository:

git clone https://github.com/your-username/todolist.git
cd todolist

Run the script using Python:

python todo_list.py

Enter a task in the input field and click Add Task.

Select a task from the list and click Delete Task to remove it.

Click Exit to close the application.

Code Overview

Functions

add_task(): Adds a new task to the list and saves it to the database.

list_update(): Updates the displayed task list.

delete_task(): Deletes a selected task from the list and database.

clear_list(): Clears the listbox content.

close(): Closes the application and prints the current task list.

retrieve_database(): Loads tasks from the database when the application starts.

Database

The tasks are stored in an SQLite database (listofTasks.db). The table structure is as follows:

CREATE TABLE IF NOT EXISTS tasks (
    title TEXT
);

GUI Components

Header Frame: Displays the title of the application.

Functions Frame: Contains input field and buttons (Add, Delete, Exit).

Listbox Frame: Displays the list of tasks.

Contributing

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m 'Add new feature').

Push to the branch (git push origin feature-branch).

Open a pull request.

Author

Saurabh Kumar
