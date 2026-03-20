# 💬 Java Messenger App

A real-time multi-client chat application built with **Java Socket Programming** and **Java Swing**. Supports broadcast messaging, private direct messages, and a live online users panel — all with a clean dark-themed GUI.

![Java](https://img.shields.io/badge/Java-8%2B-orange?style=flat-square&logo=java)
![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

---

## 🖥️ Screenshots

| Client Window | Server Monitor |
|:---:|:---:|
| ![Client](client%20side%20image.png) | ![Server](server%20side%20image.png) |

---

## ✨ Features

- 🔗 **Multi-client support** — Multiple users can connect simultaneously
- 📢 **Broadcast messaging** — Messages reach all connected clients
- 🔒 **Private messaging** — DM any user using `@username: message`
- 🟢 **Live online users panel** — See who's online in real time
- 🖥️ **Server monitor GUI** — Track all connections and messages server-side
- ⌨️ **Enter key support** — Press Enter or click Send to send messages
- 🧵 **Multithreaded** — Each client runs on a dedicated thread

---

## 📁 Project Structure

```
Messenger-App-in-java/
│
├── src/
│   ├── Client.java          # Client application (GUI + socket)
│   └── Main.java            # Server application (monitor GUI + ClientHandler)
│
├── client side image.png    # Client UI screenshot
├── server side image.png    # Server UI screenshot
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or above
- Terminal / Command Prompt or any Java IDE

### 1. Clone the Repository

```bash
git clone https://github.com/heybhart/Messenger-App-in-java-.git
cd Messenger-App-in-java-
```

### 2. Compile

```bash
cd src
javac Main.java
javac Client.java
```

### 3. Run the Server

```bash
java Main
```

> The server starts on `localhost:5555`

### 4. Run Client(s)

Open one or more terminals and run:

```bash
java Client
```

---

## 💬 Usage

| Action | Command |
|--------|---------|
| Send message to everyone | Type your message → click **Send** or press **Enter** |
| Send a private message | `@username: your message` |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Java (JDK 8+) | Core language |
| `java.net.Socket` | TCP client-server communication |
| `javax.swing` | GUI (dark theme) |
| `java.io` | I/O streams |
| `java.util.Collections` | Thread-safe sets |
| `Thread` | Multithreading per client |

---

## 🔮 Roadmap

- [ ] Username-based login system
- [ ] Message timestamps
- [ ] File/image sharing
- [ ] Persistent chat history (SQLite/MySQL)
- [ ] Proper name → socket mapping for accurate private messaging
- [ ] Dark/light mode toggle

---

## 👨‍💻 Author

**Bhart** — [@heybhart](https://github.com/heybhart)

Feel free to fork, star ⭐, and contribute!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
