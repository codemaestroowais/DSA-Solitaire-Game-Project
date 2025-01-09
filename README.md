											****Overview****
Welcome to the digital version of Solitaire! This game is built using Pygame and follows the Klondike variation of Solitaire, where your objective is to move all the cards to four foundation piles, each representing a suit (Hearts, Diamonds, Clubs, and Spades).

										-------Features-------

											***Gameplay***


1-)Standard Deck: The game uses a deck of 52 cards.
2-)Tableau Setup: The cards are arranged into 7 columns, with the top card face-up.
3-)Moving Cards: You can move cards between tableau columns, the stockpile, or the foundation piles, following the traditional Solitaire rules.
4-)Valid Moves: Cards in the tableau must be arranged in descending order (King to Ace) and must alternate between red and black (Hearts/Diamonds are red; Clubs/Spades are black).
5-)Winning Condition: The game is won when all cards are successfully placed in the foundation piles, organized in ascending order (Ace to King).

										***User Interface***


1-)Main Menu: Start a new game, check the game instructions (Help), or quit the game.
2-)Game Screen: Displays the tableau, the foundation piles, the stockpile.
3-)Help Screen: Learn how to play the game and understand the rules.
4-)Victory Screen: Celebrate your win with an animated victory screen once you successfully complete the game.

										***Statistics Display***


1-)Time: Displays the amount of time that has passed since you started the game.
2-)Moves: Tracks the number of moves you’ve made.
3-)Score: Your score increases with each valid move you make during gameplay.
4-)FPS: The entire game is working at the 120 frame per second speed.
5-)Music: Also the music is added behind the game so that the user can deeply enjoy it.

											***Installation***


1-)Download the Game Files: Clone the repository or download the files.
2-)Set Up Python and Install Pygame: Ensure that you have Python 3.x or more version installed on your computer. You can check your Python version by running this command:
python --version
If you don’t have Pygame installed, you can easily install it with pip:
pip install pygam
3-)Add the Required Assets: You’ll need the following image files in the appropriate directories for the game to work correctly:
Pictures/Heart.png: Image for the Heart suit card.
Pictures/Diamond.png: Image for the Diamond suit card.
Pictures/Club.png: Image for the Club suit card.
Pictures/Spade.png: Image for the Spade suit card.
Pictures/Background.jpg: Background image for the game screen.
Pictures/MainScreen.png: Background image for the main menu.
Pictures/Rules.png: Image for the help page with instructions.
Pictures/YOUWon0.png and Pictures/YOUWon1.png: Animation frames for the victory screen.
Pictures/Sound.mp3: Background music for the game.
Running the Game: Once everything is set up, simply run the game by executing the Frontend.py
python Frontend.py

												***Controls***


1-)Mouse: Click and drag the cards to move them around the screen.
2-)Back Button: While playing, you can click the “Back” button to return to the main menu.

												----Game Flow----

												 ***Main Menu***


1-)Start Playing: Press this to begin a new game.
2-)Help: Click here to view the game instructions.
3-)Exit Game: Exit the game if you want to quit.

												 ***Game Play***


Move Cards: Drag and drop cards between tableau columns, the stockpile, and the foundation piles.
In the tableau, you need to stack cards in descending order (alternating colors).
In the foundation piles, cards must be placed in the correct suit order, from Ace to King.

													***Winning***


Winning the Game: You win when all four foundation piles are completed, with the cards placed from Ace to King.
Victory Screen
Celebrate: When you win, the victory screen will show a fun animation to celebrate your success.

													----Development----


This game is built using Pygame for the graphical user interface and essential game logic. The backend logic is implemented using Python classes that manage the cards, tableau, stockpile, and foundation piles.
Files
Frontend.py: The main script to run the game.
BackEnd.py: Contains all the core logic for the game, including the classes for PlayingCard, DeckOfCards, Foundation, Tableau, Stack, and Stockpile.
License
This project is open-source, released under the MIT License. You’re free to contribute, use it, or modify it for educational purposes.
Contact
If you have any questions, suggestions, or feedback, feel free to contact me at 'ovas3853@gmail.com'.
Enjoy the game and good luck! 🃏
