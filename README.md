# Angular Wordle Game

A clone of the popular Wordle word-guessing game built using the Angular framework. This project recreates the essential logic and user experience of Wordle, offering a fast, interactive, and responsive gameplay experience entirely on the frontend.

##  Project Objective

The goal of this project is to practice Angular development by replicating the core features of Wordle:
- 5-letter word guessing game
- Daily word rotation or static word bank
- Real-time feedback on guesses
- Keyboard input and UI keyboard
- Clean and modular Angular architecture

---

##  Features

- Fully functional Wordle clone
- Built with Angular and TypeScript
- Local word dictionary (no backend dependency)
- Responsive layout and minimal design
- Modular components:
  - Main game logic
  - Virtual keyboard
  - Word evaluation engine
- Easy to extend with new features (e.g., difficulty levels, themes)

---

##  Project Structure

```
src/
├── app/
│   ├── main/          # Main gameplay logic and layout
│   ├── navbar/        # Top navigation component
│   ├── words.ts       # Word list used for guesses
│   ├── app.module.ts  # Angular module setup
│   └── app.component* # Root application component
├── assets/            # Static assets (currently unused)
├── environments/      # Dev/prod config
├── index.html         # Root HTML file
└── styles.css         # Global styles
```

---

## ️ Installation

Follow these steps to set up the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/mrkankilic27/angular-wordle-game.git

# 2. Navigate into the project directory
cd angular-wordle-game

# 3. Install dependencies
npm install

# 4. Run the development server
ng serve
```

Then open your browser and visit:  
**http://localhost:4200**

---

##  Usage

- Type your 5-letter guess using the physical keyboard or the on-screen keyboard.
- Letters will change color to indicate:
  - 🟩 Correct letter, correct position
  - 🟨 Correct letter, wrong position
  - ⬜️ Incorrect letter
- You have a limited number of attempts to guess the word correctly.

---

##  Built With

- [Angular](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [HTML5 & CSS3](https://developer.mozilla.org/)

---

##  Future Improvements

- Daily word logic (date-based)
- Animated transitions
- Shareable game results
- Light/Dark theme toggle
- Mobile optimization and gestures
- Multiplayer support

---

##  Developer Info

**Mertcan Kankılıç**  
Computer Engineer  
Email: [mertcankankilic27@gmail.com](mailto:mertcankankilic27@gmail.com)  
GitHub: [@mrkankilic27](https://github.com/mrkankilic27)

---

##  License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute it for personal or commercial purposes.

---

##  Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  
Make sure to update tests as appropriate.

---

Thank you for checking out the Angular Wordle Game!
