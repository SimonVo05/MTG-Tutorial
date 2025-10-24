# Magic Tutorial Game

An interactive **Magic: The Gathering–style card game** built with **C++ and Qt**  
This project simulates a turn-based battle system where players can draw, play, and interact with cards while the game enforces rules and phases.

---

## Features

- **Card Rendering and Interaction**  
  Players can view their hand, tap lands for mana, cast spells, summon creatures, attack, and block.  

- **Turn and Phase Management**  
  Automated handling of phases and steps (draw, main, combat, etc.) with a clear turn/phase indicator.  

- **Stack System**  
  Implements the Magic stack for spells and abilities, allowing responses and priority passing.  

- **Undo Actions**  
  Supports undoing player actions when no hidden information is revealed.  

- **Bot Opponent**  
  Includes a simple AI bot for practice and testing.  

- **Card API Integration**  
  Fetches card data dynamically using a card API manager, extending variety beyond static definitions.  

- **UI/UX Enhancements**  
  Built with Qt, featuring a game board, dialogs, load screen, tooltips, and interactive feedback.  

- **Data Persistence**  
  Decks and card data stored in external text files for easy customization.  

- **Box2D Integration**  
  Physics-enabled drag-and-drop interactions and card layout management.


## Usage

- Start the game to load into the main menu.  
- Players can view their hand and battlefield.  
- Use mana by tapping lands, then cast creatures and spells.  
- Attack and block during combat phases.  
- Watch the stack resolve and progress through automated phases.  
- Optional: play against the included bot for single-player practice.  

---

## File Structure

- `card.cpp / card.h` – Card representation and logic  
- `deck.cpp / deck.h` – Deck building and management  
- `gamemanager.cpp / gamemanager.h` – Core game loop and rules handling  
- `gameboard.cpp / gameboard.h` – Board rendering and layout  
- `cardapimanager.cpp / cardapimanager.h` – API integration for card data  
- `bot.cpp / bot.h` – AI opponent logic  
- `Box2D/` – Physics engine for interactions  
- `additional_files/` – Decks and unique card definitions  

---

## Future Improvements

- Expand AI for smarter decision-making  
- Enhance multiplayer support  
- Add more visual effects and animations  
- Integrate full online API data for larger card sets  

---

## Authors

Developed by **Simon, Teagan, Zach and Chase** for CS3505.  
