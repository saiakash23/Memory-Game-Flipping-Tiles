# 🎮 Memory Game: Flipping Tiles

Welcome to the **Memory Game: Flipping Tiles** project! This Java-based memory game is built using Java Swing and AWT, offering a fun and interactive way to test and improve your memory skills. Dive into the game and see how quickly you can match all the pairs!

## ✨ Features

- 🟢 **Multiple Difficulty Levels**: Choose between Easy and Hard modes to match your skill level.
- 🖥️ **User-Friendly Interface**: Simple and intuitive GUI designed with Java Swing and AWT.
- 📜 **Instructions Included**: Easy-to-follow instructions to get you started quickly.
- 🏆 **Score Tracking**: Keep track of your attempts and aim for the best score.

## 🚀 Getting Started

### 📋 Prerequisites

Ensure you have the following installed:

- [Java JDK 8+](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
- An IDE of your choice (e.g., [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/ide/))

### ▶️ Running the Game

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/memory-game-flipping-tiles.git
   cd memory-game-flipping-tiles
   ```

2. **Compile and Run**:
   - Open the project in your IDE.
   - Compile and run the `GameM2.java` file.
   - Enjoy the game!

## 🎮 How to Play

1. **Start the Game**:
   - Enter a level between 1 and 10.
   - Select Easy or Hard mode.
   - Click 'Start' to begin.

2. **Memorize and Match**:
   - Memorize the placement of pairs when the game begins.
   - Click any button to clear the screen.
   - Match the pairs by clicking the buttons.
   - Each incorrect click will increase your score (lower scores are better).

3. **Win the Game**:
   - Match all pairs to win.
   - Your total tries will be displayed at the end.

## 📸 Screenshots

![Start Screen](screenshots/start_screen.png)
*Start Screen*

![Game Screen](screenshots/game_screen.png)
*Game Screen*

![Win Screen](screenshots/win_screen.png)
*Win Screen*

## 🧩 Code Overview

The main game logic is implemented in the `GameM2` class. Here's a brief overview of the key components:

- **GUI Setup**: JFrame and JPanels are used to create the main layout.
- **Buttons**: JButton array for game tiles and menu buttons.
- **ActionListeners**: Handle button clicks and game logic.
- **Game Logic**: Methods for setting up the game, hiding/showing tiles, checking for matches, and tracking score.

```java
public class GameM2 implements ActionListener {
    JFrame frame = new JFrame("Memory Game");
    JPanel field = new JPanel();
    // Additional Panels and Buttons...

    public GameM2() {
        // GUI Initialization
    }

    public void setUpGame(int x, Boolean mode) {
        // Game setup logic
    }

    // Additional methods for game logic...

    public static void main(String[] args) {
        new GameM2();
    }
}
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements and bug fixes.

---
