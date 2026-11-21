# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:

### Project Title or Name of the Application	: 60 SECONDS
### Section			   	      : 9 - Strontium
### Group Members			    : DORONILA, MALLARI, PUA
### Date (Proposal Date)  : Nov 21, 2026

### Project Description:

### SUMMARY
- 60 SECONDS is a game in which the player is trapped in a spaceship that was hit by an asteroid, with only 60 seconds left until the ship self-destructs. This is a text role play game purely for entertainment purposes, loosely based off the movie Oxygen (2021).
- The player's main goal is to stop the spaceship from self-destruction, but in order to do that, they would have to navigate through various rooms and make decisions regarding what to do or where to go, with each decision costing 5 seconds.
- There are 5 possible endings to acquire: the $\color{red}{\text{BAD}}$ ending, $\color{green}{\text{GOOD}}$ ending, $\color{gray}{\text{MID}}$ ending, $\color{yellow}{\text{ETERNAL}}$ ending, and a secret $\color{purple}{\text{CHUD}}$ ending. Can you discover each every one of them?

### FEATURES & COMPONENTS
- The player owns a timer, which keeps track of the time, and it reduces time whenever the player makes decisions, such as interacting or moving through the rooms
- When the player is in a room, the player is given the name, description, and available exits of the room. And then, they are given the option to interact with it or move to another one. The player is able to move through the rooms in 4 directions, (North, East, South, and West) unless the chosen direction does not lead to a room. (see map attached on the bottom for further details)
- Each travel to the next room takes 5 seconds of the time, while other interactions may take much longer time, such as interacting with the entertainment room.
- There are 3 special rooms: the Suit Room, the Control Room, and of course, the Bunker Room. For the suit room, the space suit can be acquired by the player by interacting with the room, and the player is able to exit the spaceship in that same room. For the Control Room, the player is given a riddle by interacting with the room and is able to input a code to stop the spaceship from self-exploding. And lastly, the Bunker Room is where the player starts, where they are asleep at first, and once they wake up, they can interact with the room to sleep again.
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/ce3dc330-8e68-4af5-91c8-253440d0987d" />

### Target demographics:
- Preferably those aged above 7, but it would most likely be bored Redditors finding a short sci-fi webgame to waste their time on.

### Class Descriptions:
  - $\color{skyblue}{\text{Player}}$: Controls the game, navigates through the rooms
  - $\color{salmon}{\text{Timer}}$: Keeps track of the time, deducts time per decision
  - $\color{purple}{\text{Room}}$: Interactive rooms that the player navigates through 
  - Subclasses of Room:
    - $\color{#FEF08A}{\text{Control Room}}$: What can the player do? - Access a riddle and input the three-digit code to stop the spaceship from self-destruction
    - $\color{#FEF08A}{\text{Bunker Room}}$: What can the player do? - Wake up from their slumber or sleep again
    - $\color{#FEF08A}{\text{Suit Room}}$: What can the player do? - Acquire space suit and exit the spaceship

### UML Class Diagram:
<img width="1182" height="1128" alt="image" src="https://github.com/user-attachments/assets/eaeeff94-1938-4138-bf5c-f815b92e9953" />

### Our long term outcomes for our project includes
- High replayability and community engagement
- Accessible entertainment

### Objectives:
- Objective 1: Build a turn-based countdown and navigation system
- Objective 2: Design branching scenarios and multiple endings
- Objective 3: Deliver an accessible, engaging sci-fi experience
