# Speed Typing Test ⌨️

A command-line speed typing test implemented using Python and the `curses` library. The program allows users to measure their words-per-minute (WPM) typing speed by typing a randomly chosen text from a file.

## 📝 Features

- **Welcome Screen**: A simple start screen that prompts users to begin the typing test.
- **Typing Speed Display**: Displays the current typing speed in WPM during the test.
- **Text Comparison**: Highlights correct and incorrect characters while typing.
- **Random Text**: Loads a random line from an external text file for each test.
- **Real-Time Updates**: The test updates your typing progress and WPM in real-time.
- **Completion Notification**: Notifies the user once they finish typing the target text.

## 🎮 How to Play

1. **Start the Game**: Run the program and press any key on the welcome screen to begin.
2. **Type the Text**: A random line of text will appear. Start typing as fast as you can!
3. **Track Your Speed**: The WPM (words per minute) will be displayed at the top of the screen as you type.
4. **Correct Mistakes**: Incorrect characters will be highlighted in red, while correct characters are shown in green.
5. **Finish the Test**: Once you've typed the entire text correctly, a completion message will appear.
6. **Exit the Game**: Press `ESC` to exit the game at any time.

## 🔧 Code Overview

- **start_screen()**: Displays the welcome message and waits for a keypress to start the test.
- **display_text()**: Renders the target text, current typed characters, and WPM on the screen, highlighting correct and incorrect characters.
- **load_text()**: Loads a random line of text from the `text.txt` file to be used as the target text.
- **wpm_test()**: Core function that manages the typing test, tracks progress, calculates WPM, and handles user input.
- **main()**: Initializes color pairs, runs the start screen, and manages the main typing test loop.

## ⚙️ Requirements

- Python 3.x
- `curses` library (included with Python on Linux and macOS, may require installation on Windows)
- A `text.txt` file containing multiple lines of text for random selection during the test.

## 🚀 Running the Program

To run the program, use the following command:

```bash
python speed_typing_test.py
