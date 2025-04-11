# War card game
This is a Python implementation of the classic card game "War", using OOP principles.

## Technical Requirements
- The game must be implemented in **Python** using **OOP**.
- The code should be divided into **at least two classes**:
  - `Card`: Represents a playing card.
  - `Deck`: Represents the deck of cards.
- Use **Git** for version control and practice proper commit practices.
- Work using **remote pair programming** at some stages of the project.

### Functional Requirements
- The game should simulate the War card game between two players.
- The game continues until one player has all the cards or a predefined number of rounds is reached.
- Cards are compared by rank; the higher card wins the round and takes both cards.
- If both cards have the same rank, a "war" happens:
  - Each player places 1 card face down and 1 card face up.
  - The higher face-up card wins all the cards.
  - If the war results in another tie, repeat the war.
- The game should print out each round's result.
