# ♠️ Texas Hold'em Betting Sequence Generator

This project is a simulation tool for modeling betting rounds in Texas Hold'em poker.  
It systematically generates and explores all possible betting sequences among multiple players, given fixed action rules and constraints. The simulation outputs both the sequence of actions and the resulting pot size.

## 📌 Features

- 🃏 Simulates a full betting round with any number of players
- 📐 Enumerates all valid action sequences (e.g., check, bet, call, fold, raise)
- 💰 Tracks player contributions and pot growth
- 🤖 Designed for research in game theory, AI training, and behavior modeling
- 🐍 Written in Python and runnable in Google Colab

## 🚀 Open in Google Colab

Click below to launch this notebook in Colab and run it directly:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LeonLaigogo/Texas-Hold-em-Betting-Sequence-Generator/blob/main/Texas_Hold'em_Betting_Sequence_Generator.ipynb)

---

## 🔧 How It Works

- Defines player actions: `Check`, `Call`, `Fold`, `Bet`, `Raise`  
- Simulates turn-based decisions with game-state cloning
- Uses recursion to explore all paths until the round ends
- Outputs all valid action sequences along with resulting pot sizes

Example output:
Sequence: ['b10', 'c', 'f'] → Pot: 80 Sequence: ['x', 'b10', 'f', 'c'] → Pot: 90 ...


---

## 📂 File Structure
Texas-Hold-em-Betting-Sequence-Generator/ ├── Texas_Hold'em_Betting_Sequence_Generator.ipynb ← Main simulation notebook └── README.md ← Project documentation


---

## 🧠 Use Cases

- Game theory modeling and equilibrium research
- Reinforcement learning simulation environment
- Testing player behavior strategies in simplified settings
- Teaching material for poker-related decision trees

---

## 📬 Contact

If you have feedback or suggestions, feel free to reach out via GitHub:  
[@LeonLaigogo](https://github.com/LeonLaigogo)

---

## ⭐ Like this project?

If this notebook was helpful, consider giving it a ⭐ on GitHub!

