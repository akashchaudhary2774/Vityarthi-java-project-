# Java Chat Application

A simple, multi-user chat application built in Java that supports both console-based and GUI-based clients. The application allows multiple users to connect to a server, send messages, and use commands to interact with the chat system.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- *Multi-user Chat*: Supports multiple clients connecting to a single server.
- *Console and GUI Clients*: Choose between a console-based client (ChatClient.java) or a graphical user interface client (ChatClientGUI.java).
- *Commands*:
  - /help: Displays available commands.
  - /users: Lists all online users.
  - /quit: Disconnects the client from the server.
- *Real-time Messaging*: Messages are broadcast to all connected clients in real-time.
- *Username Validation*: Ensures unique usernames for each client.
- *Thread-safe Design*: Uses ConcurrentHashMap for thread-safe client management.

## Prerequisites
- *Java Development Kit (JDK)*: Version 8 or higher.
- *IDE or Compiler*: Any Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse) or command-line tools like javac.
- *Operating System*: Compatible with Windows, macOS, or Linux.
