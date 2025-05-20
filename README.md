# StickmanMath

**StickmanMath** is an **interactive and engaging educational combat-style Java game** designed to make learning fun for all ages. Players practice arithmetic skills while battling enemies in a dynamic math-based world.

Answer questions correctly to deal damage, earn coins, and progress, all while reinforcing key math skills in addition, subtraction, multiplication, and division. Built entirely in Java with Eclipse, the game uses CSV files for saving user data and game state. It supports multiple account types: **Student**, **Teacher**, and **Developer**, each offering different gameplay or administrative roles.

Perfect for practicing math, tracking student progress, or just enjoying a creative twist on learning!

---

### 📦 Features

* 🧑‍🎓 **Student Accounts**: Regular gameplay experience, track progress, earn coins, buy items.
* 👩‍🏫 **Teacher Accounts**: Add student usernames, view their progress.
* 👨‍💻 **Developer Account**: Debug and test game functionalities (creator access only).
* ⚔️ **Combat-Style Learning**: Answer math questions to deal damage; wrong answers cause damage to the player.
* 🌍 **5 Math Worlds**:

  * Addition
  * Subtraction
  * Multiplication
  * Division
  * Final Boss World (Mixed)
* 🪙 **Coin System**: Earn coins by completing levels. Spend coins in the shop to buy helpful items.
* 📊 **Leaderboard**: Tracks local progress.
* 🎮 **Game Options**: New Game, Load Saved Game, Shop, Leaderboard, Tutorial.
* 💾 **Auto & Manual Save**: Progress saved at checkpoints and via a save button.

---

### 🛠️ How to Run

1. **Clone or Download the Repository**.
2. **Open Terminal or Command Prompt** in the project folder.
3. Navigate into the `Code/` directory.
4. Compile and run the game:

   ```bash
   javac main.java
   java main
   ```

---

### 📁 File Structure

> All files are located inside the `Code/` folder. No subdirectories.

#### Source Files

* `Main.java`: Entry point of the game.
* Other game logic files (e.g., `Shop.java`, `CombatEngine.java`, etc.).

#### CSV Files (Stored outside the JAR in the same folder)

* `Main_Game_File.csv`: Stores user data (username, password, account type, level progress, item inventory).
* `Classroom.csv`: Teacher and associated students (`Teacher, student1, student2, ...`).
* `equations.csv`: Contains math equations used in gameplay.

#### Assets

* `.png`, `.jpg`: Sprites and UI graphics.
* `.wav`: Background music and sound effects.

---

### 🧪 Known Issues

* When exported as a `.jar`, all `.csv` files must **remain outside the jar** and be in the **same folder** as the executable.
* CSV files can be manually edited without running the game — this is currently not restricted.

---

### 🖥️ Requirements

* Java JDK 8 or higher
* Cross-platform: works on Windows, macOS, and Linux (as long as Java is installed)

---

### 📌 Notes

* Made entirely in **Java** using **Eclipse**.
* Data persistence is handled through **CSV files** (no database).
* Save files are auto-updated but also include a manual **save button** on the main menu.

---

### 📃 License

> No license specified yet. (You can let me know if you'd like to use one like MIT or GPL.)

---

### 🙌 Credits

* Game developed by: *\[Your Name or Team Name]*
* Special thanks to: Eclipse IDE, Java community.

---
Here's a clean and combined version of the introduction for your README, merging all the parts you provided:

---