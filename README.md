# 🧩 Slide Puzzle

A customizable number slide puzzle game with multiple grid sizes (3×3, 4×4, 5×5). Pure HTML/CSS/JS - no dependencies!

## 🎮 Play

[Live Demo](https://your-username.github.io/slide-puzzle/)

## ✨ Features

- **3 grid sizes** - 3×3, 4×4, 5×5
- **Move counter** - track your progress
- **Shuffle & Reset** - new game or reset
- **Responsive** - works on all devices
- **Solvable guaranteed** - every shuffle is winnable
- **No dependencies** - just open and play

## 🚀 Quick Start

```bash
git clone https://github.com/vishnus1793/puzzle.git
cd slide-puzzle
open index.html
```

Or just open `index.html` in your browser.

## 🎯 How to Play

1. Click a tile **adjacent** to the empty space
2. Tile slides into the empty spot
3. Arrange numbers **1 to N** in order
4. Empty space ends in **bottom-right corner**
5. Win = green glow! 🎉

## 🛠️ Controls

| Button | Action |
|--------|--------|
| 🎲 Shuffle | Randomizes puzzle (solvable) |
| ↺ Reset | Returns to solved state |
| 3×3 / 4×4 / 5×5 | Change grid size |

## 📁 File Structure

```
slide-puzzle/
└── index.html    # Complete game (HTML + CSS + JS)
```

## 🧠 Technical Details

- **Shuffle**: 200-400 random moves from solved state
- **Win detection**: Ascending order check
- **Responsive**: Flexbox + CSS Grid
- **Browser**: Chrome, Firefox, Safari, Edge, mobile

## 🎨 Customize

Edit colors in the `<style>` section:

```css
body { background: linear-gradient(145deg, #1b2b3f, #14222e); }
.tile { background: #2e4a5e; }
```

Adjust shuffle depth in `shuffleGrid()`:

```javascript
const iterations = 200 + Math.floor(Math.random() * 200);
```

## 🤝 Contributing

PRs welcome! Ideas:
- Timer/stopwatch
- High scores
- Image puzzle mode
- Sound effects
- Themes

## 📝 License

MIT License - free to use, modify, distribute.

---

**Made with ❤️ using vanilla JavaScript**
