# Rock-Paper-Scissors-Game-App
Java Rock Paper Scissors app

---

# RockPaperScissors – Java Console Game

A simple Java console-based implementation of the classic **Rock, Paper, Scissors** game.
The user selects Rock, Paper, or Scissors, and the computer generates a random choice.
The program then compares both choices and prints the result.

---

## 🚀 Features

* User-friendly console prompts
* Input validation for user choice
* Randomized computer selection
* Clear result output (Win, Lose, or Tie)
* Lightweight and beginner-friendly Java code

---

## 📝 How to Play

1. Run the program.
2. When prompted, enter:

   * **0** for Rock
   * **1** for Paper
   * **2** for Scissors
3. The computer will randomly choose one of the three options.
4. The program displays:

   * Your choice
   * Computer’s choice
   * The result (Win, Lose, or Tie)

---

## 🔧 How It Works

* The program uses a `Scanner` to read the user's input from the console.
* It validates that the user’s input is between 0 and 2.
* The computer's choice is generated using:

  ```java
  new Random().nextInt(3);
  ```
* The game logic compares both choices using standard Rock–Paper–Scissors rules.

---

## 📂 Project Structure

```
src/
└── day4/
    └── RockPaperScissors.java
```

---

## 🖥️ Sample Output

```
Welcome to the Rock, Paper, Scissor Game!
Enter your choice
0: Rock, 1: Paper, 2: Scissors
1
2
Computer wins!
```

---

## 🛠️ Requirements

* Java Development Kit (JDK) 8 or later

---

## ▶️ How to Run

1. Compile:

   ```bash
   javac RockPaperScissors.java
   ```

2. Run:

   ```bash
   java RockPaperScissors
   ```

---

## 📌 Notes

* If the user enters a number outside the range **0–2**, the program exits and shows an error message.
* Make sure your console supports numeric input.


