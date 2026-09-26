# NTUpoly 🎲

An NTU-themed Monopoly-style board game built with **HTML, CSS and JavaScript**.

NTUpoly is an interactive two-player board game inspired by classic property-trading games, redesigned around **Nottingham Trent University (NTU)**. Players can move around the board, purchase properties, collect rent, trade properties, manage their finances and use special cards while competing to build the strongest position.

The game also includes selectable time limits, player customisation, interactive menus and a range of game-management mechanics.

## 🎮 Features

- 👥 **Two-player gameplay**
- 🎲 Interactive dice system
- 🏫 NTU-themed properties and locations
- 💷 Property purchasing and rent collection
- 🏠 Houses and hotels
- 🔄 Property trading between players
- 🏦 Mortgage system
- 🃏 Joker / special event cards
- 🚔 Course Leader's Office as the game's jail-style location
- ⏱️ Timed game modes
- 👤 Player name, token and colour selection
- 💰 Player cash and property management
- 🎵 Background music
- 📖 Interactive rules and game instructions
- 🪟 Dynamic modals and game feedback
- 🎯 Turn-based gameplay and player state management

## 🏫 NTU-Themed Board

The traditional Monopoly-style board has been adapted around Nottingham Trent University.

Properties and locations are based on areas and buildings associated with NTU, creating a university-themed version of the traditional property-trading game.

Examples include:

- Benenson
- Biomedical Sciences
- CELS
- Engineering
- ISTeC
- Other NTU-inspired locations

The project combines familiar board-game mechanics with university-specific locations to create a more personalised gameplay experience.

## ⏱️ Timed Game Modes

Players can select different game durations before starting:

- **5 minutes**
- **10 minutes**
- **20 minutes**
- **30 minutes**

When the selected time expires, the game calculates the players' remaining assets and uses them to determine the final result.

This provides a shorter alternative to traditional board-game sessions and makes the game suitable for quick multiplayer gameplay.

## 💰 Property Management

Players can manage properties throughout the game by:

- Purchasing available properties
- Paying rent when landing on another player's property
- Collecting rent from opponents
- Developing properties with houses and hotels
- Trading properties
- Mortgaging properties
- Managing available cash

These systems require the game to continuously track player balances, ownership and property states.

## 🃏 Special Cards

NTUpoly includes special cards that introduce additional events and gameplay changes.

These cards add an element of unpredictability and require players to react to different situations during the game.

## 👤 Player Setup

Before starting a game, players can configure their characters, including:

- Player names
- Tokens
- Player colours
- Game duration

The setup system then initialises the game state based on the selected options.

## 🛠️ Technologies Used

- **HTML5** – Page structure and game interface
- **CSS3** – Layout, styling and responsive interface design
- **JavaScript** – Game logic, state management and interactive functionality

## ⚙️ JavaScript Functionality

The main game logic is implemented in `script.js`.

The JavaScript manages:

- Player state
- Property ownership
- Player movement
- Dice rolls
- Turns
- Cash balances
- Rent calculations
- Property purchases
- Property development
- Mortgages
- Property trading
- Special cards
- Game timers
- Game-ending conditions
- Modal interactions
- UI updates

This makes the project a practical example of using JavaScript to manage a relatively large interactive application and multiple interconnected game systems.

## 📁 Project Structure

```text
NTUpoly/
│
├── index.html
├── style.css
├── script.js
└── [game assets]
```

### Main Files

**`index.html`**  
Contains the structure of the game interface and board.

**`style.css`**  
Controls the visual design, layout and presentation of the game.

**`script.js`**  
Contains the main game logic and interactive functionality.

## 🚀 How to Run

NTUpoly is a browser-based project and does not require any additional frameworks or dependencies.

### 1. Clone the repository

```bash
git clone https://github.com/Arda-Sevgi/NTUpoly.git
```

### 2. Open the project

Open the project folder and launch:

```text
index.html
```

### 3. Start playing

Follow the on-screen instructions to configure the players and begin the game.

For the best experience, run the project using a local development server such as **VS Code Live Server**.

## 🎯 Learning Objectives

This project was developed to strengthen practical programming and web development skills.

Key areas of learning included:

- JavaScript programming
- DOM manipulation
- Event handling
- Managing complex application state
- Conditional logic
- Functions and reusable code
- Arrays and objects
- Game logic implementation
- User interface interaction
- Dynamic content updates
- Timer-based functionality
- Debugging and problem-solving
- Structuring a larger front-end project

## 💡 Challenges

One of the main challenges of the project was managing the interaction between multiple game systems.

For example, a player's actions can affect several parts of the game at the same time. Purchasing a property can change ownership, cash balance, available actions and future rent calculations.

The project therefore required careful handling of game state and event-driven interactions to keep the interface and underlying game logic synchronised.

## 🔮 Possible Future Improvements

Potential future improvements include:

- Adding AI-controlled players
- Improving mobile and tablet support
- Adding more NTU locations
- Expanding the special-card system
- Adding persistent game saves
- Adding online multiplayer
- Improving animations and visual effects
- Adding sound effects for game events
- Introducing player statistics and game history

## 📚 Project Purpose

NTUpoly was created as a practical web development project to apply programming concepts in a larger interactive application.

Rather than building a collection of isolated examples, the project combines **HTML, CSS and JavaScript** to create a complete browser-based game with interconnected systems, user interaction and dynamic state management.

## 👨‍💻 Author

**Arda Sevgi**

Built as a web development and programming project.
