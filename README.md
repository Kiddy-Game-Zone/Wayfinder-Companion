# Wayfinder's Companion 🧭👨‍🦯🏠

Welcome to **Wayfinder's Companion**! Embark on a heartwarming journey as you guide a visually impaired man safely to his home through a series of invisible mazes. This game challenges your sense of direction and empathy, using subtle audio-visual cues to help you navigate.

## 💖 About The Game

In Wayfinder's Companion, you become the unseen guide for a man trying to find his way. The paths are hidden, and you must rely on "hot" and "cold" feedback—both visual (color changes of the character) and textual—to determine if you're on the right track. With 12 progressively challenging levels, your task is to carefully drag the man across the screen, navigating the unseen twists and turns until he reaches the safety of his house.

✨ **Can you be the reliable companion he needs?** ✨

## 🚀 Features

* **❤️ Heartwarming Theme:** Guide a visually impaired man to his destination.
* **❓ Invisible Mazes:** Paths are hidden, testing your intuition and reliance on feedback.
* **📈 12 Progressive Levels:** Difficulty increases with longer, more complex mazes and subtler feedback cues.
* **🔥 "Hot & Cold" Feedback System:**
    * Character color changes (warm/cold hues).
    * Descriptive text messages to indicate proximity to the path.
* **🔊 Immersive Sound Design:**
    * Subtle sound when starting to drag the character.
    * Click sounds for all interactive buttons.
    * A cheerful jingle and sparkle animation upon level completion.
    * 🔇 Mute/Unmute option for all game sounds (state saved in `localStorage`).
* **🎨 7 Beautiful Themes:** Customize your gaming experience with a variety of visual styles:
    * Default (Playful Bright) ☀️
    * Dark Mode 🌙
    * Sunset Glow 🌅
    * Forest Whisper 🌲
    * Ocean Deep 🌊
    * Candy Pop 🍭
    * Retro Arcade 👾
* **📱 Fully Responsive Design:** Play seamlessly on any device – desktop, tablet, or mobile!
* **👨‍🦯 Enhanced Character & House Visuals:** Clearer, more thematic icons for the man and his house.
* **🎉 Animated Celebrations:** Enjoy a small visual flourish when a level is successfully completed.

## 🕹️ How to Play

1.  **Open the Game:** Launch the `index.html` file in your web browser.
2.  **Select a Theme (Optional):** Use the theme selector in the top-right corner.
3.  **Toggle Sound (Optional):** Click the 🔈/🔇 button in the game header to mute or unmute sounds.
4.  **Start the Game:** Click the "Start Game ✨" button. This will begin Level 1.
5.  **Understand the Goal:** Your objective is to drag the man icon from the starting marker to his house (which is invisible until you reach it).
6.  **Drag to Navigate:** Click and drag the man icon across the canvas.
7.  **Listen to Feedback:**
    * The **color of the man** will change: warmer colors (like orange/yellow) mean you're close to the path, colder colors (like blue) mean you're off track.
    * The **text message** in the feedback area will also guide you (e.g., "He's on the right path! (Hot 🔥)", "A bit chilly, adjust course. 🥶").
8.  **Reach the Destination:** When the man gets close enough to the hidden house location:
    * A celebratory sound will play.
    * A sparkle animation will appear around the now-visible house.
    * The feedback message will confirm level completion.
9.  **Progress:**
    * Click "Next Level ➡️" to proceed (appears after the celebration).
    * Click "Restart Level 🔄" if you get stuck on the current level.
    * If you've started the game, the main button becomes "Restart Game 🔄" to start over from Level 1.
10. **Complete All Levels:** Guide the man through all 12 levels to win the game! A final congratulatory message will appear.

## 🛠️ Technologies Used

* **HTML5:** For the core structure of the game page.
* **CSS3:** For all styling, animations, the beautiful themes (utilizing CSS Variables, Flexbox, and Grid).
* **JavaScript (Vanilla JS):** For the main game logic, UI interactions, and theme/mute state management with `localStorage`.
* **p5.js:** A JavaScript library for creative coding, used here for:
    * Rendering the game canvas, player (man), start/end points (house).
    * Handling mouse interactions for dragging.
    * Implementing the invisible maze logic and proximity detection.
    * Drawing the level completion sparkle animation.
* **Tone.js:** A Web Audio framework, used for:
    * Generating button click sounds.
    * Creating the level completion jingle.
    * The subtle drag-start sound.
* **Tailwind CSS:** Used via CDN for some utility classes to assist with layout and styling.
* **Google Fonts:** For the 'Inter' font.

## 🔮 Future Enhancements (Ideas)

* **🗺️ More Complex Maze Generation:** Implement algorithms for procedurally generated mazes for infinite replayability.
* **🐾 Path Preview (Optional/Hint):** A brief flash of the path at the start of a level or as a hint.
* **⏱️ Time Challenge:** Add a timer for each level or overall game completion.
* **🌟 Star Rating System:** Award stars based on how efficiently the player completes a level (e.g., fewest "off-path" movements).
* **🦯 Accessibility Features:** Explore further enhancements for actual accessibility, beyond the game's theme.

---

<p align="center">
  © 2025 ToolForge. All rights reserved. Built with ❤️ by Anas.
</p>
