# Morse Code Learner

An interactive web app for learning Morse code through audio and visual feedback.

**[Try it live](https://jrjr.github.io/morsecode_decode/)**

## Features

- **Character Grid** — Click any letter (A–Z) or number (0–9) to hear its Morse code
- **Text Playback** — Type a word or sentence and play it as Morse code
- **Visual Feedback** — Flashing light indicator and highlighted characters during playback
- **Speed Control** — Adjustable playback speed from 5–30 WPM

## How It Works

The app uses the Web Audio API to generate 700 Hz sine wave tones for dots and dashes, following standard Morse code timing:

- **Dot** = 1 unit
- **Dash** = 3 units
- **Intra-character gap** = 1 unit
- **Inter-character gap** = 3 units
- **Word gap** = 7 units

## Usage

No build step required — just open `index.html` in a browser, or visit the [live site](https://jrjr.github.io/morsecode_decode/).
