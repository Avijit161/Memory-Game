# Memory-Game

# 🎮 Simon Says Game

A classic memory game built with vanilla HTML, CSS, and JavaScript. Test your memory by repeating increasingly longer sequences of colors and sounds!

## 🎯 About

Simon Says is a memory skill game where players must repeat a sequence of colors and sounds that gets progressively longer with each round. This implementation features a modern, responsive design with audio feedback and smooth animations.

## ✨ Features

- **Progressive Difficulty**: Each round adds one more color to the sequence
- **Audio Feedback**: Unique sound for each color button using Web Audio API
- **Visual Animations**: Smooth button animations and hover effects
- **Score Tracking**: Keep track of your current level/score
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Beautiful gradient background with glassmorphic design
- **No Dependencies**: Pure vanilla JavaScript - no frameworks required

## 🚀 Demo

[Live Demo](#) *(Add your GitHub Pages link here after deployment)*

## 🎮 How to Play

1. Click the **Start Game** button
2. Watch carefully as the game lights up a sequence of colors
3. Repeat the sequence by clicking the colored buttons in the same order
4. Each successful round adds one more color to the sequence
5. The game ends when you click the wrong color
6. Try to beat your high score!

## 🛠️ Installation

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start playing!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/simon-says-game.git
cd simon-says-game
```

Then open `index.html` in your browser.

### Option 3: GitHub Pages
Fork this repository and enable GitHub Pages in the settings to host your own version online.

## 📁 File Structure

```
simon-says-game/
│
├── index.html          # Complete game (HTML, CSS, JS in one file)
└── README.md          # Project documentation
```

## 🎨 Customization

The game is built as a single HTML file for simplicity. You can easily customize:

- **Colors**: Modify the color values in the CSS section
- **Sounds**: Change the frequency values in the `colorSounds` object
- **Speed**: Adjust the interval timing in the `playSequence()` function
- **Styling**: Update the CSS variables and styles to match your preference

## 🌐 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

*Note: Requires a browser that supports Web Audio API*

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

### Ideas for Contributions
- Add difficulty levels (easy, medium, hard)
- Implement high score persistence using localStorage
- Add more color options (6 or 8 buttons)
- Create different game modes
- Add keyboard controls
- Implement sound on/off toggle

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Inspired by the classic Simon electronic game from the 1980s
- Built as a fun project to practice vanilla JavaScript skills

---

⭐ If you enjoyed this game, please consider giving it a star on GitHub!

**Have fun playing! 🎉**
