# Chat Application

## Project Overview
This is a simple chat application built using Java Servlets. It establishes a basic server-client connection, allowing users to send messages to each other. The UI is built using Java Swing for a minimalistic interface.

## Features
- **Basic Server-Client Connection**
- **Real-Time Messaging**
- **Simple Swing-Based User Interface**

## Tech Stack
- **Backend:** Java (Servlets)
- **UI:** Java Swing
- **Networking:** Sockets for server-client communication

## Installation & Setup
### Prerequisites
- Java 17+
- IDE (IntelliJ IDEA, Eclipse, or VS Code)

### Steps to Run
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd chat-application
   ```
2. Compile the Java files:
   ```sh
   javac Server.java Client.java
   ```
3. Start the server:
   ```sh
   java Server
   ```
4. Start the client:
   ```sh
   java Client
   ```
5. Enter messages in the Swing UI to chat.

## Code Structure
- `Server.java` → Listens for client connections and relays messages.
- `Client.java` → Connects to the server and sends messages.
- `Swing UI` → Provides a simple text-based chat interface.

## Future Improvements
- Add support for multiple clients.
- Implement message history storage.
- Improve UI design.

## Contact
For any queries, reach out via email or GitHub issues.

