# What's Wrong? 💬

A desktop chat application built with **C++** and **Qt**, inspired by WhatsApp — featuring real-time messaging, group chats, stories, and contact management.

We called it **"What's Wrong?"**  
...because that's exactly what people kept asking us while wrestling with data structures at 2AM 😅

---

## 🎥 Demo

> https://www.linkedin.com/posts/sama-ayman-36175a305_ever-yelled-whats-wrong-at-your-code-activity-7331625652388847617-vcKl?utm_source=share&utm_medium=member_ios&rcm=ACoAAE3jPnkB04IBXWv3lk4hDebhQBqCjvmctvQ

---

## 🚀 Features

### 💬 Private & Group Chats
- Send and receive messages in real-time
- Create and manage **group chatrooms**
- Message **status tracking** (sent, delivered, seen)
- **Undo** functionality to retract sent messages

### 📸 Stories
- Post text or image-based stories
- **Visibility settings** — control who can see your stories
- Stories are only visible to your contacts, just like the real thing

### 👥 Contact Management
- Add and manage contacts
- Contact-based access to profiles and stories
- Search and view other users

### 🙍 Profile Customization
- Update your display name, bio, and profile picture
- **Privacy controls** for profile visibility

### 💾 Data Persistence
- All users, messages, chatrooms, and stories saved via **file handling**
- Data loads automatically on app restart

---

## 🧠 Technologies & Concepts

| Layer | Details |
|---|---|
| Language | C++ (OOP) |
| GUI Framework | Qt |
| Data Structures | Linked lists, stacks, queues (for messages, undo, etc.) |
| Persistence | File handling (read/write) |
| Design Pattern | Object-Oriented Programming |

---

## 🗂️ Project Structure

```
WhatsWrong/
├── main.cpp                  # App entry point
├── User.h / User.cpp         # User class & logic
├── Message.h / Message.cpp   # Message structure & status
├── ChatRoom.h / ChatRoom.cpp # Private & group chat logic
├── Story.h / Story.cpp       # Story system
├── dataBase.h / dataBase.cpp # File handling & data persistence
├── project_Gui.h / .cpp      # Qt GUI logic
└── icons/ fonts/             # UI assets
```

---

## 🚀 Getting Started

### Prerequisites
- Qt Creator (Qt 5 or 6)
- C++17 compatible compiler (MinGW / MSVC)

### Run
1. Clone the repository
2. Open the `.pro` file in **Qt Creator**
3. Build and run (`Ctrl + R`)

---

## 📄 License

Built as an academic project. Feel free to explore, fork, and build on it!
