# Remote Desktop Viewer

A Java-based Remote Desktop Viewer application with real-time screen sharing, chat, and remote mouse/keyboard control. Ideal for remote support, collaboration, and education scenarios.

# Features

- Live screen sharing between server and client
- Remote mouse and keyboard control
- Real-time chat between client and server
- Password-based authentication
- File transfer
- Logs for screen sharing and chat sessions


# Tech Stack

- **Language:** Java (Java SE)
- **GUI:** Java Swing
- **Networking:** Sockets, Threads
- **IDE:** VS Code / Eclipse / IntelliJ
- **Web App:** Java Servlets, JSP, HTML/CSS/JS



# Project Structure

RemoteDesktopViewer/
├── server/
│ └── Server.java
├── client/
│ └── Client.java
├── shared/
│ ├── ScreenCapture.java
│ ├── InputController.java
│ └── ChatHandler.java
├── ui/
│ └── ViewerGUI.java
└── README.md



# How to Run

# Server
- Compile:
   ```bash
   javac RemoteDesktopServer.java
- Run:
  ```bash
  java RemoteDesktopServer
# Client
- Compile:
  ```bash
  javac RemoteDesktopClient.java

- Run and enter server IP:
  ```bash
  java Client
# Web Integration
- Web-based interface using JSP/Servlets

- JSP pages for login, dashboard, and viewer

- Connects to server backend using sockets or REST

# Authentication
- Clients must enter a valid password to connect.

- Server can approve or deny requests.

# To Do
- Add user login system

- Enable secure file transfer

- Enhance UI with JavaFX or web front-end

- Implement encrypted communication
