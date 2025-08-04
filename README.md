✏️ **ROCK PAPER SCISSORS: 5-DAY MINI-GAME QUEST**
🎮 *One Python File That Evolves Each Day*

🎯 **Objective:** Build and expand a single Python file into a complete Rock Paper Scissors game, using your knowledge of conditionals, loops, randomness—and fun twists like score tracking and wild custom moves!

🧠 **Concepts involved:** `input()`, `print()`, `if/else`, `random.choice()`, `while loops`, `functions`, `variables`, `creativity`

🕒 **Estimated time per day:** 30–45 minutes
✅ **Submission:** One single file named `rock_paper_scissors.py`. Keep editing and adding features each day so the game grows more powerful!

---

### 🌱 **Day 1 – Player vs Computer: Input & Output**

**Goal:** Get both the player and the computer to choose rock, paper, or scissors.

1. Use `input()` to ask the player:

   ```
   Choose rock, paper, or scissors: 
   ```
2. Use `import random` and `random.choice()` to randomly select one move for the computer.
3. Print both choices:

   ```
   You chose rock.
   Computer chose scissors.
   ```

💡 **Challenge Extension:** Add `.lower()` so the user can type “ROCK” or “rOcK” and it still works.

---

### ⚔️ **Day 2 – Decide the Winner**

**Goal:** Write logic to figure out who wins each round.

1. Use `if` / `elif` / `else` to handle all possible matchups:

   * Rock beats scissors
   * Scissors beats paper
   * Paper beats rock
   * If same choice → it’s a tie!
2. Print the result like:

   ```
   You win! Rock crushes scissors.
   ```

💡 **Challenge Extension:** Add special messages for each outcome (e.g., "Paper wraps rock like a gift!").

---

### 🔁 **Day 3 – Keep Playing Until Exit**

**Goal:** Make the game loop until the player wants to quit.

1. Wrap the whole game logic in a `while True:` loop.
2. After each round, ask the player:

   ```
   Do you want to play again? (yes/no): 
   ```
3. If the answer is "no", break the loop and print:

   ```
   Thanks for playing!
   ```

💡 **Challenge Extension:** If the player types something weird, like “yeet,” show a friendly error.

---

### 🧮 **Day 4 – Score Tracker**

**Goal:** Keep track of wins for both the player and computer.

1. Create two variables at the top: `player_score = 0` and `computer_score = 0`.
2. After each round, increase the correct one depending on who won.
3. Display the score after every round:

   ```
   Score → You: 3 | Computer: 2
   ```

💡 **Challenge Extension:** Let the player type `"score"` as a move to check the score without playing a round.

---

### 🎩 **Day 5 – Wild Moves Mode**

**Goal:** Add YOUR OWN custom moves to the game!

1. Add at least **2 new custom moves** (e.g., `"wizard"`, `"lava"`, `"banana"`).
2. Decide what each new move beats and loses to. Be creative and have fun with it!
3. Update the game logic so your new moves work in the same way as the classic ones.

💡 **Challenge Extension:** Make your own “secret move” that only works if the player types it! 🤫
