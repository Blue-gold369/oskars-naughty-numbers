# 🎮 Oskar's Naughty Numbers

A cyberpunk-themed number guessing game with stunning animations, neon effects, and interactive gameplay designed for 12-year-old Oskar!

## 🌟 Live Demo
**Play the game here:** [https://blue-gold369.github.io/oskars-naughty-numbers](https://blue-gold369.github.io/oskars-naughty-numbers)

## 🎯 Game Features

### 🎮 Core Gameplay
- **Number Guessing Game**: Computer picks a random number, you try to guess it!
- **4 Difficulty Levels**: Easy (1-10), Medium (1-50), Hard (1-100), Expert (1-1000)
- **Smart Hint System**: Temperature-based proximity hints (🧊 Freezing → 💥 Burning!)
- **Personal Touch**: Special victory messages for Oskar with his name!

### ✨ Visual Effects
- **Cyberpunk Aesthetic**: Neon colors, glowing borders, and animated gradients
- **Particle Background**: Floating animated particles with color-shifting effects
- **Typewriter Effect**: Hints appear character by character with sound
- **Animated Temperature Meter**: 5-bar proximity indicator that lights up progressively
- **Confetti Celebrations**: Regular confetti for wins, rainbow confetti for 1-try victories!
- **Smooth Animations**: Hover effects, button animations, and loading states

### 🔊 Audio Experience
- **Dynamic Sound Effects**: Different frequencies for different hint temperatures
- **Interactive Audio**: Typewriter sounds, button clicks, and celebration sounds
- **Web Audio API**: Professional-quality sound generation
- **Sound Toggle**: Can be disabled in game options

### 🎛️ Game Options
- **Sound Effects**: Toggle audio on/off
- **Temperature Hints**: Enable/disable proximity hints
- **Show Attempts**: Display or hide attempt counter
- **Hard Mode**: Removes temperature hints for extra challenge

### 📊 Progress Tracking
- **Attempt Counter**: Track your current game progress
- **Best Scores**: Saved per difficulty level using localStorage
- **High Score System**: Persistent best scores across browser sessions

## 🛠️ Technical Features

### 💻 Built With
- **Pure HTML5**: Single-file game, no dependencies
- **CSS3 Animations**: Advanced keyframe animations and transitions
- **Vanilla JavaScript**: Modern ES6+ features and classes
- **Web Audio API**: Dynamic sound generation
- **Local Storage**: Persistent high score tracking

### 📱 Device Support
- **Desktop**: Full experience with mouse interactions
- **iPad/Tablet**: Touch-optimized with numeric keyboard
- **Mobile**: Responsive design for phones
- **Cross-Browser**: Works in Safari, Chrome, Firefox, Edge

### 🎨 Visual Technology
- **CSS Gradients**: Animated rainbow effects and neon glows
- **Canvas Particles**: Hardware-accelerated background animation
- **Flexbox/Grid**: Responsive layout system
- **Custom Properties**: Dynamic theming support

## 🚀 How to Play

1. **Select Difficulty**: Choose your challenge level (Easy to Expert)
2. **Configure Options**: Toggle sound, hints, and other preferences
3. **Start Game**: Click "Start New Game" to begin
4. **Make Guesses**: Enter numbers and watch the temperature meter
5. **Follow Hints**: Use directional arrows and temperature clues
6. **Celebrate Victory**: Enjoy confetti and personal victory messages!

## 🏆 Scoring System

- **1 Try**: 🌟 "INCREDIBLE! That's legendary, Oskar!" + Rainbow Confetti
- **2-3 Tries**: 🔥 "AMAZING! Well done, Oskar!" + Regular Confetti  
- **4+ Tries**: 🎉 "Congratulations! Great job, Oskar!" + Celebration

## 🎲 Game Mechanics

### Temperature System
- **🧊 Freezing**: Very far from target (40%+ of range away)
- **❄️ Cold**: Far from target (20-40% of range away)
- **🔥 Warm**: Getting closer (10-20% of range away)
- **🌋 Hot**: Very close (5-10% of range away)
- **💥 Burning**: Extremely close (0-5% of range away)

### Difficulty Scaling
- **Easy (1-10)**: Perfect for beginners, quick games
- **Medium (1-50)**: Standard challenge level
- **Hard (1-100)**: Requires strategic thinking
- **Expert (1-1000)**: Ultimate challenge for number masters

## 📥 Installation & Setup

### Option 1: GitHub Pages (Recommended)
1. The game is automatically hosted at the live demo link above
2. Just bookmark and play!

### Option 2: Local Setup
1. Download `index.html` from this repository
2. Open the file in any modern web browser
3. No additional setup required!

### Option 3: Host Yourself
1. Download the files
2. Upload `index.html` to any web server
3. Access via your hosting URL

## 🔧 Customization

The game is designed to be easily customizable:

- **Colors**: Modify the CSS custom properties for different themes
- **Sounds**: Adjust frequency ranges in the `playSound()` function
- **Messages**: Change victory messages in the `handleWin()` method
- **Difficulty**: Add new ranges in the difficulty selector
- **Animations**: Modify keyframe animations for different effects

## 🎨 Design Philosophy

Created with a **cyberpunk/hacker aesthetic** inspired by sci-fi movies, featuring:
- Electric blue (#00d4ff) and bright green (#00ff88) neon colors
- Purple (#8a2be2) and hot pink (#ff1493) accent colors
- Orbitron font for futuristic headers
- Share Tech Mono for code-style number display
- Glassmorphism effects with backdrop blur
- Smooth 60fps animations throughout

## 📱 Mobile Optimization

- **Touch-First Design**: All interactions optimized for touch
- **Responsive Layout**: Adapts to any screen size
- **Numeric Keyboard**: Automatic keyboard selection on mobile
- **Large Touch Targets**: Easy tapping on small screens
- **Optimized Performance**: Smooth animations on mobile devices

## 🔊 Accessibility Features

- **Keyboard Navigation**: Full keyboard support
- **High Contrast**: Strong color contrasts for visibility
- **Clear Typography**: Large, readable fonts
- **Audio Feedback**: Sound cues for interactions
- **Visual Feedback**: Multiple forms of feedback for actions

## 🐛 Browser Support

- **Chrome 80+**: Full support
- **Safari 13+**: Full support (including iOS Safari)
- **Firefox 75+**: Full support
- **Edge 80+**: Full support

## 📝 Version History

- **v1.0**: Initial release with full game functionality
- **v1.1**: Added rainbow confetti for perfect games
- **v1.2**: Enhanced mobile optimization
- **v1.3**: Improved sound system and accessibility

## 👨‍💻 Development

Built by transforming a cyberpunk password generator into an engaging number guessing game while preserving all the visual effects and animations. The result is a professional-looking game that feels like a hacker tool from a movie!

## 🎁 Perfect For

- **12-year-old Oskar**: Personal messages and age-appropriate challenge
- **Family Game Night**: Multiple difficulty levels for all ages  
- **Math Practice**: Fun way to work with numbers and ranges
- **Showcasing Web Skills**: Demonstrates advanced CSS and JavaScript

## 📄 License

This project is open source and available under the MIT License.

---

**🎮 Ready to play? [Click here to start guessing!](https://blue-gold369.github.io/oskars-naughty-numbers)**

*Have fun, Oskar! 🌟* 