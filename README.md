# Rain Drops

Arithmetic Brain training excercise by Naadir.

A responsive, browser-based educational game where arithmetic problems fall like raindrops and players "catch" them by selecting the correct answer before they reach the bottom.

---

## Features

- **Dynamic Difficulty**: Starts with addition and subtraction, then gradually introduces multiplication and division, scaling up to 12×12 tables as your score increases.
- **Fixed-Size Drops**: Problem bubbles remain at a consistent size (120 px), ensuring readability across devices.
- **Responsive Layout**: Canvas and UI elements adapt seamlessly to desktop, tablet, and mobile screens without scrollbars.
- **Visual HUD & Feedback**:
  - Score and lives displayed in the top-left corner.
  - Correct/Wrong/Time's Up pop-up messages.
- **Instruction Overlay**: Semi-transparent instructions panel with frosted-glass effect to guide new players.
- **Stylish Aesthetics**: Gradient background, frosted panels, and polished button interactions.

---

## How to Run

1. Clone or download the repository.
2. Open `index.html` (or your HTML file) in any modern web browser (Chrome, Firefox, Edge, Safari).
3. The game will start automatically.

---

## How to Play

1. Watch the arithmetic problems fall from the top of the screen.
2. Click the correct answer button at the bottom to "catch" the problem.
3. Solve before it hits the bottom to avoid losing a life.
4. You have **3 lives**; mistakes or timeouts deduct one life.
5. Score points to increase difficulty every 5 points.

---

## Customization

- **Drop Size**: Modify `const DROP_SIZE` in the `<script>` to change bubble size.
- **Button Styles**: Edit the `#answers button` CSS block for different sizes, colors, or fonts.
- **Instruction Text**: Update the HTML inside `<div id="instructions">` to change guidance.
- **Difficulty Curve**: Adjust score thresholds or factor ranges in `createArithmeticProblem()`.

---

## File Structure

- `index.html` – Main game file containing HTML, CSS, and JavaScript.

---

## License

This project is released under the MIT License. Feel free to use, modify, and distribute!

