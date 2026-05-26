# Simon Says Game 🎮

A classic, interactive memory-testing game built entirely using front-end web technologies. The game generates a random sequence of colors and flashes them. The player must remember and replicate the exact sequence by clicking the buttons in the correct order to level up. As the levels increase, the sequence grows longer and faster!

## 🚀 Live Demo
You can play the live version of the game here: **[Insert your GitHub Pages Link Here]**

## ✨ Features
* **Dynamic Gameplay:** Generates an infinite random sequence using JavaScript.
* **Visual Feedback:** Distinct animations and state changes using unique CSS classes (`gameflash` vs `userflash`).
* **Responsive Grid Layout:** Built using clean CSS Flexbox structure for a modern 2x2 grid layout.
* **Keyboard Initiation:** Smooth user experience allowing the game to start instantly with any keypress.

## 🛠️ Technologies Used
* **HTML5:** Structures the game interface and layout containers.
* **CSS3:** Handles custom styling, colors, 2x2 grid arrangement, and smooth transition animations.
* **JavaScript (ES6):** Controls the game logic, state management, tracking arrays, random indexing, and DOM manipulation.

## 🕹️ How to Play
1. **Start the Game:** Press any key on your keyboard to begin.
2. **Watch the Sequence:** The system will flash a button white (`gameflash`). Remember it!
3. **Repeat the Steps:** Click the corresponding button. A user click triggers a red flash (`userflash`).
4. **Advance:** If you match the sequence successfully, you advance to the next level, and the game appends a new random color to the chain.
5. **Game Over:** If you click the wrong button, the game ends, displays your final score, and allows you to restart by pressing any key.

## 📂 File Structure
* `index.html` - The structural markup of the page.
* `style.css` - Custom styling rules, colors, and keyframe animations.
* `app.js` - Core event listeners, state arrays, and logical execution functions.