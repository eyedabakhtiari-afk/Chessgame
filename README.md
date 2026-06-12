# Chessgame
Console Chess Game written in java
# ♟️ Advanced Chess Game - Java

## 📌 Project Overview

This project is a complete implementation of the Chess game developed in Java as the final project for the **Advanced Programming** course.

The project was collaboratively developed by:

* **Aida Bakhtiari**
* **Narges Bahrami**

The main objective of this project was to recreate the complete logic and mechanics of a real chess game while providing a user-friendly graphical interface and an enjoyable gameplay experience.

---

## ✨ Features

### ♜ Complete Chess Logic

The game fully implements official chess rules, including:

* Legal movement for all pieces
* Turn-based gameplay
* Piece capturing
* Check detection
* Checkmate detection
* Stalemate detection
* King safety validation
* Prevention of illegal moves

### ♟ Piece Management

Each chess piece has its own dedicated movement logic implemented separately, making the code modular and maintainable.

Implemented pieces:

* King
* Queen
* Rook
* Bishop
* Knight
* Pawn

---

### ⏱ Chess Timer

The game includes a professional timer system:

* 10-minute timer for each player
* Real-time countdown
* Automatic turn switching
* Time-out detection

---

### 🎯 Captured Pieces Panel

A dedicated panel displays all captured pieces during gameplay, allowing players to track material advantages throughout the match.

---

### 🖥 Graphical User Interface (GUI)

The project provides an interactive graphical environment featuring:

* Chessboard rendering
* Piece visualization
* Move execution via mouse interaction
* Captured pieces display
* Timer display
* Game status notifications

---

## 🏗 Project Structure

```text
ChessProject/
│
├── pieces/
│   ├── King.java
│   ├── Queen.java
│   ├── Rook.java
│   ├── Bishop.java
│   ├── Knight.java
│   └── Pawn.java
│
├── Board.java
├── GamePanel.java
├── Move.java
├── MouseHandler.java
├── Timer.java
├── Main.java
│
└── Assets/
```

### 📂 pieces/

This package contains the movement logic and behavior of all chess pieces.

Responsibilities:

* Defining legal moves
* Movement validation
* Piece-specific rules

---

### 📂 Board

Responsible for:

* Managing board state
* Tracking piece positions
* Updating game status after every move

---

### 📂 Game Panel

Handles:

* Board rendering
* Drawing pieces
* User interactions
* Visual updates

---

### 📂 Timer System

Responsible for:

* Countdown management
* Player time tracking
* Timeout detection

---

## 🧠 Object-Oriented Programming Concepts Used

This project heavily utilizes OOP principles:

### Encapsulation

Game data and piece states are protected within their corresponding classes.

### Inheritance

All chess pieces inherit common functionality from a shared parent class.

### Polymorphism

Different pieces implement their own movement behavior while sharing a common interface.

### Abstraction

Complex chess mechanics are encapsulated behind clean class structures.

---

## 🚀 How to Run

### Requirements

* Java JDK 17+ (or the version used in the project)
* Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans)

### Steps

1. Clone the repository:

```bash
git clone https://github.com/your-username/chess-project.git
```

2. Open the project in your IDE.

3. Build and run:

```bash
Main.java
```

4. Enjoy playing Chess!

---

## 🎓 Educational Goals

This project was designed to strengthen skills in:

* Object-Oriented Programming
* GUI Development with Java
* Event Handling
* Data Structures
* Software Design
* Game Development

---

## 🤝 Authors

### Aida Bakhtiari

Advanced Programming Student

### Narges Bahrami

Advanced Programming Student

---

## ⭐ Project Highlights

✔ Full chess rules implementation

✔ Object-oriented architecture

✔ Interactive GUI

✔ 10-minute chess clock

✔ Captured pieces panel

✔ Modular piece logic

✔ Educational and maintainable codebase

---

*"Every grandmaster was once a beginner."* ♟️
