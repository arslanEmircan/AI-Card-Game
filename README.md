# AI Card Game – Heuristic Search Game 

## Overview
This project is a card matching game developed in **Python** using the **Tkinter GUI** library.  
The game features an **AI opponent** that applies **heuristic-based algorithms** for decision-making, offering strategic depth and adaptive gameplay.  

The implementation demonstrates the integration of **artificial intelligence techniques** into a traditional card game environment.

---

## Features
- **AI Opponent with Heuristic Algorithms**  
  Implements custom evaluation functions to analyze cards and maximize winning probability.  

- **Two Difficulty Levels**  
  - Easy Mode: Win by collecting **3 cards of the same suit**.  
  - Hard Mode: Win by collecting **6 cards of the same suit**, with advanced scoring formulas.  

- **Strategic Card Discarding**  
  Probability-based decision-making for selecting which card to discard, ensuring more realistic AI behavior.  

- **Interactive GUI**  
  Built with **Tkinter**, displaying the player’s hand, AI’s hand, and game progression dynamically.  

---

## Technical Details
- **Programming Language:** Python  
- **Libraries:** Tkinter (GUI), Standard Python Libraries  
- **Algorithms Implemented:**  
  - Hand Evaluation (`evaluate_hand`)  
  - Winning Probability Calculation (`get_winning_probability`)  
  - Card Discard Strategy (`choose_card_to_discard`)  

---

## How to Run
Clone the repository and run:
```bash
python main.py

