# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:

### Project Title or Name of the Application	: 60 SECONDS
### Section			   	      : 9 - Strontium
### Group Members			    : DORONILA, MALLARI, PUA
### Date (Proposal Date)  : Nov 21, 2026

### Project Description:

- 60 SECONDS is a game in which the player is trapped in a spaceship that was hit by an asteroid, with only 60 seconds left until the ship self-destructs. This is a text role play game purely for entertainment purposes, loosely based off the movie Oxygen (2021).
- The player's main goal is to stop the spaceship from self-destruction, but in order to do that, they would have to navigate through various rooms and make decisions regarding what to do or where to go, with each decision costing 5 seconds. 
- There are 5 possible endings to acquire: the $\color{red}{\text{BAD}}$ ending, $\color{green}{\text{GOOD}}$ ending, $\color{gray}{\text{MID}}$ ending, $\color{yellow}{\text{ETERNAL}}$ ending, and a secret $\color{purple}{\text{CHUD}}$ ending. Can you discover each every one of them?
- Our target audience is preferably those aged above 7, but it would most likely be bored Redditors finding a short sci-fi webgame to waste their time on.

### Classes:
  - $\color{teal}{\text{Player}}$: Controls the game, navigates through the rooms
  - $\color{coral}{\text{Timer}}$: Keeps track of the time, deducts time per decision
  - $\color{purple}{\text{Room}}$: Interactive rooms that the player navigates through 
  - Subclasses of Room:
    - $\color{yellow}{\text{Control Room}}$: What can the player do? - Access a riddle and input the three-digit code to stop the spaceship from self-destruction
    - $\color{yellow}{\text{Bunker Room}}$: What can the player do? - Wake up from their slumber or sleep again
    - $\color{yellow}{\text{Suit Room}}$: What can the player do? - Acquire space suit and exit the spaceship

### UML Class Diagram:
<img width="1182" height="1128" alt="image" src="https://github.com/user-attachments/assets/eaeeff94-1938-4138-bf5c-f815b92e9953" />

### Our long term outcomes for our project includes: 
- High replayability and community engagement
- Accessible entertainment

### Objectives:
- Objective 1: Build a turn-based countdown and navigation system
- Objective 2: Design branching scenarios and multiple endings
- Objective 3: Deliver an accessible, engaging sci-fi experience
