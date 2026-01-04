# Color Code (Code Breaker)

This is a simple iOS game built with **SwiftUI**.
The project was created as a learning exercise to practice **SwiftUI**, basic game logic, and separation of model and view, following the style taught in Stanford’s **CS193p** course.

---

## 🎮 Game Rules

- The system randomly generates a hidden code consisting of **4 colors**
- Available colors:
- Colors may repeat
- The player selects 4 colors as a guess each turn

### Feedback

- ⚫ **Black peg (Exact)**: correct color in the correct position
- ⚪ **White peg (Inexact)**: correct color but wrong position
- The position of feedback pegs does not correspond to specific colors, only the count matters

---

## 🕹 How to Play

- Tap a colored square to cycle through the available colors
- Tap the **Guess** button to submit the current guess
- Each attempt is shown with black and white feedback pegs
- The game is won when all 4 pegs are black

---

## 🧱 Project Structure

- `CodeBreaker`  
  - The main game model that manages the secret code, guesses, and attempts
- `MatchMarkers`  
  - An enum representing match results (`exact`, `inexact`, `nomatch`)
- `CodeBreakerView`  
  - The SwiftUI view that displays the game and handles user interaction

---
