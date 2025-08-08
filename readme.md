# 🏌️ Mini Golf Scorecard PWA

A beautiful, mobile-first Progressive Web App for tracking scores during mini golf games with friends. Features offline functionality, automatic score saving, and detailed game statistics.

## ✨ Features

### 🎯 Core Functionality
- **Multiple Players**: Add unlimited players to your game
- **18-Hole Scoring**: Complete scorecard for full mini golf rounds
- **Par Tracking**: Set and track par for each hole
- **Real-time Leaderboard**: See current standings as you play
- **Score Analysis**: Automatic calculation of birdies, eagles, bogeys, etc.

### 📱 Progressive Web App
- **Offline Support**: Plays completely offline after first load
- **Auto-Save**: Game state automatically saved to device
- **Mobile Optimized**: Responsive design perfect for phones
- **Install to Home Screen**: Add to device home screen like a native app
- **Fast Loading**: Cached resources for instant startup

### 🎨 User Experience
- **Beautiful Design**: Modern gradient background with glassmorphism effects
- **Intuitive Interface**: Clean, easy-to-use scoring interface
- **Animated Interactions**: Smooth hover effects and transitions
- **Accessibility**: High contrast and readable fonts

## 🚀 Getting Started

### Quick Start
1. Open `mini_golf_pwa.html` in any modern web browser
2. Add players to your game
3. Start playing and enter scores for each hole
4. View final results and leaderboard

### Installation as PWA
1. Open the app in Chrome, Safari, or other PWA-supported browser
2. Look for "Install" or "Add to Home Screen" prompt
3. Confirm installation to add to your device
4. Launch from home screen like any other app

## 📖 How to Use

### Setting Up a Game
1. **Add Players**: Enter player names and click "Add"
2. **Remove Players**: Use the "Remove" button if needed
3. **Start Game**: Click "Start Game (18 Holes)" when ready

### During the Game
1. **Set Par**: Enter the par for each hole (typically 3-5)
2. **Enter Scores**: Input each player's stroke count
3. **View Standings**: Check current leaderboard below scoring
4. **Navigate**: Use "Previous" and "Next Hole" buttons
5. **Auto-Save**: Game automatically saves progress

### Viewing Results
- **Final Leaderboard**: Complete ranking by total strokes
- **Par Comparison**: See how each player performed relative to par
- **Winner Celebration**: Special highlight for the game winner

## 🛠️ Technical Details

### Built With
- **React 18**: Modern JavaScript framework
- **Vanilla CSS**: Custom styling with CSS Grid and Flexbox
- **Service Worker**: Offline functionality and caching
- **LocalStorage**: Data persistence across sessions
- **PWA Manifest**: Home screen installation support

### Browser Support
- ✅ Chrome 60+
- ✅ Safari 12+
- ✅ Firefox 65+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
```
mini_golf_pwa.html          # Complete PWA in single file
├── HTML structure
├── CSS styling
├── React components
├── Service Worker
└── PWA manifest
```

## 🔧 Development

### Local Development
1. Clone this repository
2. Open `mini_golf_pwa.html` in your browser
3. Make changes and refresh to see updates

### Key Components
- **MiniGolfApp**: Main React component managing game state
- **Setup View**: Player management interface
- **Playing View**: Hole-by-hole scoring interface  
- **Results View**: Final leaderboard and celebration

### Data Structure
```javascript
{
  players: ["Alice", "Bob"],
  scores: {
    "Alice": { 1: 4, 2: 3, ... },
    "Bob": { 1: 5, 2: 4, ... }
  },
  pars: { 1: 4, 2: 3, ... },
  currentHole: 5,
  view: "playing"
}
```

## 🎮 Screenshots

*Add screenshots of your app in action here:*
- Setup screen with player management
- Scoring interface during gameplay
- Leaderboard and results screen

## 🤝 Contributing

We welcome contributions! Here are some ways you can help:

### Ideas for Enhancement
- [ ] Score history and statistics
- [ ] Course templates and presets
- [ ] Photo capture for memorable shots
- [ ] Social sharing of results
- [ ] Tournament mode with multiple rounds
- [ ] Dark mode theme
- [ ] Sound effects and celebrations

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly on mobile devices
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Icons and emojis for visual enhancement
- React team for the amazing framework
- PWA community for best practices
- Mini golf enthusiasts for inspiration

## 📞 Support

Having issues or questions?
- 🐛 **Bug Reports**: Open an issue with detailed description
- 💡 **Feature Requests**: Suggest new features via issues
- ❓ **Questions**: Ask in the discussions section

---

**Made with ❤️ for mini golf lovers everywhere!**

*Hit a hole-in-one with your scoring - try Mini Golf Scorecard today!*