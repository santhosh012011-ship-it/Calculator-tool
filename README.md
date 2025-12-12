# Calculator Tool — School Project

Welcome! This is a small, friendly calculator built as a school project. It's written using plain HTML (with embedded CSS and JavaScript inside the HTML file), so it's easy to open and run in any web browser.

## What this project does

- Provides a simple calculator interface with:
  - A display area that shows the current number or result
  - Buttons for digits (0–9), basic operators (+, −, ×, ÷), decimal point, clear, and equals
- Lets you type numbers and perform basic arithmetic (addition, subtraction, multiplication, division)
- Performs calculations instantly when you press the equals button

## How the code works (simple explanation)

1. Structure (HTML):
   - The page contains the calculator layout: a display element and several button elements.
   - Each button corresponds to a digit, an operator, or a control (clear, equals).

2. Styling (CSS):
   - CSS is used to make the calculator look clean and easy to use: sizing, spacing, colors and responsive layout so it fits well on different screens.

3. Logic (JavaScript inside the HTML file):
   - Button clicks are captured with event listeners.
   - When a digit or operator button is pressed, the display updates to show the input.
   - The equals button takes the current input expression, evaluates the math, and shows the result on the display.
   - The clear button resets the display to an empty or zero state.

Note: The project uses basic JavaScript techniques to keep the logic easy to follow. If you look inside the HTML file you will find the script section where the event listeners and calculation functions are implemented.

## How to run the project

1. Download or clone this repository to your computer.
2. Open the main HTML file (for example, index.html or calculator.html) in a web browser by double-clicking it or dragging it into the browser window.
3. Use the on-screen buttons to perform calculations.

## Tips for reading the code

- Start with the HTML to see how the buttons and display are organized.
- Look for a <script> section (usually near the end of the file) to see how clicks are handled and results are calculated.
- The code is intentionally simple so classmates can read and learn from it.

## This is a school project

This calculator was created as a part of a school assignment. It is meant for learning and demonstration purposes.

## License & Credits

Feel free to use and modify this project for learning. If you share it, please mention the original author.

---

Happy learning! If you want, I can also update this README with a screenshot, example input/output, or step-by-step comments inside the HTML file to help classmates understand the code even faster.
