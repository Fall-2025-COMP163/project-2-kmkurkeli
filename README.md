# Project 2 – Character Abilities Showcase
Course: COMP 163 – Fall 2025  
Student: Kurkeli Kurkeli  
File: `project2_starter.py`  

---

## 🧠 Project Overview
This project demonstrates object-oriented programming (OOP) concepts including inheritance, method overriding, polymorphism, and composition through a text-based RPG character system.

Players can create unique character types Warrior, Mage, and Rogue each with special abilities and stats.  
Weapons are represented using composition, and the battle system tests interactions between characters.

---

## ⚙️ How to Run
1. Open `project2_starter.py` in PyCharm.
2. Run the program (▶ button or `python3 project2_starter.py` in terminal).
3. The console will display:
   - Each character’s stats  
   - Their special abilities (Power Strike, Fireball, Sneak Attack)  
   - Weapon composition tests  
   - A short battle simulation between Warrior and Mage  

---

## 🧩 Features Demonstrated
| Concept | Description |
|----------|--------------|
| Inheritance | Warrior, Mage, and Rogue inherit from Player → Character |
| Method Overriding | Each subclass redefines `attack()` and `display_stats()` |
| Polymorphism | Multiple classes share the same interface but behave differently |
| Composition | Weapon class objects are attached to characters |
| Encapsulation | Health values are protected from going below zero |

---

## 🧙 Example Output

=== CHARACTER ABILITIES SHOWCASE ===
Testing inheritance, polymorphism, and method overriding
⚔️ Character Stats:
Kurkeli the Brave | HP: 120 | STR: 15 | MAG: 5
Elaris the Arcane | HP: 80 | STR: 8 | MAG: 20
Nyx the Shadow | HP: 90 | STR: 12 | MAG: 10
🔥 Testing Special Abilities:
Kurkeli the Brave uses Power Strike on Training Dummy 1 for 25 damage!
Elaris the Arcane casts Fireball on Training Dummy 2 for 30 damage!
Nyx the Shadow performs a Sneak Attack on Training Dummy 3 for 24 damage!
🗡️ Testing Weapon Composition:
Weapon: Iron Sword | Damage Bonus: +10
Weapon: Magic Staff | Damage Bonus: +15
Weapon: Steel Dagger | Damage Bonus: +8
⚔️ Testing Battle System:
🏆 Kurkeli the Brave wins!
✅ Testing complete! Great work, Kurkeli!

---

## 🧾 AI Assistance Statement
AI was used for code explanation, debugging, and documentation formatting.  
All logic, final implementation, and testing were completed and verified by me.

---

## 📁 File Structure
project-2-kmkurkeli/
├── project2_starter.py # Main program file
├── tests/ # Provided test files (for pytest)
├── README.md # Project documentation (this file)
└── .idea/ , pycache/ # Environment files (ignored)
---

## ✅ Status
All 53 tests passed using 
Project successfully demonstrates inheritance, polymorphism, method overriding, and composition principles.
