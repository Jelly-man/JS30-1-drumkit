﻿# JS30-1-drumkit

# JS Drum Kit
![image](https://github.com/user-attachments/assets/070b1176-d772-4a66-acd3-13fbfb439976)


This is a simple JavaScript Drum Kit project from wes bos js 30, that lets you play different drum sounds by pressing specific keys on the keyboard. Each key press triggers both the sound and a visual highlight for the corresponding key.

## Features

- Play 9 different drum sounds using the keyboard.
- Visual feedback with key animation when pressed.
- Smooth key transition effects.
- Background image to enhance the UI.

## How to Use

1. Clone or download the repository.
2. Open the `index.html` file in a browser.
3. Press the following keys to play the corresponding sounds:
   - **A**: Clap
   - **S**: Hi-hat
   - **D**: Kick
   - **F**: Open-hat
   - **G**: Boom
   - **H**: Ride
   - **J**: Snare
   - **K**: Tom
   - **L**: Tink

## Project Structure

- `index.html`: The main HTML file that defines the layout and structure of the drum kit.
- `style.css`: The CSS file that styles the layout, adds animations, and enhances the overall design.
- `sounds/`: The folder containing the audio files for each drum sound.

## CSS Highlights

- **Responsive Design**: The drum kit is centered both horizontally and vertically using Flexbox (`align-items` and `justify-content`).
- **Animations**: Keys scale up and change color when pressed using a `playing` class, with transitions for smooth effects.
- **Background**: A custom background image is used to create a visually appealing look, with `background-size: cover` to ensure it fits well on different screens.

## Setup

1. Ensure all necessary assets like sound files (`sounds/*.wav`) and background image (`background.jpg`) are available.
2. Open `index.html` in any modern browser to use the drum kit.
