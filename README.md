# 🐍 Snake Water Gun Game

A simple **console-based Snake Water Gun game built using Python**.
This beginner-friendly project demonstrates fundamental Python concepts such as functions, conditional statements, user input, random number generation, and basic game logic.

## 🎥 Demo Video

The following demo video shows the Snake Water Gun game running in the terminal and demonstrates the actual program output.

https://github.com/user-attachments/assets/3accd8bf-6cff-45d1-89f2-b0488aa237ab



## 🎮 Project Overview

Snake Water Gun is a simple game similar to Rock Paper Scissors.

The player chooses one of:

* 🐍 Snake (`s`)
* 💧 Water (`w`)
* 🔫 Gun (`g`)

The computer randomly selects one of the three choices.

The program then compares the player's choice with the computer's choice and displays:

* 🥳 You Win
* 😖 You Lose
* 🤦‍♂️ Draw

## 🧠 Game Rules

| Player      | Computer    | Result       |
| ----------- | ----------- | ------------ |
| 🐍 Snake    | 💧 Water    | Player Wins  |
| 💧 Water    | 🐍 Snake    | Player Loses |
| 💧 Water    | 🔫 Gun      | Player Wins  |
| 🔫 Gun      | 💧 Water    | Player Loses |
| 🔫 Gun      | 🐍 Snake    | Player Wins  |
| 🐍 Snake    | 🔫 Gun      | Player Loses |
| Same Choice | Same Choice | Draw         |

## 🛠️ Technologies Used

* **Python 3**
* **random module**

## 📚 Python Concepts Used

This project helped me practice:

* Functions
* `if-elif-else` statements
* User input
* String handling
* Random number generation
* Boolean values
* Comparison operators
* Basic game logic

## ⚙️ How It Works

### 1. Import the random module

```python
import random
```

The `random` module is used to generate a random choice for the computer.

### 2. Create the game logic

The `game_win()` function compares the user's choice with the computer's choice.

```python
def game_win(user, computer):
    if user == computer:
        return None
```

The function returns:

* `True` → User wins
* `False` → User loses
* `None` → Draw

### 3. Generate the computer's choice

```python
rand_no = random.randint(1, 3)
```

The generated number determines whether the computer selects Snake, Water, or Gun.

### 4. Take user input

```python
user = input(
    "Your turn :🐍 Snake(s), 💧 Water(w), 🔫 Gun(g): "
).lower()
```

The `.lower()` method makes the input lowercase.

### 5. Display the result

The program compares both choices and prints the final result.

## ▶️ How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/AvadheshKumarRathaur/Snake-Water-Gun-Game.git
```

### Step 2: Open the project folder

```bash
cd snake-water-gun
```

### Step 3: Run the Python file

```bash
python snake_water_gun.py
```

## 💻 Example Output

```text
Computer's turn: 🐍 Snake(s), 💧 Water(w), 🔫 Gun(g)

Your turn: 🐍 Snake(s), 💧 Water(w), 🔫 Gun(g): s

You Choose: s

Computer choose: w

You win! 🥳🥳
```

Another possible output:

```text
Computer's turn: 🐍 Snake(s), 💧 Water(w), 🔫 Gun(g)

Your turn: 🐍 Snake(s), 💧 Water(w), 🔫 Gun(g): g

You Choose: g

Computer choose: g

It's a draw! 🤦‍♂️
```



## 🚀 Future Improvements

Some features that could be added in future versions:

* Multiple rounds
* Score tracking
* Play Again option
* Better input validation
* GUI interface using Tkinter
* Match history
* Difficulty levels

## 🎯 Learning Outcome

This project helped me understand how basic Python concepts can be combined to create an interactive program.

It also gave me practical experience with **functions, conditions, randomization, input handling, and problem-solving**.

## 👨‍💻 Author

**Avadhesh Kumar Rathaur**

B.Tech Computer Science
Maharana Pratap Engineering College, Kanpur

### 🔗 Connect With Me

* LinkedIn: https://www.linkedin.com/in/avadhesh-kumar-rathaur
* GitHub: https://github.com/AvadheshKumarRathaur

---

⭐ If you find this project useful, feel free to star the repository!
