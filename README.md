# 🎮 Hangman Game – Python Edition 🎮

> 🕹️ Interactive Hangman game built in **Python**  
> 🎨 Customizable themes, levels & character wardrobe  
> 🧠 Includes scoring system and Top 10 leaderboard  

---

## 🧾 Project Overview 🧾

This project implements a fully interactive **Hangman game** written in **Python**.

At the beginning of each game session, the user selects:

- 👤 User name  
- 👕 Preferred character wardrobe  
- 🎯 Difficulty level  
- 🎭 Word theme  

The game then:

- 🎲 Randomly selects a word according to the chosen theme  
- 🔍 Determines number of clues based on selected difficulty  
- ⌨️ Requests the user to enter one letter per iteration  
- ✅ Checks if the letter exists in the word  
- ❌ Adds a new part to the gallows after each wrong attempt  

After **7 wrong attempts**, the player loses.  
If the player guesses all letters correctly — they win 🏆  

At the end of each round:

- 📊 Score is calculated  
- 🗂️ Score is stored  
- 🥇 Top 10 players leaderboard is updated  
- 🔄 Player can choose to start a new round  

---

## 🛠️ Technologies & Tools 🛠️

### 💻 Core Technology
- 🐍 Python 3  

### 📦 External Libraries
- 🖥️ `pyautogui` – for clearing screen in certain IDEs  
- 🎨 `pyfiglet` – for styled and enlarged text output  

---

## ⚙️ Installation & Setup ⚙️

### 📥 Install Required Modules

```bash
pip install pyautogui
pip install pyfiglet
```

---

### 🧼 Clearing Screen in Certain IDEs

In some IDEs (e.g., PyCharm),  
`os.system('cls')` or `os.system('clear')` may not properly clear the console.

To solve this:

1. Install `pyautogui`
2. Define the IDE shortcut for "Clear All" as:

```
ALT + D
```

3. Call:

```python
pyautogui.hotkey('alt', 'd')
```

---

### 🎨 Styled Output with Pyfiglet

To print enlarged, designed text:

```python
import pyfiglet
print(pyfiglet.figlet_format("Your Word", font="slant"))
```

---

## 🎮 Game Features 🎮

- 🎭 Multiple word themes  
- 🎯 Adjustable difficulty levels  
- 👕 Custom character wardrobe  
- 🎲 Random word selection  
- 🪢 Visual hanging progression  
- 📊 Score tracking  
- 🥇 Top 10 leaderboard system  
- 🔄 Multiple rounds per session  

---

## 🧠 Programming Concepts Applied 🧠

- 🎯 Input validation  
- 🔁 Loop control & game flow management  
- 📂 Score persistence & sorting  
- 🎲 Randomization  
- 🧩 Modular function-based structure  

---

## ▶️ Running the Game ▶️

1. Make sure Python 3 is installed  
2. Install required libraries  
3. Run the main file:

```bash
python main.py
```

(or run directly from your IDE)

---

## 👩‍💻 Authors & Credits 👩‍💻

- ⚡ **Hadar Sarusi** ⚡  
  [![GitHub](https://img.shields.io/badge/GITHUB-HADARSARUSI-1F6FEB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HadarSarusi)

- 🔥 **Evyatar Baruch** 🔥  
  [![GitHub](https://img.shields.io/badge/GITHUB-AVIAMADER-0D1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aviaMader)


---

> ⭐ If you enjoyed this project – feel free to leave a star! ⭐
