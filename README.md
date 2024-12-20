# Key Event Tracker

A simple JavaScript application that tracks and displays information about keyboard key events in real-time. When a key is pressed, it shows the key's name, its keycode, and the key code associated with the event in a table format.

## Features

- **Key Detection**: The app detects when a key is pressed on the keyboard.
- **Displays Key Information**: For each key press, the app shows:
  - The name of the key pressed (e.g., "Enter", "Space", etc.)
  - The keycode (the numerical representation of the key)
  - The code (a string representing the physical key on the keyboard)
- **Dynamic Updates**: As you press different keys, the displayed information updates dynamically in the app.

## How It Works

1. **Press any key**: When you press any key on your keyboard, the app will display the key's information in a table.
2. **Key Information Display**: The table contains three columns:
   - **Key**: The name of the key pressed, where "Space" is used for the space bar.
   - **Keycode**: A numerical value representing the key pressed.
   - **Code**: A string value that indicates which key was physically pressed (e.g., "KeyA", "Space").

## Setup Instructions

1. Clone or download the repository.
2. Open the `index.html` file in your web browser.
3. Press any key on your keyboard to see the information being displayed.

## File Structure

```plaintext
├── index.html          # HTML file that contains the structure of the app
├── script.js           # JavaScript file that implements the key event detection logic
└── style.css           # Optional CSS file for styling the table (if desired)
