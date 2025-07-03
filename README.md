# 💬 Real‑Time Chat Application in Python

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

A simple **client‑server** chat application built from scratch in Python using the `socket` and `threading` modules. It supports two‑way, real‑time messaging in the terminal and demonstrates core networking and concurrency concepts.

---

## 📝 Table of Contents

1. [Features](#features)  
2. [Prerequisites](#prerequisites)  
3. [Getting Started](#getting-started)  
   - [Clone the Repo](#clone-the-repo)  
   - [Run the Server](#run-the-server)  
   - [Run the Client](#run-the-client)  
4. [Project Structure](#project-structure)  
5. [Usage Example](#usage-example)  
6. [How It Works](#how-it-works)  
7. [What I Learned](#what-i-learned)  
8. [Future Improvements](#future-improvements)  
9. [Contributing](#contributing)  
10. [License](#license)  

---

## 🔥 Features

- 🔄 **Two‑way real‑time chat** over TCP (localhost)  
- 🤖 **Multithreading** for simultaneous send/receive  
- 🌐 **Client‑Server architecture** using Python’s `socket` API  
- 🛡️ Graceful shutdown via the `"exit"` command  
- 📚 Clean, well‑commented code for learning and extension  

---

## ⚙️ Prerequisites

- Python 3.7 or higher  
- Basic familiarity with command‑line/terminal  
- (Optional) Git for version control

---

## 🚀 Getting Started

### Clone the Repo

```bash
git clone https://github.com/Ansh-1019/chat_application.git
cd chat_application

### 🔁 1. Clone the Repository
```bash
git clone https://github.com/Ansh-1019/chat_application.git
cd chat_application

### 🖥️ 2. Run the Server

Open terminal 1 and run:
```bash
python server.py

### 💬 3. Run the Client

Open terminal 2 and run:
```bash
python client.py

### 🔚 4. Exit the Chat
type 'exit' in either terminal


