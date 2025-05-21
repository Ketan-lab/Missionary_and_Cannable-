# ⛵ Missionaries and Cannibals River Crossing Puzzle

A console-based Python simulation of the classic logic puzzle: move all the missionaries and cannibals from one side of the river to the other without violating the safety rules.

---

## 🧠 Game Concept

The goal is to move **3 missionaries** and **3 cannibals** from the **right side** of the river to the **left side** using a boat that can carry **1 or 2 people** at a time. However, if **cannibals outnumber missionaries** on either side at any point, **you lose**.

---

## 🕹️ How to Play

- The boat starts on the **right** side of the river.
- The user inputs how many missionaries and cannibals are in the boat.
- Rules:
  - The boat can carry **1 or 2 people only**.
  - You **cannot move more people than available** on that side.
  - If cannibals ever outnumber missionaries on either side (when missionaries are present), **you lose**.
  - If you manage to move all 3 missionaries and cannibals to the **left** side without breaking the rules, **you win**.

---

## 💻 Example Gameplay

```bash
M = 0 C = 0 |-----B| M = 3 C 3
Enter the number of missionaries on boat Right: 1
Enter the number of cannibals on boat Right: 1

M = 1 C = 1 |B-----| M = 2 C 2
Left
...

YOU WIN


⚙️ Features
Console-based logic simulation of the river crossing puzzle.

Turn-based input from the player.

Automatic rule checks:

Maximum boat capacity

Invalid moves

Game win/lose conditions

Printed state after every move.

🚀 How to Run
1. Save the code in a file called missionaries_cannibals.py.
2. Run the script using Python:
python missionaries_cannibals.py

💡 Make sure you have Python 3.x installed on your system.

🧱 Known Issues
Only one move is processed per execution. To make it a complete game loop, you could wrap the logic in a while True loop.

Input validation could be improved.

👨‍💻 Contributors
Your Name – Initial Code & Documentation

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

📬 Feedback
Have suggestions or improvements? Feel free to open an issue or a pull request.
