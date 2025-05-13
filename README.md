# Three-Player Chess Implementation

## Overview
This project implements a rule-compliant digital version of three-player chess with a hexagonal board layout. The game adds triangular board geometry, multi-directional moving pieces, and dynamically converting alliances between players, filling the void of standardized implementations for this chess variant.

## Demo
Watch our demonstration video: [Demo Video Link](https://youtu.be/e7oyk8sMBRE)

## Features
- Hexagonal board layout for three-player gameplay
- Complete implementation of chess piece movement rules adapted for triangular geometry
- Move validation and highlighting of legitimate moves for selected pieces
- Game state tracking including checkmate, stalemate, and alliance victories
- Support for local multiplayer with 3 human players through sockets
- Visual display of moving pieces, captures, and turn sequence

## Technologies Used
- Node.js and Express.js for interface implementation
- Socket programming for local multiplayer support

## Installation

```bash
# Clone the repository
git clone https://github.com/sunnyallana/three-player-chess.git

# Navigate to the project directory
cd yourproject

# Install dependencies
npm install  # or other package manager command
```

## Usage

```bash
# Run the application
node app.js
```

## Challenges and Solutions
- **Complex Board Layout**: Implemented hexagonal grid using Shapely for geometric calculations
- **Rule Adaptation**: Formalized movement rules for chess pieces across triangular sections and multiple edges
- **Multi-player Turn Management**: Created a robust turn sequence system with state tracking

## Future Improvements
- Online multiplayer functionality
- AI opponents with adaptive difficulty
- Additional chess variants and rule modifications
- Tournament and ranking system

## Acknowledgements
- Project Advisor: Ma'am Almas Ayesha
- Chess.com community for three-player chess rule discussions
- References:
  - [Chess for 3 Players](https://www.chess.com/blog/Mortal_Michy/chess-for-3-players)
  - [Chess for Three People Forum](https://www.chess.com/forum/view/chess960-chess-variants/chess-for-three-people)
