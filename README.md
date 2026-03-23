# Rain Drops

> Arithmetic training game where players solve math problems before falling raindrops reach the bottom.

[![HTML5](https://img.shields.io/badge/HTML5-Canvas orange?style=flat square&logo=html5)](https://html.spec.whatwg.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript ES6-yellow?style=flat square&logo=javascript)](https://developer.mozilla.org/en US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive blue?style=flat square&logo=css3)](https://www.w3.org/Style/CSS/)

---

## Overview

Rain Drops is a fast paced arithmetic brain training game where players race against falling raindrops to solve math problems. Built with vanilla HTML5, CSS3, and JavaScript, this game combines timed challenge mechanics with educational content to make arithmetic practice engaging and fun.

Players must solve arithmetic problems before the corresponding raindrop reaches the bottom of the screen. The game features progressively challenging difficulty levels, multiple arithmetic operations, and a polished dark themed interface with particle effects. Perfect for students and anyone looking to sharpen their mental math skills while competing against time.

---

## Features

- Timed arithmetic problem solving mechanics
- Falling raindrop animations creating urgency
- Progressive difficulty with dynamic problem scaling
- Multiple arithmetic operations (addition, subtraction, multiplication, division)
- Problem difficulty increases with score milestones
- Real-time score tracking and lives/health system
- Responsive button based answer selection
- Visual feedback for correct/incorrect answers
- HUD display with score and remaining lives
- Instruction overlay with clear guidance
- Polished dark themed interface with gradients
- Mobile responsive Canvas rendering
- No framework dependencies (vanilla JS)

---

## Screenshots

> Drop screenshots into `screens/` or the root and they'll render here.

![Rain Drops Game](screens/raindrops.png)

---

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation required

### Play Online

Visit the live game at: https://raindrops by naadir.netlify.app/

### Local Development

```bash
git clone https://github.com/Naadir-Dev-Portfolio/HTML5-Game-RainDrops.git
cd HTML5-Game-RainDrops
# Open index.html in your web browser
python -m http.server 8000  # Or use any local server
```

Then navigate to `http://localhost:8000` in your browser.

---

## Tech Stack

- HTML5 Canvas, 2D graphics and raindrop animations
- CSS3, Responsive layout, gradient backgrounds, button styling
- Vanilla JavaScript (ES6), Game mechanics and problem generation
- Netlify, Cloud deployment

---

## How It Works

The game randomly generates arithmetic problems and displays them on descending raindrops. Each problem appears in a bubble that falls from the top of the screen. Players must solve the problem and click the correct answer from multiple choice buttons at the bottom before the raindrop reaches the bottom edge. Correct answers clear the drop and award points. Missed raindrops cost a life. Difficulty increases as score progresses, introducing larger numbers and more complex operations.

---

## How to Play

1. Watch arithmetic problems appear in falling raindrops
2. Solve each problem and click the correct answer button
3. Clear the raindrop before it hits the bottom (3-second window)
4. You have 3 lives; each missed raindrop costs one
5. Score points for each correct answer
6. Difficulty increases every 5 points with larger operands
7. Game ends when you lose all lives
8. Reload to play again and beat your previous score

---

## Configuration

Customize gameplay by editing the following parameters in the `<script>` section:

- `DROP_SIZE`, Visual size of problem bubbles
- `ROUND_TIME`, Milliseconds before answer buttons timeout
- `DIFFICULTY_STEP`, Score threshold for increasing difficulty
- Button styling, Modify `#answers button` CSS block
- Problem ranges, Adjust the `createArithmeticProblem()` function

---

## Related Projects

- [HTML5-Game Algebraverse](https://github.com/Naadir Dev Portfolio/HTML5-Game Algebraverse)
- [HTML5-Game Hexamatch](https://github.com/Naadir Dev Portfolio/HTML5-Game Hexamatch)
- [HTML5-Game LogicGrid](https://github.com/Naadir Dev Portfolio/HTML5-Game LogicGrid)
