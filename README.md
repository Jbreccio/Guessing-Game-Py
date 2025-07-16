# 🎲 Guessing Game

An interactive game where the player must guess a randomly generated secret number.

## 📋 Features

- 🎯 Random secret number
- 🔢 Different difficulty levels
- 💡 Hints (highest/lowest)
- 🏆 Scoring system
- 📊 Attempt statistics
- 🎮 Colorful and interactive interface

## 🛠️ Technologies Used

- Python 3.7+
- `random` module (native)
- `colorama` module (for colors in the terminal)

## 🚀 How to Run

1. Clone the repository
2. Install the dependencies:
```bash
pip install -r requirements.txt
```
3. Run the command:
```bash
python main.py
```

## 📖 How to Use

1. Run the program
2. Choose the difficulty level
3. Try to guess the secret number
4. Use the hints to get closer to the goal Answer
5. See your final score

## 🎯 Difficulty Levels

- 🟢 **Easy**: 1 to 50 (10 attempts)
- 🟡 **Medium**: 1 to 100 (7 attempts)
- 🔴 **Hard**: 1 to 200 (5 attempts)

## 🏆 Scoring System

- Base: 1000 points
- Discount: -100 points per attempt
- Difficulty Bonuses: Easy (x1), Medium (x1.5), Hard (x2)

## 🎯 Concepts Learned

- Random Module
- Conditional Structures
- While Loops
- Exception Handling
- Functions
- Terminal Coloring (Colorama)
- Game Logic

## 📝 Usage Example

```
🎲 GAME GUESSING
Choose the difficulty:
1. Easy (1-50)
2. Medium (1-100)
3. Hard (1-200)

Your choice: 2
Try to guess the number between 1 and 100!
Attempt 1/7: 50
📈 The number is BIGGER!
```

## 🔧 Future Improvements

- High score ranking
- Multiplayer mode
- Game history
- Graphical interface
- More elaborate hints

## 📄 License

This project is licensed under the MIT license.
