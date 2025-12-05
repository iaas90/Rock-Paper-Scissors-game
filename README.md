<!-- badges: start -->
[![Java Version](https://img.shields.io/badge/Java-8%2B-blue.svg)](#)  
<!-- badges: end -->

# 🪨🧻✂️ Rock-Paper-Scissors (Java)

## 📖 Table of Contents  
- [Description](#description)  
- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Compile & Run](#compile--run)  
- [Usage Example](#usage-example)  
- [Project Structure](#project-structure)  
- [Potential Improvements](#potential-improvements)  
- [License / Notes](#license--notes)  

---

## Description  
A simple command-line Rock-Paper-Scissors game in Java. The user chooses Rock, Paper, or Scissors (via numeric input), the computer picks a random choice, and the program determines the outcome (win, lose, or tie).  
This is a beginner-friendly exercise demonstrating use of user input, randomness, and conditional logic in Java.

## Features  
- 🎯 Lets the user play Rock, Paper, or Scissors against a computer opponent  
- ✅ Handles invalid user input (rejects choices outside permitted range)  
- ✅ Uses built-in Java libraries — no external dependencies required  
- 🧪 Minimal, clear code — ideal for Java beginners  

## Getting Started

### Prerequisites  
- Java Development Kit (JDK) installed (version 8 or higher recommended)  
- Terminal / Command-line environment  

### Compile & Run  
From the root directory (where the `day4` folder resides), run:
```bash
javac day4/RockPaperScissors.java
java day4.RockPaperScissors
````

Then follow the prompts to enter your choice (0, 1 or 2).

---

## Usage Example

```
Welcome to the Rock, Paper, Scissor Game!

Enter your choice
0: Rock, 1: Paper, 2: Scissors
> 0
Computer choice is: 2
User Wins
```

---

## Project Structure

```
day4/
  └─ RockPaperScissors.java    ← Main program
```

---

## Potential Improvements

* Add a loop so the user can play multiple rounds without restarting the program
* Display the user’s and computer’s choice in human-readable form (e.g. “Rock” instead of “0”)
* Add a score counter (e.g. best of N rounds)
* Improve input handling — ask again if the user enters something invalid instead of exiting
* Optionally extend with a GUI or more advanced interface

---

## License / Notes

This is a simple learning project — feel free to use, modify, or extend it as you like.
