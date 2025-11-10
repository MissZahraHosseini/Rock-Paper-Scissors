# Rock-Paper-Scissors
 Rock Paper Scissors Game

A simple implementation of the classic **Rock, Paper, Scissors** game written in Python.  
Play against the computer and see who wins each round!

---

## 📋 Features

- Random computer choice using `random.choice`
- User input validation
- Winner determined based on standard game rules
- Option to continue or quit after each round
- Clean, well-documented, and type-hinted code

---

## 🧠 Game Rules

| User Choice | Computer Choice | Result |
|--------------|----------------|---------|
| rock 🪨 | scissors ✂️ | user wins 👤 |
| scissors ✂️ | paper 📄 | user wins 👤 |
| paper 📄 | rock 🪨 | user wins 👤 |
| both same | both same | it's a tie 🤝 |

---

## ⚙️ Requirements

- Python **3.8+**

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Run the following command:

```bash
python rock_paper_scissors.py

    If your file has a different name, replace it in the command above.

🕹️ How to Play

    When prompted, enter one of the following:

        rock

        paper

        scissors

    The computer will randomly choose its move.

    The result (win, lose, or tie) will be displayed.

    You can choose to play again or quit by typing 'q'.

🧩 Example Output

Enter your choice (rock/paper/scissors): rock
Computer chose: paper
Oh no, the computer won!

Do you want to play again? (Enter any key to continue or 'q' to quit): q

🛠️ Code Structure

rock_paper_scissors.py
│
├── RockPaperScissors        # Main game class
│   ├── get_user_choice()    # Gets and validates user input
│   ├── get_computer_choice()# Generates a random computer move
│   ├── decide_winner()      # Determines the result
│   └── play()               # Main game loop
│
└── __main__                 # Runs the game in a loop



