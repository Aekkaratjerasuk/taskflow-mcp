# TaskFlow MCP 🌟

![GitHub release](https://img.shields.io/github/v/release/Aekkaratjerasuk/taskflow-mcp?color=brightgreen&label=Latest%20Release&style=flat)

Welcome to **TaskFlow MCP**, a task management Model Context Protocol (MCP) server designed to enhance AI assistants. This project helps break down user requests into manageable tasks, complete with subtasks, dependencies, and notes. It enforces a structured workflow with user approval steps, making task management simpler and more efficient.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Task Management**: Break down complex requests into simple tasks.
- **Subtasks**: Organize tasks into smaller, manageable components.
- **Dependencies**: Define task dependencies to maintain workflow integrity.
- **Notes**: Attach notes to tasks for additional context.
- **User Approval**: Ensure tasks receive user confirmation before proceeding.
- **Easy Integration**: Designed to work seamlessly with AI assistants.

## Getting Started

To get started with TaskFlow MCP, follow the instructions below. You can download the latest release [here](https://github.com/Aekkaratjerasuk/taskflow-mcp/releases).

### Prerequisites

Make sure you have the following installed:

- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Aekkaratjerasuk/taskflow-mcp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd taskflow-mcp
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

Now, your TaskFlow MCP server is running and ready to manage tasks.

## Usage

Once the server is running, you can interact with it through your AI assistant. Here’s how to utilize the features:

### Creating Tasks

To create a new task, send a request to the server with the task details. The server will respond with a unique task ID.

### Adding Subtasks

You can add subtasks to any existing task by specifying the parent task ID. This helps in organizing tasks better.

### Managing Dependencies

Define dependencies between tasks to ensure they execute in the correct order. The server will handle the logic for you.

### Adding Notes

Attach notes to any task for additional context. This is useful for providing background information or instructions.

### User Approval

Before a task proceeds, the server will prompt for user approval. This ensures that the user is always in control.

## Contributing

We welcome contributions to TaskFlow MCP! If you have ideas for improvements or features, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes.
4. Submit a pull request.

Please ensure that your code follows our coding standards and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Links

For more information and updates, visit the [Releases](https://github.com/Aekkaratjerasuk/taskflow-mcp/releases) section. Here, you can find the latest versions and updates for TaskFlow MCP.

---

Feel free to explore, contribute, and make the most out of TaskFlow MCP. We appreciate your interest and support!