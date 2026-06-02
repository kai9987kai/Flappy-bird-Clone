# Neo Flap — Advanced Canvas Game

Neo Flap is a polished, single-file browser game inspired by classic flap-style arcade games. It upgrades a simple canvas prototype into a smoother, more complete experience with menus, scoring, particles, animated backgrounds, mobile controls, sound effects, practice mode, and progressive difficulty.

## Features

- Single-file HTML game
- Smooth canvas rendering
- Frame-rate independent physics
- Start menu and game-over screen
- Score, level, and best-score tracking
- Best score saved in `localStorage`
- Pause, resume, mute, and restart controls
- Keyboard, mouse, and mobile tap support
- Animated sky, clouds, stars, hills, and floor
- Particle bursts and trail effects
- Screen shake and flash feedback on crashes
- Sound effects using the Web Audio API
- Practice mode with slower speed and more forgiving crashes
- Progressive difficulty with faster gates and tighter gaps
- Responsive layout for desktop and mobile browsers

## How to Play

Open `neo-flap-advanced.html` in a web browser.

### Controls

| Action | Control |
|---|---|
| Flap | Space, Arrow Up, click, or tap |
| Pause / Resume | `P` or Pause button |
| Restart | `R` or Restart button |
| Mute / Unmute | `M` or Sound button |

## Game Modes

### Normal Mode

Normal arcade mode. Crashing into a gate or the floor ends the run. Your best score is saved locally in the browser.

### Practice Mode

A gentler mode with slower movement, wider gaps, and forgiving crashes. Useful for testing or learning the controls.

## File Structure

This project is intentionally simple:

```text
neo-flap-advanced.html
README.md
```

Everything needed to run the game is inside the HTML file:

- HTML structure
- CSS styling
- Canvas game logic
- Web Audio sound effects
- Local storage best-score saving

No build tools, package managers, frameworks, or external dependencies are required.

## Running Locally

Download or clone the project, then open the HTML file directly:

```bash
open neo-flap-advanced.html
```

On Windows, you can simply double-click the file.

You can also serve it locally:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000/neo-flap-advanced.html
```

## Browser Support

Neo Flap should work in modern browsers that support:

- HTML5 Canvas
- JavaScript ES6
- Web Audio API
- Local Storage
- Pointer Events

Recommended browsers:

- Chrome
- Edge
- Firefox
- Safari

## Customisation Ideas

You can easily modify the game by editing constants inside the script.

Ideas:

- Change the bird design
- Add collectible coins
- Add power-ups
- Add different worlds or themes
- Add skins and unlockables
- Add a leaderboard
- Add moving pipes
- Add boss-style obstacle waves
- Add accessibility options
- Add a settings menu
- Add touch-only UI for mobile
- Add sprite images instead of canvas-drawn shapes

## Possible Future Improvements

- Online leaderboard
- Character selection
- Daily challenge mode
- Procedural weather effects
- Achievement system
- Saveable settings
- Better accessibility mode with reduced motion
- Custom difficulty sliders
- Progressive music system
- PWA support for installable mobile play

## Credits

Original prototype concept: simple canvas flap game.

Advanced version: redesigned and expanded into a full browser game with modern UI, responsive input, better physics, visual effects, and improved gameplay structure.

## License

Use, remix, and modify freely. Add your preferred license if publishing the project publicly.
