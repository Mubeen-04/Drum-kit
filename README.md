# Drum Kit

The Drum Kit website offers a fun and interactive virtual drumming experience. Users can play different drum sounds by clicking on buttons or pressing specific keys on their keyboard.

## Features

- **Interactive Drum Buttons:** Click on the drum buttons labeled `w`, `a`, `s`, `d`, `j`, `k`, `l` to play different drum sounds.
- **Keyboard Control:** Play drum sounds by pressing the corresponding keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`).
- **Sound Effects:**
  - `w` - Tom 1
  - `a` - Tom 2
  - `s` - Tom 3
  - `d` - Tom 4
  - `j` - Snare
  - `k` - Crash
  - `l` - Kick Bass
- **Visual Feedback:** Buttons animate to show they are pressed.

## How It Works

- **Event Listeners:** JavaScript adds event listeners to drum buttons for `click` events and to the document for `keydown` events.
- **Sound Function:** The `makeSound` function plays the corresponding audio file based on the button clicked or key pressed.
- **Animation Function:** The `buttonAnimation` function adds a "pressed" class to the button for visual feedback, which is removed after a short delay.

## Screenshots
![Screenshot (61)](https://github.com/Mubeen-04/Drum-kit/assets/172309170/8499f582-71b6-48df-bc48-75f0662e647c)


