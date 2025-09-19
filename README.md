# 🧟 Zombie Smasher

A thrilling Halloween-themed top-down zombie survival game built with HTML5 Canvas and JavaScript.

## 🎮 Game Overview

**Zombie Smasher** is an action-packed survival game where players fight through zombie-infested environments using various weapons and characters. Navigate through multiple levels, defeat hordes of zombies and skeletons, and survive as long as possible while earning points and unlocking new content.

### 🎯 Game Objective
- Clear infected areas by eliminating all zombies
- Survive waves of enemies across multiple levels
- Earn points and XP to progress through the game
- Complete all levels to win the game

## 🕹️ How to Play

### Controls
- **Movement**: WASD or Arrow Keys
- **Shooting**: Mouse (click to shoot)
- **Weapon Switching**: Number keys 1-5
  - `1` - Pistol (default)
  - `2` - Shotgun
  - `3` - Frag Grenade
  - `4` - Nuke
  - `5` - Missile
- **Gamepad Support**: Full Xbox/PlayStation controller support available

### Mobile Controls
- Touch controls automatically enabled on mobile devices
- Optimized interface for touchscreen gameplay
- Full-screen mode on mobile for immersive experience

### Gameplay Mechanics
- **Health System**: Start with 3 health points
- **Ammunition**: Each weapon has limited ammo that can be replenished
- **Power-ups**: Collect chests for weapon upgrades and bonuses
- **Scoring**: Earn points by defeating enemies
- **XP System**: Gain experience to unlock new features
- **Invincibility Frames**: Brief protection after taking damage

### Characters
The game features multiple character variants with unique designs and abilities.

### Enemies
- **Zombies**: Basic infected enemies that spawn regularly
- **Skeletons**: Stronger enemies that appear less frequently
- **Max Spawns**: Up to 10 zombies and 10 skeletons can be active at once

### Levels
- **Level 1**: "Forest Lodge Outbreak" - Clear the infected cabin
- **Level 2**: Additional challenges and objectives
- **Future Levels**: More content planned for development

## 🛠️ Development Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Quick Start
1. **Clone or download** the project
2. **Open `index.html`** in your web browser
3. **Start playing!** The game runs entirely in the browser

### Running Locally
```bash
# Option 1: Simple HTTP server with Python
python -m http.server 8000

# Option 2: Node.js http-server
npx http-server

# Option 3: VS Code Live Server extension
# Right-click index.html and select "Open with Live Server"
```

### File Structure
```
halloween/
├── index.html          # Complete game in a single file
├── README.md          # This documentation
└── .git/              # Git repository
```

## 🏗️ Technical Architecture

### Single-File Architecture
- **Self-contained**: Entire game in one HTML file
- **Embedded CSS**: All styling included in `<style>` tags
- **Embedded JavaScript**: Complete game logic in `<script>` tags
- **No dependencies**: Runs without external libraries

### Key Systems
- **Canvas Rendering**: HTML5 Canvas for 2D graphics
- **Audio System**: Web Audio API for sound effects
- **Input Handling**: Keyboard, mouse, and gamepad support
- **State Management**: Game states, level progression, scoring
- **Mobile Optimization**: Responsive design and touch controls
- **Progress Saving**: Local storage for high scores and progress

### Performance Features
- **Graphics Caching**: Optimized sprite rendering
- **Efficient Collision Detection**: Spatial optimization for large numbers of entities
- **Frame Rate Management**: Smooth 60fps gameplay
- **Memory Management**: Proper cleanup of game objects

## 🚀 Building and Deployment

### Local Development
No build process required! Simply open `index.html` in a browser.

### Testing
```bash
# Test in different browsers
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Deployment Options
1. **Static Hosting**: Upload `index.html` to any web host
2. **GitHub Pages**: Push to GitHub and enable Pages
3. **Netlify**: Drag and drop the file
4. **Vercel**: Deploy with zero configuration

### Mobile Testing
- Test on actual devices for touch controls
- Use browser dev tools device simulation
- Verify full-screen mode functionality

## 🎨 Game Features

### Visual Features
- **Retro Pixel Art Style**: Classic arcade game aesthetics
- **Dynamic Lighting**: Atmospheric lighting effects
- **Particle Effects**: Blood splatters, explosions, muzzle flashes
- **Screen Shake**: Impact feedback for actions
- **Damage Numbers**: Visual feedback for hits
- **Animation System**: Smooth character and enemy animations

### Audio Features
- **Sound Effects**: Weapon sounds, enemy deaths, UI feedback
- **Dynamic Audio**: Positional audio for immersive experience
- **Volume Control**: Adjustable audio settings

### Quality of Life
- **High Score Tracking**: Persistent score records
- **Progressive Saving**: Automatic progress preservation
- **Pause Functionality**: Game can be paused/resumed
- **Responsive UI**: Adapts to different screen sizes
- **Accessibility**: Gamepad support for different input needs

## 📊 Game Statistics

- **Current Levels**: 2 completed levels
- **Enemy Types**: Zombies, Skeletons
- **Weapon Types**: 5 different weapons
- **Character Variants**: Multiple character designs
- **Mobile Ready**: Full mobile device support
- **File Size**: ~330KB (complete game)

## 🔧 Customization

### Adding New Weapons
Weapons are defined in the JavaScript section with properties for damage, ammo, and behavior.

### Creating New Levels
Levels are configured in the `gameLevel` object with objectives and completion conditions.

### Modifying Characters
Character graphics are defined in SVG format within the `playerBodyParts` object.

### Adjusting Difficulty
Enemy spawn rates and health values can be modified in the configuration constants.

## 🐛 Known Issues
- None currently reported

## 🚧 Planned Features
- Additional levels and environments
- New enemy types and bosses
- Weapon upgrade system
- Multiplayer support
- Achievement system
- Sound track integration

## 📝 Version History
- **Latest**: Character design improvements, main menu enhancements
- **Previous**: Level 2 implementation, building system, wall mechanics
- **Earlier**: Core game mechanics, zombie AI, weapon systems

---

**Ready to start developing the next blockbuster features?** Let's plan the next steps together! 🎮