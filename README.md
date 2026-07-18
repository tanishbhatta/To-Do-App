<<<<<<< HEAD
# Simple Calculator

A lightweight, responsive calculator web app built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies.

---

## Preview

> _A dark-themed calculator with orange operator keys, displayed on a warm orange background._

---

## Features

- Basic arithmetic: addition, subtraction, multiplication, and division
- Decimal number support
- Clear (C) button to reset the display
- Clean dark UI with orange-highlighted operator keys
- Responsive layout using CSS Grid — works on desktop and mobile
- Hover and active button states for tactile feedback

---

## Project Structure

```
simple-calculator/
├── index.html     # Markup and button layout
├── style.css      # Styling, layout, and theming
└── script.js      # Calculator logic
```

---

## Getting Started

No installation or build tools required.

1. **Clone the repo**
   ```bash
   git clone https://github.com/tanishbhatta/simple-calculator.git
   ```

2. **Open the app**
   ```bash
   cd simple-calculator
   open index.html
   ```
   Or simply double-click `index.html` in your file explorer.

---

## How It Works

### HTML
The calculator layout is built with a `<div>` grid of `<button>` elements. Each button calls a JavaScript function via `onclick`.

### CSS
- Buttons are laid out using `display: grid` with `grid-template-columns: repeat(4, 1fr)`
- The equals (`=`) button spans the full row using `grid-column: 4`
- Operator buttons use a distinct orange (`hsl(39, 100%, 50%)`) to visually separate them from number buttons

### JavaScript

| Function | Description |
|---|---|
| `addToDisplay(input)` | Appends the given value to the display |
| `clearDisplay()` | Resets the display to an empty string |
| `calculate()` | Evaluates the current expression and shows the result |

> **Note:** The `calculate()` function uses JavaScript's built-in `eval()` to evaluate expressions. This works well for a personal or demo project, but `eval()` is generally not recommended for production apps due to security implications.

---

## 🎨 Design

| Element | Value |
|---|---|
| Background | `#e9af74` (warm orange) |
| Calculator body | `hsl(0, 0%, 0%)` (black) |
| Number buttons | `hsl(0, 0%, 30%)` (dark grey) |
| Operator buttons | `hsl(39, 100%, 50%)` (amber/orange) |
| Display text | `#FFFCE1` (off-white) |
| Font | Arial / Helvetica sans-serif |

---

## Possible Improvements

- [ ] Add keyboard input support
- [ ] Show full expression history above the display
- [ ] Add a backspace / delete button
- [ ] Replace `eval()` with a custom expression parser
- [ ] Add percentage (`%`) and sign toggle (`±`) buttons
- [ ] Animate button presses

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋 Author

Made by **[Your Name]** — feel free to fork, modify, and use however you like.
=======
# To-Do-App
A simple task manager built with plain HTML, CSS, and JavaScript. No frameworks, no dependencies. Add tasks, mark them as complete, and delete them.
>>>>>>> de2c6ebebec0ea1c794fbab07c4208c206cd2db4
