**BlackJack Simulation**

This project is a simulation of the classic card game BlackJack using different strategies for gameplay. It demonstrates object-oriented principles and various design patterns in Java.

**Features**

Multiple Game Strategies: The simulation implements several strategies for playing BlackJack, including:
**BlackjackStrategy**, 
**Hit21Strategy**, 
**RandomStrategy**, 
**StringBlackjackStrategy**, \br
Graphical Display: The game interface includes visual elements like cards and tips using Java's Swing components (MainFrame, DeckPanel, ImagePanel, etc.).
Custom Deck: Includes custom deck handling and shuffling through classes like Deck and StandardDeck.
Files in the Project

**Game Logic:**

**BlackJackSimu.class**: Main class running the BlackJack simulation.
**BlackjackStrategy.class**: Abstract strategy class for defining how players interact with the game.
**Card.class**: Represents a card in the deck.
**Deck.class**: Handles deck management, including dealing cards.
**StandardDeck.class**: Implements a standard deck of 52 cards.

**UI Components:**

MainFrame.class: The main graphical frame for the simulation.

DeckPanel.class, ImagePanel.class: Panels displaying cards and other visual elements.

TipDisplay.class: Displays game tips.

**Game Strategies:**

Hit21Strategy.class: A strategy where the player aims to hit 21.

RandomStrategy.class: A random decision-making strategy.
