# 🥁 Music DrumKit

Interactive virtual drum kit that lets you play 8 different drum sounds using your keyboard or mouse clicks.

## ✨ Features

- 🎹 8 unique drum sounds with keyboard controls
- 🖱️ Mouse click support on all drums
- 🎨 Visual feedback with animations on key press
- 🔊 High-quality drum sound samples
- 📱 Fully responsive design
- 🚀 No installation required - runs directly in browser

## 🎮 How to Play

1. Visit the [live demo](https://music-drumkit.netlify.app/)
2. Press the corresponding keys on your keyboard
3. Or click the drum buttons with your mouse
4. Create your own beats and rhythms!

## 🎵 Drum Sounds & Keys

| Key | Drum Sound |
|-----|------------|
| **A** | Clap 👏 |
| **C** | Hi-Hat (Closed) 🎩 |
| **Z** | Kick Drum 🥁 |
| **F** | Open Hi-Hat 🔓 |
| **G** | Boom 💥 |
| **H** | Ride Cymbal 🌊 |
| **S** | Snare Drum 🥁 |
| **K** | Tom 🪘 |

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Interactivity and event handling
- **HTML5 Audio API** - Sound playback

## 🚀 Local Setup
```bash
# Clone the repository
git clone https://github.com/smita1078/Music-DrumKit.git

# Navigate to directory
cd drumkit

# Open in browser
open index.html
# Or simply double-click index.html
```

## 📂 Project Structure
```
drumkit/
├── index.html  + js script        # Main HTML file # JavaScript logic
├── style.css           # Styling and animations          
├── sounds/             # Audio files folder
│   ├── clap.wav
│   ├── hihat.wav
│   ├── kick.wav
│   ├── openhat.wav
│   ├── boom.wav
│   ├── ride.wav
│   ├── snare.wav
│   └── tom.wav
└── README.md
```

## 🎯 Learning Outcomes

This project demonstrates:
- ✅ DOM manipulation
- ✅ Event listeners (keyboard events & mouse clicks)
- ✅ Audio playback in JavaScript
- ✅ CSS animations and transitions
- ✅ Responsive web design
- ✅ Clean code structure

## 💡 Key Features Explained

### Keyboard Event Handling
```javascript
document.addEventListener('keypress', function(event) {
    playSound(event.key);
    addAnimation(event.key);
});
```

### Visual Feedback
Each key press triggers a CSS animation for visual feedback, making the experience more interactive and engaging.

## 🎨 Customization

You can easily customize:
- **Sounds**: Replace audio files in `/sounds` folder
- **Keys**: Modify key mappings in `script.js`
- **Styling**: Edit `style.css` for colors and animations
- **Layout**: Adjust drum positions in `index.html`


## 📄 License

Free to use for learning and personal projects!

## 👤 Author

**Smita Prajapati**
- 💼 Senior Analyst @ Deutsche Bank
- 🎓 NIT Raipur Silver Medalist
- 🌐 Portfolio: [smita-portfolio.netlify.app]()
- 💻 GitHub: [@smita1078](https://github.com/smita1078)
- 💼 LinkedIn: [Smita Prajapati](https://www.linkedin.com/in/smita-prajapati082/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- Built as part of web development learning journey

---

**🎵 Happy Drumming! 🥁**
```

---

## 🏷️ Updated Topics
```
drumkit
drum-machine
music
javascript
html5-audio
vanilla-javascript
keyboard-events
interactive
web-audio
audio
browser-game
educational-project
beginner-friendly
```
H - Ride 🌊
S - Snare 🥁
K - Tom 🪘
