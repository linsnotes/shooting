# Language Marksman

**Language Marksman** is an interactive, web-based game that combines language learning with arcade-style shooting gameplay. Players must match a given word with its correct translation by aiming and firing at moving targets.

## Demo
- **Try out the live demo of Language Marksman at:**  
[Language Marksman](https://linsnotes.com/shooting)


## Features

- **Interactive Gameplay:**  
  Control the shooter using keyboard arrows or on-screen mobile controls. Fire bullets with the spacebar (or touch) to hit targets.

- **Quiz-based Challenge:**  
  The game displays a word (question) on the shooter. Multiple moving targets show potential answers. Hit the correct target to score points.

- **Custom & Built-in Games:**  
  Choose from a list of built-in quizzes or enter a custom Google Sheet ID to load your own game data.

- **Real-Time Scoring:**  
  Points are awarded based on your response time and accuracy. Bonus points are given for hitting the target on the first try.

- **Responsive Design:**  
  Enjoy the game on both desktop and mobile devices.

## How It Works

1. **Landing Screen:**  
   - Select a built-in game from the dropdown menu or enter a custom Google Sheet ID provided by your teacher.
   - Start the game by clicking the corresponding button.

2. **Name Screen:**  
   - Enter your name to personalize your gaming experience.

3. **Quiz Screen:**  
   - The shooter displays a word (the question) while several targets (potential answers) move across the screen.
   - Use arrow keys (or mobile controls) to position the shooter and press the spacebar (or tap the fire button) to shoot.
   - The game awards points based on how quickly and accurately you hit the correct target.

4. **Results Screen:**  
   - After finishing the quiz, your overall score, correct answers, and attempt details are shown.
   - Optionally, take a screenshot of your results.

## Setup & Usage

### Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- An Internet connection to load external resources (such as Font Awesome, SweetAlert2, XLSX, and html2canvas).

### Running the App

1. **Clone or Download the Repository:**
   - Download the files to your local machine.

2. **Open the App:**
   - Simply open the `index.html` file in your web browser.

### Custom Game Data

- **Google Sheet Format:**
  - The first row should include the quiz title in cell A1.
  - Cell C1 specifies the number of target options (default is 4 if left empty or invalid).
  - Cell D1 (optional) enables unlimited bullets if it contains any text.
  - Subsequent rows should contain the quiz data:
    - Column A: The question word.
    - Column B: The correct answer (match word).

- **Sharing the Sheet:**
  - Make sure the Google Sheet is publicly accessible so that the game can fetch the data.

## File Structure

- **index.html:**  
  Contains the HTML, embedded CSS, and JavaScript that power the game.

- **External Libraries (via CDN):**
  - Font Awesome
  - SweetAlert2
  - XLSX
  - html2canvas
  - GoatCounter (for visitor tracking)

## Credits

- **Game Design & Development:**  
  Developed by [Your Name or Organization].

- **External Resources:**  
  - [Font Awesome](https://fontawesome.com/)
  - [SweetAlert2](https://sweetalert2.github.io/)
  - [XLSX](https://github.com/SheetJS/sheetjs)
  - [html2canvas](https://html2canvas.hertzen.com/)
  - [GoatCounter](https://www.goatcounter.com/)

## License

[MIT license](LICENSE)
