# Chat-Application_java
Here's a sample `README.md` file for your Java Chat Application using sockets and Swing:

---

```markdown
# Java Chat Application (Client-Server Model)

This is a simple **chat application** implemented in Java using **Socket Programming** and **Java Swing GUI**. The project includes a `chat_client` and a `chat_server`, which can communicate over localhost using TCP sockets.

## Features

- GUI-based chat using Java Swing
- Real-time messaging between server and client
- Simple and user-friendly interface
- Socket-based communication
- Error handling for network issues

---

## Requirements

- Java Development Kit (JDK) 8 or higher
- Java Swing (part of standard Java)
- IDE (e.g., Eclipse, IntelliJ IDEA, or NetBeans) or use terminal/command line

---

## How to Run

### 1. Compile the project

Compile both `chat_server.java` and `chat_client.java` using a terminal or IDE.

```bash
javac chat_server.java
javac chat_client.java
```

### 2. Run the Server

Run the server first to start listening on port `1201`.

```bash
java chat_server
```

### 3. Run the Client

Run the client after the server is running.

```bash
java chat_client
```

### 4. Start Chatting

- Type a message in the text field and press **Send**.
- Messages will appear in the text area for both client and server.

---

## Code Structure

### `chat_server.java`
- Listens for incoming client connection on port `1201`.
- Receives messages from the client and displays them.
- Sends messages typed by the server operator.

### `chat_client.java`
- Connects to server at `127.0.0.1:1201`.
- Sends messages to the server.
- Displays incoming server messages in a text area.

---

## Screenshots
![image](https://github.com/user-attachments/assets/73a1ab16-ec17-4683-9547-13b39bf9a723)

## Notes

- The application is designed for localhost only. For remote connections, change the IP from `127.0.0.1` to the server's actual IP address.
- Currently supports single client-server connection only.

---

## License

This project is open-source and free to use for educational purposes.

---

## Author

Developed by [Mohit Kumar Singh]
