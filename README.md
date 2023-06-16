# To-Do App in Golang

This repository contains a simple To-Do application implemented in Golang. The application allows users to create, read, update, and delete tasks.

## Features

- Create a new task with a title and description.
- View a list of all tasks.
- Update the title or description of a task.
- Mark a task as completed.
- Delete a task.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Go programming language (version 1.16+): [Install Go](https://golang.org/doc/install)
- SQLite database: [Download SQLite](https://www.sqlite.org/download.html) (Optional, only required for running the application with a persistent database)

## Installation

To install and run the To-Do app, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Coffeedragon96/to-do-app-golang.git
   ```

2. Navigate to the project directory:

   ```bash
   cd to-do-app-golang
   ```

3. Install the project dependencies:

   ```bash
   go mod download
   ```

4. Run the application:

   ```bash
   go run main.go
   ```

   The application will start and listen on `http://localhost:8080` by default.

   **Note:** If you want to use a persistent SQLite database, make sure you have SQLite installed and update the database configuration in `config/config.go` accordingly.

## Usage

Once the application is running, you can access the To-Do app in your web browser at `http://localhost:8080`. The app provides a simple user interface to interact with the tasks.

- To create a new task, click on the "Add Task" button and provide the title and description.
- To view all tasks, click on the "View All Tasks" button.
- To update a task, click on the "Edit" button next to the task and make the necessary changes.
- To mark a task as completed, click on the checkbox next to the task.
- To delete a task, click on the "Delete" button next to the task.

## Contributing

Contributions to this repository are welcome. If you find a bug or have suggestions for improvements, feel free to open an issue or submit a pull request.

Please follow the existing coding style and provide clear commit messages when contributing.

## License

This repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the code according to the terms of the license.

## Acknowledgments

This To-Do app project was created to showcase the implementation of a simple task management application using Golang. Special thanks to the Golang community for providing the necessary tools and resources to build this project.
